<?php
$servername = "localhost";
$username = "root";
$password = "";
$dbname = "iiot_sensores";

// Crear conexión
$conn = new mysqli($servername, $username, $password, $dbname);

// Verificar conexión
if ($conn->connect_error) {
    die("Conexión fallida: " . $conn->connect_error);
}

// Recibir datos POST
$sensor = isset($_POST['sensor']) ? $_POST['sensor'] : '';
$valor = isset($_POST['valor']) ? $_POST['valor'] : '';

if (!empty($sensor) && !empty($valor)) {
    $stmt = $conn->prepare("INSERT INTO lecturas (sensor, valor) VALUES (?, ?)");
    $stmt->bind_param("ss", $sensor, $valor);

    if ($stmt->execute()) {
        echo "Datos guardados correctamente";
    } else {
        echo "Error al guardar en la base de datos: " . $stmt->error;
    }
    $stmt->close();
} else {
    echo "Faltan datos del sensor o valor";
}

$conn->close();
?>