

<?php

$host = "localhost";
$usuario = "root";
$senha = "senac";
$banco = "atividade17soma";
$porta = "3307";

$conexao = new mysqli($host, $usuario, $senha, $banco, $porta);

if (!$conexao) {
    die("Erro na conexão: " . mysqli_connect_error());
}
echo "Conexão realizada com sucesso!";
?>

<?php 

include 'conexao.php';

$numero1 = 15;
$numero2 = 5;
$numero3 = 10;

$resultado = $numero1 + $numero2 + $numero3;

$sql =" INSERT INTO somas (numero1, numero2, numero3, resultado) VALUES ($numero1, $numero2, $numero3, $resultado)";
if ($conexao->query($sql)) {
    echo "<br> Dados da soma dos três números foram salvos com sucesso!";
} else {
    echo "<br> Erro ao salvar os dados da soma!";
}

?>
