<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Atividade const e let</title>
</head>
<body>

    <h1>Sistema com const e let</h1>

    <label>Digite seu nome:</label>
    <input type="text" id="nome"><br><br>

    <label>Digite sua idade:</label>
    <input type="number" id="idade"><br><br>

    <button onclick="mostrarDados()">Enviar</button>

    <h2 id="resultado"></h2>

    <script>
        function mostrarDados() {
            let nomeUsuario = document.getElementById("nome").value;
            let idadeUsuario = document.getElementById("idade").value;

            const mensagemFinal = "Se não muda, usamos const";

            document.getElementById("resultado").innerHTML =
                "Nome: " + nomeUsuario + "<br>" +
                "Idade: " + idadeUsuario + "<br><br>" +
                mensagemFinal;
        }
    </script>

</body>
</html>

