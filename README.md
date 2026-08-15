<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Vinicius Melão | Portfólio</title>
  <!-- Ícones Font Awesome e Devicon -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/devicon.min.css">
  
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    }

    body {
      background-color: #0d1117;
      color: #c9d1d9;
      display: flex;
      justify-content: center;
      padding: 40px 20px;
      line-height: 1.6;
    }

    .container {
      max-width: 800px;
      width: 100%;
    }

    /* Cabeçalho */
    .header {
      font-size: 1.8rem;
      font-weight: 700;
      color: #f0f6fc;
      display: flex;
      align-items: center;
      gap: 10px;
      margin-bottom: 16px;
    }

    hr {
      border: 0;
      height: 1px;
      background-color: #30363d;
      margin: 20px 0;
    }

    /* Tag de Cargo */
    .badge {
      display: inline-block;
      background-color: #161b22;
      border: 1px solid #30363d;
      color: #f0f6fc;
      padding: 4px 10px;
      border-radius: 6px;
      font-size: 0.85rem;
      font-family: monospace;
      margin-bottom: 16px;
    }

    /* Sobre */
    .about-text {
      font-size: 0.95rem;
      color: #c9d1d9;
      text-align: justify;
      margin-bottom: 20px;
    }

    /* Redes Sociais */
    .social-links {
      display: flex;
      gap: 16px;
      font-size: 1.8rem;
      margin-bottom: 10px;
    }

    .social-links a {
      color: #8b949e;
      text-decoration: none;
      transition: color 0.2s ease;
    }

    .social-links a:hover {
      color: #58a6ff;
    }

    .social-links .fa-linkedin {
      color: #0a66c2;
    }

    /* Títulos de Seções */
    .section-title {
      font-size: 1.25rem;
      font-weight: 600;
      color: #f0f6fc;
      display: flex;
      align-items: center;
      gap: 8px;
      margin-bottom: 16px;
    }

    /* Tecnologias */
    .tech-stack {
      display: flex;
      align-items: center;
      gap: 20px;
      font-size: 2rem;
      flex-wrap: wrap;
      margin-bottom: 28px;
    }

    /* Projetos */
    .projects-content {
      font-size: 0.95rem;
      color: #8b949e;
    }
  </style>
</head>
<body>

  <main class="container">
    <!-- Cabeçalho Principal -->
    <h1 class="header">👨‍💻 Vinicius Melão</h1>
    
    <hr>

    <!-- Tag de Função -->
    <span class="badge">Data Scientist</span>

    <!-- Bio / Descrição -->
    <p class="about-text">
      Me chamo Vinicius Melão, natural de São Paulo. Formado em Ciência da Computação. Atualmente, estou cursando o MBA em Data Science, Inteligência Artificial e Analytics na USP ESALQ. Atuo no mercado financeiro, com experiência em produtos digitais, APIs e análise de dados, conectando tecnologia e negócio para transformar dados em insights e oportunidades de melhoria. Atuo na gestão técnica de APIs de financiamento de veículos, trabalhando com mais de 20 parceiros em produção e produtos que impactam milhares de clientes por mês. Atualmente, direciono minha carreira para Ciência de Dados, buscando aplicar tecnologia, estatística e inteligência artificial na resolução de problemas de negócio, especialmente no setor financeiro.
    </p>

    <!-- Links / Redes Sociais -->
    <nav class="social-links" aria-label="Redes Sociais">
      <a href="https://linkedin.com/in/SEU_LINKEDIN" target="_blank" title="LinkedIn"><i class="fa-brands fa-linkedin"></i></a>
      <a href="https://github.com/SEU_GITHUB" target="_blank" title="GitHub"><i class="fa-brands fa-github"></i></a>
      <a href="mailto:seu-email@exemplo.com" title="E-mail"><i class="fa-solid fa-envelope"></i></a>
    </nav>

    <hr>

    <!-- Seção de Tecnologias -->
    <section>
      <h2 class="section-title">🤖 Linguagens e Tecnologias</h2>
      <div class="tech-stack">
        <i class="devicon-python-plain colored" title="Python"></i>
        <i class="devicon-azuresqldatabase-plain colored" title="SQL"></i>
        <i class="devicon-pandas-plain colored" title="Pandas"></i>
        <i class="devicon-numpy-plain colored" title="NumPy"></i>
        <i class="devicon-apachespark-original colored" title="Apache Spark"></i>
      </div>
    </section>

    <!-- Seção de Projetos -->
    <section>
      <h2 class="section-title">🚀 Projetos</h2>
      <div class="projects-content">
        <p>aaaaaaaaaaaaaaaaaaaaaaaa</p>
      </div>
    </section>
  </main>

</body>
</html>
