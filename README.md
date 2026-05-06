<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Multiplicação de Números</title>
</head>
<body>

    <h1>Sistema de Multiplicação</h1>

    <label>Digite seu nome:</label>
    <input type="text" id="nome"><br><br>

    <label>Digite o primeiro número:</label>
    <input type="number" id="num1"><br><br>

    <label>Digite o segundo número:</label>
    <input type="number" id="num2"><br><br>

    <label>Digite o terceiro número:</label>
    <input type="number" id="num3"><br><br>

    <button onclick="calcular()">Calcular</button>

    <h2 id="resultado"></h2>

    <script>
        function calcular() {
            let nome = document.getElementById("nome").value;
            let num1 = Number(document.getElementById("num1").value);
            let num2 = Number(document.getElementById("num2").value);
            let num3 = Number(document.getElementById("num3").value);

            const multiplicacao = num1 * num2 * num3;

            document.getElementById("resultado").innerHTML =
                "Olá, " + nome + "! O resultado da multiplicação é: " + multiplicacao;
        }
    </script>

</body>
</html>
