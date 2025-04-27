# Lucro-em-Pixels-Como-Construir-Sua-Fortuna-Online

<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lucro em Pixels - Conquiste sua Liberdade Financeira</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@600;800&family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary-color: #1a1a40;
      --secondary-color: #ff7e5f;
      --accent-color: #feb47b;
      --text-color: #ffffff;
      --font-title: 'Orbitron', sans-serif;
      --font-text: 'Poppins', sans-serif;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: var(--font-text);
      background: linear-gradient(-45deg, #1a1a40, #2c2c54, #1a1a40, #3d3d75);
      background-size: 400% 400%;
      animation: gradient 15s ease infinite;
      color: var(--text-color);
      line-height: 1.7;
    }

    @keyframes gradient {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    .container {
      width: 90%;
      max-width: 1200px;
      margin: auto;
      padding: 60px 0;
    }

    .header {
      text-align: center;
      padding: 100px 20px 50px;
    }

    .header h1 {
      font-family: var(--font-title);
      font-size: 4rem;
      color: var(--secondary-color);
      letter-spacing: 2px;
      text-shadow: 0px 0px 20px rgba(255, 126, 95, 0.8);
    }

    .header p {
      margin-top: 20px;
      font-size: 1.8rem;
      color: #ddd;
    }

    .btn-primary {
      display: inline-block;
      margin-top: 30px;
      padding: 15px 40px;
      background: linear-gradient(45deg, var(--secondary-color), var(--accent-color));
      color: #1a1a40;
      font-weight: bold;
      font-size: 1.2rem;
      text-decoration: none;
      border-radius: 50px;
      transition: all 0.4s ease;
      box-shadow: 0px 5px 20px rgba(255, 126, 95, 0.5);
    }

    .btn-primary:hover {
      transform: scale(1.1);
      box-shadow: 0px 8px 25px rgba(255, 126, 95, 0.8);
    }

    section {
      padding: 80px 0;
      text-align: center;
    }

    section h2 {
      font-family: var(--font-title);
      font-size: 3rem;
      color: var(--accent-color);
      margin-bottom: 20px;
      text-shadow: 0px 0px 10px rgba(255, 180, 123, 0.7);
    }

    section p {
      font-size: 1.3rem;
      color: #ccc;
      max-width: 800px;
      margin: auto;
    }

    .cards {
      margin-top: 50px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
    }

    .card {
      background: rgba(255, 255, 255, 0.05);
      border: 1px solid rgba(255, 255, 255, 0.1);
      padding: 30px 20px;
      border-radius: 20px;
      backdrop-filter: blur(10px);
      transition: 0.4s;
      min-height: 200px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-weight: bold;
      font-size: 1.2rem;
    }

    .card:hover {
      transform: translateY(-10px) scale(1.02);
      border-color: var(--accent-color);
    }

    .chapters ul {
      list-style: none;
      padding: 0;
      margin-top: 40px;
    }

    .chapters li {
      margin-bottom: 15px;
      font-size: 1.3rem;
    }

    .cta {
      background: linear-gradient(45deg, var(--secondary-color), var(--accent-color));
      color: #1a1a40;
      padding: 100px 20px;
      border-radius: 20px;
    }

    .cta h2 {
      color: #1a1a40;
      font-size: 2.5rem;
      margin-bottom: 20px;
    }

    .footer {
      text-align: center;
      padding: 30px;
      font-size: 0.9rem;
      background: #0d0d1d;
      color: #aaa;
    }

    /* Reveal animation */
    .reveal {
      opacity: 0;
      transform: translateY(60px);
      transition: all 0.8s ease;
    }

    .reveal.active {
      opacity: 1;
      transform: translateY(0);
    }
  </style>
</head>

<body>

  <!-- HEADER -->
  <header class="header reveal">
    <div class="container">
      <h1>Lucro em Pixels</h1>
      <p>Transforme suas ideias digitais em liberdade financeira</p>
      <a href="#comprar" class="btn-primary">Quero Começar Agora</a>
    </div>
  </header>

  <!-- INTRODUÇÃO -->
  <section class="intro reveal">
    <div class="container">
      <h2>O Caminho para a Liberdade</h2>
      <p>Descubra como transformar habilidades e dedicação em fontes reais de renda no universo digital. Um guia prático para quem busca construir um império online do zero!</p>
    </div>
  </section>

  <!-- BENEFÍCIOS -->
  <section class="benefits reveal">
    <div class="container">
      <h2>Você Vai Aprender</h2>
      <div class="cards">
        <div class="card">➔ Dominar o mercado digital</div>
        <div class="card">➔ Escolher seu modelo de renda online</div>
        <div class="card">➔ Criar uma presença digital forte</div>
        <div class="card">➔ Atrair público e converter em vendas</div>
        <div class="card">➔ Monetizar sua audiência de forma eficaz</div>
      </div>
    </div>
  </section>

  <!-- CAPÍTULOS -->
  <section class="chapters reveal">
    <div class="container">
      <h2>Capítulos do E-Book</h2>
      <ul>
        <li><strong>Capítulo 1:</strong> O poder do digital para sua renda</li>
        <li><strong>Capítulo 2:</strong> 5 modelos de ganhos online</li>
        <li><strong>Capítulo 3:</strong> Construindo sua base digital</li>
        <li><strong>Capítulo 4:</strong> Estratégias para atrair audiência</li>
        <li><strong>Capítulo 5:</strong> Convertendo audiência em lucro</li>
      </ul>
    </div>
  </section>

  <!-- CTA -->
  <section class="cta reveal" id="comprar">
    <div class="container">
      <h2>Está pronto para mudar sua vida?</h2>
      <a href="LINK_DO_CHECKOUT_KIWIFY" class="btn-primary">Garantir Meu Acesso</a>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="footer">
    <div class="container">
      <p>© 2025 Lucro em Pixels. Todos os direitos reservados.</p>
    </div>
  </footer>

  <script>
    window.addEventListener('scroll', reveal);

    function reveal() {
      const reveals = document.querySelectorAll('.reveal');
      for (let i = 0; i < reveals.length; i++) {
        const windowHeight = window.innerHeight;
        const elementTop = reveals[i].getBoundingClientRect().top;
        const elementVisible = 150;

        if (elementTop < windowHeight - elementVisible) {
          reveals[i].classList.add('active');
        }
      }
    }
  </script>

</body>
</html>
