<?php
$host = "localhost";
$usuario = "root";
$senha = "senac";
$banco = "atividade20somas";
$porta = "3307";

$conexao = new mysqli($host, $usuario, $senha, $banco, $porta);

if (!$conexao) {
    die("Erro na conexão: " . mysqli_connect_error());
}
echo "Conexão realizada com sucesso!";

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Calculadora - Soma</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h2>Calculadora de Soma</h2>
        <form action="resultado.php" method="POST">
            <label for="num1">Primeiro número:</label>
            <input type="number" step="any" name="num1" required>

            <label for="num2">Segundo número:</label>
            <input type="number" step="any" name="num2" required>

            <button type="submit">Calcular Soma</button>
        </form>
    </div>
</body>
</html>


body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f9;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}

.container {
    background-color: #3c0303;
    padding: 30px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(203, 10, 10, 0.1);
    width: 300px;
    text-align: center;
}

h2 {
    color: #333;
    margin-bottom: 20px;
}

label {
    display: block;
    margin-bottom: 8px;
    text-align: left;
    font-weight: bold;
}

input {
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    border: 1px solid #ddd;
    border-radius: 4px;
    box-sizing: border-box;
}

button {
    width: 100%;
    padding: 10px;
    background-color: #28a745;
    color: white;
    border: none;
    border-radius: 4px;
    font-size: 16px;
    cursor: pointer;
}

button:hover {
    background-color: #218838;
}

.sucesso {
    color: green;
    font-size: 14px;
}

.destaque {
    font-size: 24px;
    color: #007bff;
}

a {
    display: block;
    margin-top: 15px;
    text-decoration: none;
    color: #0056b3;
}

