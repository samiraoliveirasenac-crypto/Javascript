<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projeto - Tela de Login com Bootstrap</title>

    <!-- Bootstrap CDN -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

    <!-- CSS Externo -->
    <link rel="stylesheet" href="./css/style.css">
</head>
<body>

    <div class="container d-flex justify-content-center align-items-center vh-100">
        <div class="login-box shadow-lg p-5 rounded-4">

            <!-- Nome do Projeto -->
            <h2 class="text-center mb-2">Projeto</h2>

            <!-- Nome da Tela -->
            <h4 class="text-center mb-4">Tela de Login</h4>

            <form>
                <!-- Campo de E-mail -->
                <div class="mb-3">
                    <label for="email" class="form-label">E-mail</label>
                    <input 
                        type="email" 
                        class="form-control" 
                        id="email" 
                        placeholder="Digite seu e-mail"
                        required
                    >
                </div>

                <!-- Campo de Senha -->
                <div class="mb-4">
                    <label for="senha" class="form-label">Senha</label>
                    <input 
                        type="password" 
                        class="form-control" 
                        id="senha" 
                        placeholder="Digite sua senha"
                        required
                    >
                </div>

                <!-- Botão -->
                <button 
                    type="button" 
                    class="btn btn-primary w-100"
                    onclick="entrar()"
                >
                    Entrar
                </button>
            </form>

        </div>
    </div>

    <!-- JavaScript -->
    <script src="./js/script.js"></script>

</body>
</html>
