<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>PES 2013 + Patch 2025</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f8f9fa;
      color: #333;
    }
    header {
      background-color: #111;
      color: white;
      padding: 20px;
      text-align: center;
    }
    .hero {
      padding: 40px 20px;
      text-align: center;
      background: #0066cc;
      color: white;
    }
    .hero h1 {
      margin-bottom: 10px;
    }
    .container {
      padding: 20px;
      max-width: 1000px;
      margin: auto;
    }
    .gallery img {
      max-width: 100%;
      border-radius: 10px;
      margin: 10px 0;
    }
    .buy-button {
      background: #28a745;
      color: white;
      padding: 15px 25px;
      text-decoration: none;
      font-size: 18px;
      border-radius: 8px;
      display: inline-block;
      margin-top: 20px;
    }
    footer {
      background: #111;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

<header>
  <h1>PES 2013 + Patch Atualizado 2025</h1>
</header>

<section class="hero">
  <h1>O Melhor PES 2013 de Todos os Tempos!</h1>
  <p>Atualizado com elencos, gráficos e uniformes de 2025. Rodando liso até em PC fraco!</p>
  <a href="#" class="buy-button">Comprar Agora</a>
</section>

<div class="container">
  <h2>O que está incluso:</h2>
  <ul>
    <li>⚽ Elencos atualizados 2025 (Brasileirão, Champions, Libertadores etc)</li>
    <li>🧤 Kits e uniformes reais 2025</li>
    <li>🎮 Compatível com teclado, controle USB e patch online</li>
    <li>🚀 Otimizado para rodar em PCs fracos</li>
    <li>📥 Link de download direto + tutorial fácil de instalação</li>
  </ul>

  <div class="gallery">
    <h2>Imagens do Jogo</h2>
    <img src="https://via.placeholder.com/800x400.png?text=PES+2025+Patch" alt="Imagem do jogo">
    <img src="https://via.placeholder.com/800x400.png?text=Times+Atualizados" alt="Times Atualizados">
  </div>

  <h2>Perguntas Frequentes</h2>
  <p><strong>❓ É fácil de instalar?</strong><br> Sim! Enviamos um tutorial completo em vídeo + PDF.</p>
  <p><strong>🎮 Funciona com controle?</strong><br> Sim, compatível com controles USB e até joystick genérico.</p>
  <p><strong>📦 Recebo o jogo completo?</strong><br> Sim! PES 2013 completo + Patch atualizado incluso.</p>

  <a href="#" class="buy-button">Quero Garantir o Meu!</a>
</div>

<footer>
  <p>© 2025 PES Patch Brasil | Suporte via WhatsApp e E-mail</p>
</footer>

</body>
</html> <!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Comprar PES 2013 + Patch 2025</title>
  <script src="https://cdn.jsdelivr.net/npm/emailjs-com@2.4.1/dist/email.min.js"></script>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f8f9fa;
      margin: 0;
      padding: 0;
    }
    .container {
      max-width: 400px;
      margin: 100px auto;
      padding: 20px;
      background: white;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    h2 {
      text-align: center;
    }
    input, button {
      width: 100%;
      padding: 12px;
      margin: 8px 0;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    button {
      background: #28a745;
      color: white;
      font-size: 16px;
      border: none;
    }
  </style>
</head>
<body>

<div class="container">
  <h2>Login para Comprar</h2>
  <input type="email" id="email" placeholder="Digite seu Gmail" required>
  <input type="text" id="nome" placeholder="Seu nome completo" required>
  <button onclick="enviarCompra()">Confirmar Compra</button>
</div>

<script>
  (function(){
    emailjs.init("YOUR_USER_ID"); // Substitua pelo seu ID do EmailJS
  })();

  function enviarCompra() {
    const email = document.getElementById("email").value;
    const nome = document.getElementById("nome").value;

    if (!email || !nome) {
      alert("Preencha todos os campos!");
      return;
    }

    const templateParams = {
      to_email: email,
      nome_cliente: nome,
      codigo_compra: Math.floor(Math.random() * 999999)
    };

    emailjs.send('default_service', 'template_bepes', templateParams)
      .then(function(response) {
        alert("Compra confirmada! Um e-mail foi enviado.");
        window.location.href = "https://wa.me/5548998023938?text=Olá,%20meu%20nome%20é%20" + encodeURIComponent(nome) + "%20e%20meu%20código%20de%20compra%20é%20" + templateParams.codigo_compra;
      }, function(error) {
        alert("Erro ao enviar e-mail. Tente novamente.");
      });
  }
</script>

</body>
</html>
