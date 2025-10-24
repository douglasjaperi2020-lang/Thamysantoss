<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Confirmação de idade</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #000;
      color: #fff;
      text-align: center;
      padding-top: 100px;
    }
    h1 {
      font-size: 28px;
      margin-bottom: 20px;
    }
    p {
      font-size: 18px;
      margin-bottom: 40px;
    }
    button {
      background-color: #e60000;
      color: white;
      border: none;
      padding: 15px 25px;
      font-size: 18px;
      cursor: pointer;
      margin: 10px;
      border-radius: 5px;
    }
    button:hover {
      background-color: #b30000;
    }
  </style>
</head>
<body>
  <h1>⚠️ Conteúdo +18</h1>
  <p>Este conteúdo é destinado apenas para maiores de 18 anos.<br>Deseja continuar?</p>
  <button onclick="prosseguir()">Sim, tenho mais de 18</button>
  <button onclick="sair()">Não</button>

  <script>
    function prosseguir() {
      window.location.href = "https://t.me/Thamysantos_bot";
    }
    function sair() {
      window.location.href = "https://google.com";
    }
  </script>
</body>
</html>
