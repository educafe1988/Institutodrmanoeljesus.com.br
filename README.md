
<!DOCTYPE 
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Instituto Teológico Dr. Manoel Jesus</title>

  <meta name="description" content="Instituto Teológico Dr. Manoel Jesus. Formação teológica, cursos livres e informações sobre cursos de graduação.">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, Helvetica, sans-serif;
      line-height: 1.6;
      color: #243044;
      background: #f5f7fa;
    }

    header {
      background: #071b38;
      color: white;
      padding: 18px 5%;
      border-bottom: 4px solid #d9ad53;
    }

    .topo {
      max-width: 1150px;
      margin: auto;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 20px;
      flex-wrap: wrap;
    }

    .marca {
      display: flex;
      align-items: center;
      gap: 12px;
    }

    .aguia {
      font-size: 43px;
    }

    .marca h1 {
      color: #f0cb77;
      font-size: 21px;
      line-height: 1.3;
    }

    .marca p {
      font-size: 12px;
      color: #ffffff;
    }

    nav {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-size: 14px;
      font-weight: bold;
    }

    nav a:hover {
      color: #f0cb77;
    }

    .banner {
      background: linear-gradient(135deg, #0a2850, #123f67);
      color: white;
      text-align: center;
      padding: 75px 20px;
    }

    .banner h2 {
      font-size: clamp(28px, 5vw, 44px);
      color: #f0cb77;
      margin-bottom: 18px;
    }

    .banner p {
      max-width: 720px;
      margin: 0 auto 25px;
      font-size: 17px;
    }

    .botao {
      display: inline-block;
      background: #e7bd64;
      color: #071b38;
      padding: 12px 23px;
      margin: 6px;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
    }

    .botao:hover {
      background: #ffda8b;
    }

    .botao-contorno {
      border: 1px solid #e7bd64;
      color: white;
      padding: 11px 22px;
      border-radius: 6px;
      display: inline-block;
      margin: 6px;
      text-decoration: none;
    }

    section {
      padding: 55px 6%;
      scroll-margin-top: 15px;
    }

    .container {
      max-width: 1100px;
      margin: auto;
    }

    .titulo {
      color: #0a2850;
      text-align: center;
      font-size: 29px;
      margin-bottom: 12px;
    }

    .subtitulo {
      text-align: center;
      max-width: 720px;
      margin: 0 auto 30px;
      color: #596579;
    }

    .sobre {
      background: white;
    }

    .sobre-conteudo {
      display: grid;
      grid-template-columns: 1fr 1.5fr;
      align-items: center;
      gap: 35px;
    }

    .foto-diretor {
      width: 100%;
      max-width: 340px;
      display: block;
      margin: auto;
      border-radius: 12px;
      border: 4px solid #e7bd64;
      object-fit: cover;
    }

    .foto-placeholder {
      background: #e9eef5;
      color: #0a2850;
      padding: 55px 15px;
      text-align: center;
      border-radius: 12px;
      border: 2px dashed #b7c3d3;
    }

    .sobre h3 {
      color: #0a2850;
      margin-bottom: 12px;
      font-size: 24px;
    }

    .sobre p {
      margin-bottom: 12px;
    }

    .cursos {
      background: #f0f3f8;
    }

    .grade {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 20px;
    }

    .cartao {
      background: white;
      border-radius: 10px;
      padding: 25px 20px;
      border-top: 4px solid #d9ad53;
      box-shadow: 0 4px 15px rgba(7, 27, 56, 0.07);
    }

    .cartao .icone {
      font-size: 32px;
    }

    .cartao h3 {
      color: #0a2850;
      margin: 10px 0;
      font-size: 19px;
    }

    .cartao p {
      font-size: 14px;
      color: #596579;
    }

    .destaque {
      background: #0a2850;
      color: white;
      text-align: center;
    }

    .destaque h2 {
      color: #f0cb77;
      margin-bottom: 15px;
    }

    .destaque p {
      max-width: 760px;
      margin: auto;
    }

    .valores {
      background: white;
    }

    .rodape {
      background: #071b38;
      color: white;
      padding: 45px 6% 20px;
      border-top: 4px solid #d9ad53;
    }

    .rodape h2 {
      color: #f0cb77;
      margin-bottom: 10px;
    }

    .rodape h3 {
      color: #f0cb77;
      margin-bottom: 12px;
    }

    .contatos {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 25px;
      max-width: 1000px;
      margin: 25px auto;
    }

    .contatos a {
      color: white;
      overflow-wrap: anywhere;
    }

    .contatos p {
      margin-bottom: 9px;
    }

    .copyright {
      border-top: 1px solid #526178;
      padding-top: 18px;
      text-align: center;
      font-size: 13px;
      margin-top: 25px;
    }

    @media (max-width: 760px) {
      .topo {
        justify-content: center;
        text-align: center;
      }

      .marca {
        justify-content: center;
      }

      nav {
        justify-content: center;
      }

      .sobre-conteudo {
        grid-template-columns: 1fr;
      }

      .grade {
        grid-template-columns: 1fr;
      }

      .contatos {
        grid-template-columns: 1fr;
      }

      section {
        padding: 40px 6%;
      }

      .banner {
        padding: 55px 18px;
      }
    }
  </style>
</head>

<body>

  <header>
    <div class="topo">
      <div class="marca">
        <span class="aguia" aria-hidden="true">🦅</span>
        <div>
          <h1>Instituto Teológico<br>Dr. Manoel Jesus</h1>
          <p>Conhecimento, fé e formação</p>
        </div>
      </div>

      <nav aria-label="Menu principal">
        <a href="#inicio">Início</a>
        <a href="#sobre">O Instituto</a>
        <a href="#cursos">Cursos</a>
        <a href="#valores">Nossa missão</a>
        <a href="#contato">Contato</a>
      </nav>
    </div>
  </header>

  <main>
    <section class="banner" id="inicio">
      <div class="container">
        <h2>Formando vidas através do conhecimento</h2>

        <p>
          Bem-vindo ao Instituto Teológico Dr. Manoel Jesus.
          Um espaço dedicado ao estudo da Bíblia, à formação
          teológica e ao desenvolvimento do conhecimento.
        </p>

        <a class="botao" href="#cursos">Conheça nossos cursos</a>
        <a class="botao-contorno" href="#contato">Fale conosco</a>
      </div>
    </section>

    <section class="sobre" id="sobre">
      <div class="container">
        <h2 class="titulo">Sobre o Instituto</h2>

        <p class="subtitulo">
          Educação, compromisso e dedicação à formação de pessoas.
        </p>

        <div class="sobre-conteudo">
          <div>
            <!-- Para exibir sua foto, envie o arquivo ao GitHub
                 com o nome foto-diretor.jpg, na mesma pasta
                 deste index.html. Depois, substitua este bloco
                 pela imagem abaixo. -->

            <div class="foto-placeholder">
              <span style="font-size:45px;">👤</span>
              <p>Foto do diretor</p>
              <p>Dr. Manoel Jesus</p>
            </div>
          </div>

          <div>
            <h3>Diretor: Dr. Manoel Jesus</h3>

            <p>
              O Instituto Teológico Dr. Manoel Jesus tem como
              propósito promover o conhecimento bíblico, a
              formação teológica e o desenvolvimento educacional.
            </p>

            <p>
              Nossa proposta é incentivar o estudo responsável,
              a reflexão, os valores cristãos e a preparação
              de pessoas para servir à comunidade.
            </p>

            <a class="botao" href="#cursos">Ver cursos</a>
          </div>
        </div>
      </div>
    </section>

    <section class="cursos" id="cursos">
      <div class="container">
        <h2 class="titulo">Nossos cursos</h2>

        <p class="subtitulo">
          Conheça as áreas de formação e consulte as opções
          disponíveis, os requisitos e as modalidades de cada curso.
        </p>

        <div class="grade">
          <article class="cartao">
            <div class="icone">📖</div>
            <h3>Teologia Básica</h3>
            <p>
              Introdução ao estudo da Bíblia, fundamentos da fé
              cristã e conhecimentos teológicos essenciais.
            </p>
          </article>

          <article class="cartao">
            <div class="icone">🎓</div>
            <h3>Graduação em Teologia</h3>
            <p>
              Consulte informações sobre oferta, instituição
              responsável, modalidade e reconhecimento do curso.
            </p>
          </article>

          <article class="cartao">
            <div class="icone">📚</div>
            <h3>Cursos Livres de Teologia</h3>
            <p>
              Estudos temáticos para aprofundamento bíblico
              e crescimento no conhecimento teológico.
            </p>
          </article>

          <article class="cartao">
            <div class="icone">🏫</div>
            <h3>Pedagogia</h3>
            <p>
              Informações sobre oportunidades de formação
              na área da educação.
            </p>
          </article>

          <article class="cartao">
            <div class="icone">💼</div>
            <h3>Administração</h3>
            <p>
              Conhecimentos relacionados à gestão,
              organização e administração.
            </p>
          </article>

          <article class="cartao">
            <div class="icone">📊</div>
            <h3>Gestão e Recursos Humanos</h3>
            <p>
              Consulte as opções de formação em gestão pública,
              recursos humanos e áreas relacionadas.
            </p>
          </article>
        </div>

        <p style="text-align:center; margin-top:28px;">
          <a class="botao"
             href="https://wa.me/5511958414506"
             target="_blank"
             rel="noopener noreferrer">
            Consultar cursos pelo WhatsApp
          </a>
        </p>
      </div>
    </section>

    <section class="destaque" id="valores">
      <div class="container">
        <h2>Nossa missão</h2>

        <p>
          Promover o ensino, incentivar o conhecimento bíblico
          e contribuir para a formação intelectual, teológica
          e humana, com responsabilidade e compromisso.
        </p>
      </div>
    </section>

    <section class="valores">
      <div class="container">
        <h2 class="titulo">Nossos princípios</h2>

        <div class="grade">
          <article class="cartao">
            <h3>Conhecimento</h3>
            <p>Incentivo ao estudo e à aprendizagem contínua.</p>
          </article>

          <article class="cartao">
            <h3>Compromisso</h3>
            <p>Responsabilidade com a formação e o ensino.</p>
          </article>

          <article class="cartao">
            <h3>Serviço</h3>
            <p>Valorização da vida, da comunidade e do próximo.</p>
          </article>
        </div>
      </div>
    </section>
  </main>

  <footer class="rodape" id="contato">
    <div class="container">
      <div style="text-align:center;">
        <span style="font-size:42px;" aria-hidden="true">🦅</span>
        <h2>Instituto Teológico Dr. Manoel Jesus</h2>
        <p>Conhecimento, fé e formação.</p>
      </div>

      <div class="contatos">
        <div>
          <h3>Fale conosco</h3>

          <p>
            📱 WhatsApp:
            <a href="https://wa.me/5511958414506"
               target="_blank"
               rel="noopener noreferrer">
              (11) 95841-4506
            </a>
          </p>

          <p>
            ✉️ E-mail:
            <a href="mailto:teologomanoeljesus@gmail.com">
              teologomanoeljesus@gmail.com
            </a>
          </p>

          <p>
            📍 Endereço: Rua José Cabanilles, 95, térreo,
            São Paulo – SP, CEP 03977-004.
          </p>
        </div>

        <div>
          <h3>Redes sociais</h3>

          <p>
            ▶️ YouTube:
            <a href="https://www.youtube.com/results?search_query=teologomanoeljesus"
               target="_blank"
               rel="noopener noreferrer">
              Teólogo Manoel Jesus
            </a>
          </p>

          <p>
            📸 Instagram:
            <a href="https://www.instagram.com/manoel0204/"
               target="_blank"
               rel="noopener noreferrer">
              @manoel0204
            </a>
          </p>

          <p>
            <a href="#inicio">Voltar ao início ↑</a>
          </p>
        </div>
      </div>

      <div class="copyright">
        <p>
          © <span id="ano">2026</span>
          Instituto Teológico Dr. Manoel Jesus.
          Todos os direitos reservados.
        </p>
      </div>
    </div>
  </footer>

  <script>
    document.getElementById("ano").textContent =
      new Date().getFullYear();
  </script>

</body>
</html>

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
