<?php
//dashboard.php – Muestra las últimas lecturas de la base

$conn = new mysqli("localhost", "root", "", "iiot_sensores");

$result = $conn->query("SELECT sensor, valor, fecha FROM lecturas ORDER BY id DESC LIMIT 20");
?>

<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>Dashboard IIoT</title>
    <style>
        table { border-collapse: collapse; width: 100%; }
        th, td { border: 1px solid #ccc; padding: 8px; text-align: left; }
        th { background: #eee; }
    </style>
</head>
<body>
    <h1>Dashboard – Lecturas de sensores</h1>
    <table>
        <tr><th>Sensor</th><th>Valor</th><th>Fecha</th></tr>
        <?php while ($row = $result->fetch_assoc()): ?>
        <tr>
            <td><?php echo $row['sensor']; ?></td>
            <td><?php echo $row['valor']; ?></td>
            <td><?php echo $row['fecha']; ?></td>
        </tr>
        <?php endwhile; ?>
    </table>
</body>
</html>