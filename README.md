<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página de Login</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background-color: #3498db; /* Azul */
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }

        .login-container {
            background-color: #ffffff; /* Branco */
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .login-container h2 {
            color: #333;
        }

        .input-group {
            margin: 15px 0;
        }

        .input-group label {
            display: block;
            margin-bottom: 5px;
            color: #333;
        }

        .input-group input {
            width: 100%;
            padding: 8px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        .input-group button {
            background-color: #2ecc71; /* Verde */
            color: #fff;
            padding: 10px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
    </style>
</head>
<body>

<div class="login-container">
    <h2>Faça Login</h2>
    <div class="input-group">
        <label for="username">Usuário:</label>
        <input type="text" id="username" placeholder="Digite seu usuário">
    </div>
    <div class="input-group">
        <label for="password">Senha:</label>
        <input type="password" id="password" placeholder="Digite sua senha">
    </div>
    <div class="input-group">
        <button onclick="login()">Entrar</button>
    </div>
</div>

<script>
    function login() {
        // Adicione lógica de autenticação aqui
        alert("Autenticação bem-sucedida!"); // Exemplo: exibe um alerta
    }
</script>

</body>
</html>

