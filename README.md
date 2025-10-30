<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>CEJE Espaço Multidisciplinar</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #121212;
      color: #E0E0E0;
      margin: 0;
      padding: 0;
    }
    header {
      background: #0A84FF;
      padding: 1rem 2rem;
      display: flex;
      align-items: center;
      gap: 1rem;
      box-shadow: 0 2px 8px rgba(0,0,0,0.7);
    }
    header img {
      width: 120px;
      height: auto;
      border-radius: 8px;
    }
    header h1 {
      color: white;
      font-size: 1.8rem;
      margin: 0;
      letter-spacing: 2px;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 2rem;
      background: #1E1E1E;
      padding: 0.8rem 0;
    }
    nav a {
      text-decoration: none;
      color: #0A84FF;
      font-weight: 600;
      transition: color 0.3s ease;
    }
    nav a:hover {
      color: #40C4FF;
    }
    main {
      max-width: 900px;
      margin: 2rem auto;
      padding: 0 1rem;
    }
    section {
      margin-bottom: 2.5rem;
    }
    h2 {
      color: #0A84FF;
      border-bottom: 2px solid #0A84FF;
      padding-bottom: 0.5rem;
      margin-bottom: 1rem;
    }
    p {
      line-height: 1.6;
      font-size: 1.1rem;
    }
    form {
      background: #232323;
      padding: 1.5rem;
      border-radius: 8px;
      box-shadow: 0 0 10px #0A84FF;
      max-width: 500px;
      margin: 0 auto;
    }
    label {
      display: block;
      margin-bottom: 0.3rem;
      font-weight: 600;
      color: #B0B0B0;
    }
    input, textarea {
      width: 100%;
      padding: 0.5rem;
      margin-bottom: 1rem;
      border: none;
      border-radius: 4px;
      font-size: 1rem;
      background: #1A1A1A;
      color: #E0E0E0;
    }
    input:focus, textarea:focus {
      outline: 2px solid #0A84FF;
    }
    button {
      background: #0A84FF;
      border: none;
      color: white;
      padding: 0.7rem 1.5rem;
      font-size: 1.1rem;
      font-weight: 700;
      border-radius: 5px;
      cursor: pointer;
      transition: background-color 0.3s ease;
      width: 100%;
    }
    button:hover {
      background: #005FCC;
    }
    footer {
      text-align: center;
      padding: 1rem 0;
      background: #1E1E1E;
      color: #666;
      font-size: 0.9rem;
      margin-top: 3rem;
    }
    .instagram-embeds {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
      justify-content: center;
    }
    .instagram-embeds blockquote {
      width: 300px;
      max-width: 100%;
    }
    @media (max-width: 600px) {
      nav {
        flex-direction: column;
      }
      header {
        flex-direction: column;
        text-align: center;
      }
      .instagram-embeds {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>
  <header>
    <img src="https://instagram.fplu1-1.fna.fbcdn.net/v/t51.2885-15/ceje_logo.jpg" alt="Logotipo CEJE Espaço Multidisciplinar" />
    <h1>CEJE Espaço Multidisciplinar</h1>
  </header>
  <nav>
    <a href="#sobre">Sobre</a>
    <a href="#servicos">Serviços</a>
    <a href="#inscricao">Inscrição</a>
    <a href="#contato">Contato</a>
    <a href="#imagens">Imagens Instagram</a>
  </nav>
  <main>
    <section id="sobre">
      <h2>Sobre o CEJE</h2>
      <p>O CEJE Espaço Multidisciplinar é um centro dedicado ao desenvolvimento integral do público infantil e geral, com equipe multidisciplinar pronta para atender com excelência e cuidado.</p>
    </section>
    <section id="servicos">
      <h2>Serviços</h2>
      <ul>
        <li>Atendimento psicológico e terapêutico</li>
        <li>Atividades educativas e recreativas</li>
        <li>Fonoaudiologia e fisioterapia</li>
        <li>Projetos socioemocionais e apoio escolar</li>
      </ul>
    </section>
    <section id="inscricao">
      <h2>Inscrição</h2>
      <p>Para realizar sua inscrição, preencha o formulário abaixo com seus dados para entrarmos em contato e agendar uma visita.</p>
      <form>
        <label for="nome">Nome Completo</label>
        <input type="text" id="nome" name="nome" required />
        
        <label for="telefone">Telefone / WhatsApp</label>
        <input type="tel" id="telefone" name="telefone" required />
        
        <label for="email">E-mail</label>
        <input type="email" id="email" name="email" required />
        
        <label for="mensagem">Mensagem</label>
        <textarea id="mensagem" name="mensagem" rows="4"></textarea>
        
        <button type="submit">Enviar Inscrição</button>
      </form>
    </section>
    <section id="contato">
      <h2>Contato</h2>
      <p><strong>Telefone:</strong> (95) 99175-7983 / (95) 99115-3421</p>
      <p><strong>Endereço:</strong> Av. Ville Roy, 7806 - São Vicente</p>
      <p>Siga nosso Instagram: <a href="https://www.instagram.com/ceje.multidisciplinar/" target="_blank" style="color:#0A84FF;">@ceje.multidisciplinar</a></p>
    </section>
    <section id="imagens">
      <h2>Imagens mais curtidas do Instagram</h2>
      <div class="instagram-embeds">
        <blockquote class="instagram-media" data-instgrm-permalink="https://www.instagram.com/p/DP3xFBBjrTw/" data-instgrm-version="14" style="max-width:540px; width:100%; margin: auto;">
          <a href="https://www.instagram.com/p/DP3xFBBjrTw/" target="_blank">Ver postagem</a>
        </blockquote>
        <blockquote class="instagram-media" data-instgrm-permalink="https://www.instagram.com/p/DGdRhSRu5wI/" data-instgrm-version="14" style="max-width:540px; width:100%; margin: auto;">
          <a href="https://www.instagram.com/p/DGdRhSRu5wI/" target="_blank">Ver postagem</a>
        </blockquote>
      </div>
    </section>
  </main>
  <footer>
    © 2025 CEJE Espaço Multidisciplinar - Todos os direitos reservados.
  </footer>
  <script async src="//www.instagram.com/embed.js"></script>
</body>
</html>
