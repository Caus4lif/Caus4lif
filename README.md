<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GoCity - Cadastro</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background-color: #000; /* Fundo preto */
            color: #FFD700; /* Texto amarelo */
        }
        .company-name {
            font-size: 2rem;
            font-weight: bold;
            margin-bottom: 20px;
        }
        .form-container {
            background-color: #333; /* Fundo do formulário em cinza escuro */
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(255, 215, 0, 0.3); /* Sombra amarela */
            width: 90%;
            max-width: 400px;
        }
        .form-group {
            margin-bottom: 15px;
        }
        .form-group label {
            display: block;
            margin-bottom: 5px;
            color: #FFD700; /* Rótulos em amarelo */
        }
        .form-group input {
            width: 100%;
            padding: 10px;
            border: 1px solid #FFD700; /* Borda amarela */
            border-radius: 5px;
            background-color: #555; /* Campo de entrada em cinza escuro */
            color: #fff; /* Texto dos campos em branco */
        }
        .button {
            background-color: #FFD700; /* Botão amarelo */
            color: #000; /* Texto do botão em preto */
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            width: 100%;
        }
        .button:hover {
            background-color: #FFC300; /* Amarelo mais claro ao passar o mouse */
        }
        .link {
            text-align: center;
            margin-top: 15px;
        }
        .link a {
            color: #FFD700; /* Link em amarelo */
            text-decoration: none;
        }
    </style>
</head>
<body>
    <div class="company-name">GoCity</div>
    <div class="form-container">
        <h2>Criar Conta</h2>
        <div class="form-group">
            <label for="username">Nome de Usuário</label>
            <input type="text" id="username" placeholder="Digite seu nome" required>
        </div>
        <div class="form-group">
            <label for="email">Email</label>
            <input type="email" id="email" placeholder="Digite seu email" required>
        </div>
        <div class="form-group">
            <label for="password">Senha</label>
            <input type="password" id="password" placeholder="Digite sua senha" required>
        </div>
        <button class="button">Criar Conta</button>
        <div class="link">
            <p>Esqueceu sua senha? <a href="reset-password.html">Clique aqui</a></p>
        </div>
    </div>
</body>
</html>
