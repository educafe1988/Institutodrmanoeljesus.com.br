
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Instituto Teológico Dr. Manoel Jesus. Formação bíblica, cursos livres de Teologia e informações acadêmicas.">
  <title>Instituto Teológico Dr. Manoel Jesus</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, sans-serif;
      background: #f4f6fa;
      color: #18243a;
      line-height: 1.6;
    }

    header {
      background: #0b1730;
      color: white;
      text-align: center;
      padding: 35px 18px;
      border-bottom: 4px solid #d4af37;
    }

    .aguia {
      font-size: 65px;
      margin-bottom: 8px;
    }

    header h1 {
      color: #e4c45e;
      font-size: clamp(25px, 5vw, 38px);
    }

    header p {
      margin-top: 10px;
    }

    nav {
      background: #142647;
      padding: 14px 10px;
      text-align: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      display: inline-block;
      margin: 5px 9px;
      font-weight: bold;
    }

    .hero {
      padding: 55px 20px;
      text-align: center;
      background: linear-gradient(135deg, #142647, #263f65);
      color: white;
    }

    .hero h2 {
      font-size: clamp(26px, 5vw, 36px);
      color: #e4c45e;
      margin-bottom: 15px;
    }

    .hero p {
      max-width: 680px;
      margin: 0 auto 22px;
    }

    .botao {
      display: inline-block;
      background: #d4af37;
      color: #101b30;
      padding: 12px 22px;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
      margin: 5px;
    }

    section {
      padding: 40px 18px;
      max-width: 1100px;
      margin: auto;
    }

    section h2 {
      text-align: center;
      color: #142647;
      margin-bottom: 12px;
      font-size: 28px;
    }

    .introducao {
      text-align: center;
      margin: 0 auto 25px;
      max-width: 760px;
    }

    .cursos {
      display: grid;
      grid-template-columns: repeat(
        auto-fit, minmax(min(100%, 235px), 1fr)
      );
      gap: 18px;
      margin-top: 25px;
    }

    .card {
      background: white;
      padding: 23px;
      border-radius: 10px;
      border-top: 4px solid #d4af37;
      box-shadow: 0 4px 14px #15274412;
    }

    .card h3 {
      color: #142647;
      margin-bottom: 10px;
    }

    .card p {
      margin-bottom: 15px;
    }

    .sobre {
      background: white;
      border-radius: 10px;
      text-align: center;
      padding: 30px;
    }

    .aviso {
      background: #fff7df;
      border-left: 4px solid #d4af37;
      padding: 15px;
      border-radius: 5px;
      margin-top: 25px;
      font-size: 14px;
    }

    footer {
      background: #0b1730;
      color: white;
      text-align: center;
      padding: 25px 15px;
      margin-top: 25px;
    }

    footer p {
      margin: 5px 0;
    }
  </style>
</head>

<body>

  <header id="inicio">
    <div class="aguia" aria-label="Símbolo da águia">🦅</div>
    <h1>Instituto Teológico Dr. Manoel Jesus</h1>
    <p>Conhecimento bíblico, formação e compromisso com a Palavra.</p>
  </header>

  <nav aria-label="Menu principal">
    <a href="#inicio">Início</a>
    <a href="#graduacao">Graduação</a>
    <a href="#livres">Cursos Livres</a>
    <a href="#sobre">O Instituto</a>
    <a href="#contato">Contato</a>
  </nav>

  <main>
    <div class="hero">
      <h2>Prepare-se para crescer no conhecimento bíblico</h2>
      <p>
        Conheça nossas opções de formação teológica e
        encontre um caminho de aprendizado para sua jornada.
      </p>
      <a class="botao" href="#livres">Conheça os Cursos Livres</a>
      <a class="botao" href="#graduacao">Graduação</a>
    </div>

    <section id="graduacao">
      <h2>Cursos de Graduação</h2>
      <p class="introducao">
        Consulte as opções de formação superior e as informações
        sobre a instituição responsável pela oferta e pelo diploma.
      </p>

      <div class="cursos">
        <article class="card">
          <h3>Teologia</h3>
          <p>Estudo sistemático da Bíblia, doutrinas cristãs e história da Igreja.</p>
        </article>

        <article class="card">
          <h3>Pedagogia</h3>
          <p>Formação superior voltada à educação e aos processos de ensino.</p>
        </article>

        <article class="card">
          <h3>Administração</h3>
          <p>Estudos de gestão, planejamento, organizações e liderança.</p>
        </article>

        <article class="card">
          <h3>Gestão Pública</h3>
          <p>Conhecimentos de administração e gestão de serviços públicos.</p>
        </article>

        <article class="card">
          <h3>Recursos Humanos</h3>
          <p>Formação em gestão de pessoas, desenvolvimento e relações de trabalho.</p>
        </article>
      </div>

      <p class="aviso">
        As opções acima são informativas. A oferta efetiva, a modalidade,
        a duração e a emissão de diploma dependem da instituição de ensino
        responsável e de sua situação regulatória. Confirme esses dados
        antes de realizar a matrícula.
      </p>
    </section>

    <section id="livres">
      <h2>Cursos Livres de Teologia</h2>
      <p class="introducao">
        Cursos para aprofundar o conhecimento das Escrituras,
        desenvolver habilidades ministeriais e estudar temas bíblicos.
      </p>

      <div class="cursos">
        <article class="card">
          <h3>Teologia Básica</h3>
          <p>Fundamentos da fé cristã, doutrinas e introdução à Bíblia.</p>
        </article>

        <article class="card">
          <h3>Teologia Média</h3>
          <p>Aprofundamento doutrinário, interpretação e estudo bíblico.</p>
        </article>

        <article class="card">
          <h3>Hermenêutica Bíblica</h3>
          <p>Princípios e métodos de interpretação das Escrituras.</p>
        </article>

        <article class="card">
          <h3>Escatologia</h3>
          <p>Estudo bíblico das profecias e da esperança cristã.</p>
        </article>

        <article class="card">
          <h3>Cristologia</h3>
          <p>Estudo da pessoa, natureza, obra e ensinamentos de Jesus Cristo.</p>
        </article>

        <article class="card">
          <h3>Bibliologia</h3>
          <p>Estudo da Bíblia, sua formação, estrutura e características.</p>
        </article>

        <article class="card">
          <h3>Evangelismo</h3>
          <p>Princípios bíblicos e práticas de comunicação do Evangelho.</p>
        </article>

        <article class="card">
          <h3>Capelania</h3>
          <p>Introdução ao serviço de assistência espiritual e acolhimento.</p>
        </article>
      </div>

      <p class="aviso">
        Os cursos livres têm finalidade formativa e não equivalem,
        por si só, a uma graduação superior nem garantem habilitação
        profissional regulamentada.
      </p>
    </section>

    <section id="sobre">
      <div class="sobre">
        <h2>Sobre o Instituto</h2>
        <p>
          O Instituto Teológico Dr. Manoel Jesus dedica-se à divulgação
          do conhecimento bíblico e à formação teológica, incentivando
          o estudo das Escrituras e o desenvolvimento ministerial.
        </p>
      </div>
    </section>

    <section id="contato">
      <h2>Informações e Matrículas</h2>
      <p class="introducao">
        Entre em contato para consultar disponibilidade de turmas,
        conteúdo programático, valores e condições de matrícula.
      </p>
      <p class="introducao">
        Adicione aqui o telefone, o WhatsApp e o e-mail oficiais do instituto.
      </p>
    </section>
  </main>

  <footer>
    <p><strong>Instituto Teológico Dr. Manoel Jesus</strong></p>
    <p>Conhecimento bíblico e formação teológica.</p>
    <p>© <span id="ano"></span> - Todos os direitos reservados.</p>
  </footer>

  <script>
    document.getElementById("ano").textContent =
      new Date().getFullYear();
  </script>

</body>
</html>
