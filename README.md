<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Central Invictus Store</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #f2f2f2;
      color: #333;
    }

    header {
      position: fixed;
      top: 0;
      width: 100%;
      background: #1a1a2e;
      color: white;
      z-index: 1000;
      padding: 1rem 2rem;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 1rem;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: 500;
    }

    main {
      padding-top: 80px;
    }

    section {
      padding: 80px 20px;
      max-width: 1000px;
      margin: 0 auto;
    }

    section:nth-child(even) {
      background-color: #e9e9e9;
    }

    h2 {
      margin-bottom: 1rem;
      color: #1a1a2e;
    }

    p {
      font-size: 1.1rem;
    }

    .btn {
      display: inline-block;
      margin-top: 1rem;
      background: #1a1a2e;
      color: white;
      padding: 10px 20px;
      border-radius: 8px;
      text-decoration: none;
      transition: 0.3s;
    }

    .btn:hover {
      background: #27277a;
    }

    footer {
      background: #1a1a2e;
      color: white;
      text-align: center;
      padding: 1.5rem 0;
      margin-top: 2rem;
    }

    @media (max-width: 768px) {
      nav ul {
        flex-direction: column;
        gap: 0.5rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <nav>
      <div><strong>CentralTech</strong></div>
      <ul>
        <li><a href="#servicos">Serviços</a></li>
        <li><a href="#orcamento">Orçamento</a></li>
        <li><a href="#aparelhos">Aparelhos</a></li>
        <li><a href="#perifericos">Periféricos</a></li>
        <li><a href="#garantias">Garantias</a></li>
        <li><a href="#promocao">Promoção</a></li>
        <li><a href="#terceirizacao">Terceirização</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="servicos">
      <h2>🛠️ Catálogo de Serviços Técnicos</h2>
      <p>Reparos em celulares, tablets, troca de telas, limpeza interna.</p>
      <a href="#orcamento" class="btn">Ver todos os serviços</a>
    </section>

    <section id="orcamento">
      <h2>📋 Solicite um Orçamento</h2>
      <p>Informe o problema do seu dispositivo e receba um orçamento personalizado rapidamente.</p>
      <a href="https://wa.me/5571993437063" class="btn">Solicitar via WhatsApp</a>
    </section>

    <section id="aparelhos">
      <h2>📱 Venda de Aparelhos</h2>
      <p>Aparelhos revisados e com garantia. Smartphones prontos para uso.</p>
      <a href="#" class="btn">Ver aparelhos disponíveis</a>
    </section>

    <section id="perifericos">
      <h2>🎧 Venda de Periféricos</h2>
      <p>Mouses, teclados, fones, cabos, fontes e acessórios com preço justo e garantia.</p>
      <a href="#" class="btn">Explorar periféricos</a>
    </section>

    <section id="garantias">
      <h2>📄 Reclamações e Garantias</h2>
      <p>Teve um problema com um produto ou serviço? Faça contato direto para resolvermos.</p>
      <a href="https://wa.me/5571993437063" class="btn">Abrir solicitação</a>
    </section>

    <section id="promocao">
      <h2>🔥 Promoção da Semana</h2>
      <p>Ofertas imperdíveis em consertos, acessórios e equipamentos com até 40% de desconto.</p>
      <a href="#" class="btn">Ver promoções</a>
    </section>

    <section id="terceirizacao">
      <h2>🤝 Terceirização de Serviços</h2>
      <p>Você é técnico ou loja? Terceirize seus reparos conosco com agilidade e qualidade garantida.</p>
      <a href="#" class="btn">Clique aqui para mais detalhes</a>
    </section>
  </main>
  <footer>
    <p>© 2025 Central Invictus Store Assistência Técnica - Todos os direitos reservados.</p>
  </footer>
</body>
</html>
