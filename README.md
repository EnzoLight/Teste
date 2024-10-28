<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cadastro de Conta</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
        }
        form {
            background: white;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            max-width: 400px;
            margin: auto;
        }
        input, select, button {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            background-color: #5cb85c;
            color: white;
            border: none;
            cursor: pointer;
        }
        button:hover {
            background-color: #4cae4c;
        }
    </style>
</head>
<body>

    <h2>Cadastro de Conta</h2>
    <form action="#" method="POST">
        <label for="usuario">Usuário:</label>
        <input type="text" id="usuario" name="usuario" required>

        <label for="email">E-mail:</label>
        <input type="email" id="email" name="email" required>

        <label for="senha">Senha:</label>
        <input type="password" id="senha" name="senha" required>

        <label for="repetirSenha">Repetir Senha:</label>
        <input type="password" id="repetirSenha" name="repetirSenha" required>

        <label for="tipoConta">Tipo de Conta:</label>
        <select id="tipoConta" name="tipoConta" required>
            <option value="administrador">Administrador</option>
            <option value="usuario">Usuário</option>
        </select>

        <button type="submit">Cadastrar Conta</button>
        <button type="button" onclick="window.location.href='login.html'">Logar</button>
    </form>

</body>
</html>

