<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>inicio</title>
    <link rel="stylesheet" href="./css/style.css">

</head>
<body>
 
<div class="form-container">
    <h2>Formulário de Contato</h2>

    <form>
        <label for="nome">Nome:</label>
        <input type="text" id="nome" placeholder="Digite seu nome" required>

        <label for="email">E-mail:</label>
        <input type="email" id="email" placeholder="Digite seu e-mail" required>

        <label for="texto">Mensagem:</label>
        <textarea id="texto" rows="4" placeholder="Digite sua mensagem" required></textarea>

        <button type="button" onclick="enviarFormulario()">Enviar</button>
    </form>

    <p id="mensagem"></p>
</div>

<script src="./js/script.js"></script>
</body>
</html>
