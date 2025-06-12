#HTML

<!DOCTYPE html> <!-- Define o tipo de documento como HTML5 -->
<html lang="pt-br"> <!-- Início do documento HTML com idioma português do Brasil -->

<head> <!-- Início do cabeçalho do documento -->
    <meta charset="UTF-8"> <!-- Define a codificação de caracteres como UTF-8 -->
    <meta name="viewport" content="width=device-width, initial-scale=1"> <!-- Torna o layout responsivo em dispositivos móveis -->
    <link rel="preconnect" href="https://fonts.googleapis.com"&gt; <!-- Otimiza a conexão antecipada com o Google Fonts -->
    <title>Tropicália</title> <!-- Define o título da aba do navegador como "Tropicália" -->
    <link href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.3/css/bootstrap.min.css&quot; rel="stylesheet"> <!-- Importa o CSS do Bootstrap via CDN -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap-icons/1.11.3/font/bootstrap-icons.min.css"&gt; <!-- Importa ícones do Bootstrap Icons -->
    <link rel="stylesheet" href="styles.css"> <!-- Importa o arquivo CSS personalizado -->
</head>

<body> <!-- Início do corpo do site, conteúdo visível na página -->

    <header class="p-5"> <!-- Cabeçalho com preenchimento interno (padding) -->
        <nav class="container d-flex justify-content-between align-items-center"> <!-- Navegação com layout flexível e espaçamento entre itens -->
            <img src="img/logo.png" class="nav-img" loading="lazy"> <!-- Logo com carregamento preguiçoso (lazy load) -->
            <ul class="nav mt-5"> <!-- Lista de navegação com margem superior -->
                <li class="nav-item"><a class="nav-link" href="#inicio">Início</a></li> <!-- Link para a seção "Início" -->
                <li class="nav-item"><a class="nav-link" href="#galeria">Galeria</a></li> <!-- Link para a seção "Galeria" -->
                <li class="nav-item"><a class="nav-link" href="#contato">Contato</a></li> <!-- Link para a seção "Contato" -->
            </ul>
            <div id="acessibilidade" class="menu-acessibilidade"> <!-- Div para o menu de acessibilidade -->
                <button id="botao-acessibilidade" class="btn btn-primary fw-bold rotacao-botao" aria-expanded="false">acessibilidade</button> <!-- Botão que abre as opções de acessibilidade -->
                <div id="opcoes-acessibilidade" class="opcoes-acessibilidade apresenta-lista"> <!-- Menu de opções de acessibilidade (inicialmente oculto) -->
                    <button id="aumentar-fonte" class="btn btn-primary fw-bold" aria-label="Aumentar o tamanho da fonte">A+</button> <!-- Botão para aumentar fonte -->
                    <button id="diminuir-fonte" class="btn btn-primary fw-bold" aria-label="diminuir o tamanho da fonte">A-</button> <!-- Botão para diminuir fonte -->
                    <button id="alterna-contraste" class="btn btn-primary fw-bold" aria-label="Alterna o contraste de cores"> <!-- Botão para alternar o contraste -->
                        <i class="bi bi-shadows"></i> <!-- Ícone de contraste -->
                    </button>
                </div>
            </div>
        </nav>
    </header>

    <main class="container my-5"> <!-- Área principal com margens verticais -->

        <section id="inicio" class="my-5"> <!-- Seção inicial com margem vertical -->
            <div class="inicio-fundo d-flex justify-content-between align-items-center"> <!-- Div com fundo e layout flexível -->
                <div class="esquerda-conteudo"> <!-- Área com conteúdo textual e botão -->
                    <h1 class="display-4 text-white fst-italic fw-bold">Boas-vindas a</h1> <!-- Título principal estilizado -->
                    <img src="img/logo-2.png" class="mb-3" width="563" height="278" loading="lazy"> <!-- Imagem logo abaixo do título -->
                    <a href="#tropicalia" class="btn btn-primary btn-lg botao-inicio fw-semibold">Quero conhecer!</a> <!-- Botão com link para a seção Tropicália -->
                </div>
                <img src="img/lossy-page1-640px-Os_Mutantes.tif (1).png" alt="A imagem apresenta o grupo musical Os mutantes, sao tres pessoas cantando em um microfone" title="Os mutantes - CC0 Domínio Público / Acervo Arquivo Nacional" class="img-fluid img-inicio"> <!-- Imagem com descrição e estilo responsivo -->
            </div>
        </section>

        <section id="tropicalia" class="my-5 pt-6 secao-tropicalia" tabindex="0" aria-label="Seção explicativa sobre a tropicália"> <!-- Seção explicativa com acessibilidade -->
            <div class="container d-flex align-items-center"> <!-- Container com layout flexível -->
                <div class="col-4 d-flex justify-content-center"> <!-- Coluna com imagem centralizada -->
                    <img src="img/image (1).png" class="rounded-pill" width="273" height="331" loading="lazy"> <!-- Imagem com cantos arredondados (formato pílula) -->
                </div>
                <div class="col-5"> <!-- Coluna com o texto -->
                    <h2>O que foi a Tropicália?</h2> <!-- Título da seção -->
                    <p class="p-2">A Tropicália, também conhecida como Tropicalismo, foi um movimento cultural brasileiro que surgiu na década de 1960 [...]</p> <!-- Texto explicativo com padding -->
                </div>
            </div>
        </section>

        <section id="galeria" tabindex="0" aria-label="Seção de galeria de imagens"> <!-- Seção de galeria com acessibilidade -->
            <h2 class="text-center pt-5">Galeria</h2> <!-- Título centralizado -->
            <div class="container p-3 mt-3 fundo-galeria"> <!-- Container com padding, margem e fundo estilizado -->
                <div class="row justify-content-md-center"> <!-- Linha de imagens centralizada -->
                    <div class="col-md-4">
                        <img src="img/lossy-page1-640px-Jorge_Ben_e_o_Trio_Mocotó_no_Teatro_da_Lagoa,_1971.tif.jpg" class="img-fluid rounded-5" loading="lazy"> <!-- Imagem da galeria -->
                    </div>
                    <div class="col-md-4">
                        <img src="img/lossy-page1-640px-Os_Mutantes_2.tif.jpg" class="img-fluid rounded-5" loading="lazy"> <!-- Segunda imagem -->
                    </div>
                </div>
                <div class="row mt-4 justify-content-md-center"> <!-- Segunda linha de imagens -->
                    <div class="col-md-4">
                        <img src="img/lossy-page1-640px-Gilberto_Gil_nos_anos_1960.tif.jpg" class="img-fluid rounded-5" loading="lazy"> <!-- Terceira imagem -->
                    </div>
                    <div class="col-md-4">
                        <img src="img/lossy-page1-640px-Caetano_Veloso_no_III_Festival_da_Música_Popular.tif.jpg" class="img-fluid rounded-5" loading="lazy"> <!-- Quarta imagem -->
                    </div>
                </div>
            </div>
        </section>

        <section id="contato"> <!-- Seção de formulário de contato -->
            <div class="container p-5 d-flex justify-content-center"> <!-- Container com padding e conteúdo centralizado -->
                <div class="col-md-8 col-lg-10 rounded-5 formulario"> <!-- Formulário com bordas arredondadas -->
                    <h2 class="mb-3">Entre em contato</h2> <!-- Título do formulário -->
                    <form> <!-- Início do formulário -->
                        <div class="form-group mb-3"> <!-- Grupo de campo -->
                            <label for="nome">Nome</label> <!-- Rótulo do campo nome -->
                            <input type="text" id="nome" name="nome" class="form-control rounded-3 mt-1" placeholder="Digite seu nome completo"> <!-- Campo de entrada para o nome -->
                        </div>
                        <div class="form-group mb-3"> <!-- Grupo de campo -->
                            <label for="email">Email</label> <!-- Rótulo do campo email -->
                            <input type="email" id="email" name="email" class="form-control rounded-3 mt-1" placeholder="Digite seu email"> <!-- Campo de entrada para o email -->
                        </div>
                        <div class="form-group mb-3"> <!-- Grupo de campo -->
                            <label for="mensagem">Mensagem</label> <!-- Rótulo do campo mensagem -->
                            <textarea id="mensagem" name="mensagem" class="form-control rounded-4 mt-2" rows="4" placeholder="Escreva sua mensagem"></textarea> <!-- Campo de texto -->
                        </div>
                        <div class="d-grid gap-2"> <!-- Div com grid de espaçamento -->
                            <button type="submit" class="btn btn-primary btn-lg rounded-pill">Enviar mensagem</button> <!-- Botão de envio -->
                        </div>
                    </form> <!-- Fim do formulário -->
                </div>
            </div>
        </section>

    </main> <!-- Fim da área principal -->

    <footer class="text-center p-3 fst-italic"> <!-- Rodapé com texto centralizado e em itálico -->
        <p>Acesse nossas redes:</p> <!-- Texto do rodapé -->
        <i class="bi bi-whatsapp"></i> <!-- Ícone do WhatsApp -->
        <i class="bi bi-instagram"></i> <!-- Ícone do Instagram -->
        <i class="bi bi-tiktok"></i> <!-- Ícone do TikTok -->
        <p class="mt-3">Desenvolvido por Start by Alura. Projeto fictício sem fins comerciais.</p> <!-- Texto final de créditos -->
    </footer>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/scrollReveal.js/4.0.9/scrollreveal.js"></script&gt; <!-- Biblioteca ScrollReveal para animações -->
    <script src="script.js"></script> <!-- JavaScript personalizado do site -->

</body>
</html>
<!DOCTYPE html> <!-- Declara o tipo de documento como HTML5 -->
<html lang="pt-BR"> <!-- Início do documento HTML, definido para o idioma português do Brasil -->
<head> <!-- Cabeçalho do documento, contém metadados e links -->
  <meta charset="UTF-8"> <!-- Define a codificação de caracteres como UTF-8 (compatível com acentos) -->
  <title>Urbanidade Urbana</title> <!-- Título da página exibido na aba do navegador -->
  <link rel="stylesheet" href="style.css"> <!-- Importa um arquivo CSS externo para estilizar a página -->
</head>
<body> <!-- Início do corpo da página, onde o conteúdo visível é inserido -->
  <header class="header-main"> <!-- Cabeçalho principal da página com classe para estilização -->
    <h1>Urbanidade Urbana</h1> <!-- Título principal da página -->
    <nav class="menu"> <!-- Menu de navegação com classe para estilização -->
      <a href="#">Início</a> <!-- Link de navegação (atualmente sem destino definido) -->
      <a href="#mobilidade">Mobilidade</a> <!-- Link âncora que leva à seção de mobilidade -->
      <a href="#sustentabilidade">Sustentabilidade</a> <!-- Link âncora que leva à seção de sustentabilidade -->
    </nav>
  </header>

  <main> <!-- Conteúdo principal da página -->
    <section class="intro"> <!-- Seção introdutória com classe para estilização -->
      <h2>O que é Urbanidade?</h2> <!-- Subtítulo da seção -->
      <p>… definição, respeito mútuo, convivência no espaço urbano …</p> <!-- Parágrafo com conteúdo descritivo -->
      <p>… importância de práticas sustentáveis e cooperativas na cidade …</p> <!-- Outro parágrafo complementar -->
    </section>

    <div class="gallery"> <!-- Container com classe para organizar uma galeria de seções -->
      <section id="mobilidade"> <!-- Seção com ID para âncora, sobre mobilidade urbana -->
        <h3>Mobilidade e Espaço Público</h3> <!-- Título da subseção -->
        <img src="images/cidade1.jpg" alt="Rua com ciclovia e pedestres"> <!-- Imagem ilustrativa com texto alternativo -->
        <p>Descrição sobre ciclovias, acessibilidade e convivência.</p> <!-- Parágrafo descritivo da imagem -->
      </section>

      <section id="sustentabilidade"> <!-- Seção com ID para âncora, sobre sustentabilidade urbana -->
        <h3>Sustentabilidade Urbana</h3> <!-- Título da subseção -->
        <img src="images/cidade2.jpg" alt="Parque urbano com árvores e bancos"> <!-- Imagem ilustrativa com texto alternativo -->
        <p>Descrição sobre áreas verdes, coleta seletiva e bem-estar.</p> <!-- Parágrafo descritivo da imagem -->
      </section>
    </div>
  </main>

  <footer class="footer-main"> <!-- Rodapé da página com classe para estilização -->
    <p>2025 Seu Nome. Conecte-se: <a href="#">Instagram</a> | <a href="#">LinkedIn</a></p> <!-- Texto de rodapé com links para redes sociais -->
  </footer>
</body>
</html> <!-- Fim do documento HTML -->

body {
  font-family: Arial, sans-serif; /* Define a fonte padrão do site como Arial, com alternativa sans-serif */
  margin: 0; /* Remove as margens padrão do corpo da página */
  line-height: 1.6; /* Define o espaçamento entre linhas para melhorar a legibilidade */
}

.header-main {
  background: #2c3e50; /* Define a cor de fundo do cabeçalho */
  color: white; /* Define a cor do texto como branco */
  padding: 1rem; /* Adiciona espaçamento interno de 1 rem ao redor do conteúdo */
  display: flex; /* Usa Flexbox para organizar os elementos horizontalmente */
  justify-content: space-between; /* Distribui os elementos com espaço entre eles */
  align-items: center; /* Alinha os itens verticalmente ao centro */
}

.menu a {
  color: white; /* Define a cor dos links do menu como branco */
  margin-left: 1rem; /* Adiciona espaço à esquerda de cada link (exceto o primeiro) */
  text-decoration: none; /* Remove o sublinhado padrão dos links */
}

.menu a:hover {
  text-decoration: underline; /* Ao passar o mouse, sublinha o link para indicar interatividade */
}

.intro {
  padding: 2rem; /* Adiciona espaçamento interno de 2 rem ao redor da seção introdutória */
}

.gallery {
  display: flex; /* Exibe os elementos filhos lado a lado usando Flexbox */
  gap: 1rem; /* Adiciona espaçamento de 1 rem entre os elementos */
  padding: 0 2rem; /* Adiciona espaçamento interno de 2 rem apenas nas laterais (direita e esquerda) */
}

.gallery section {
  flex: 1; /* Faz com que cada seção ocupe a mesma proporção do espaço disponível */
}

.gallery img {
  width: 100%; /* Faz a imagem ocupar 100% da largura do seu contêiner */
  height: auto; /* Mantém a proporção da imagem automaticamente */
  border-radius: 4px; /* Arredonda levemente os cantos da imagem */
}

.footer-main {
  background: #34495e; /* Define a cor de fundo do rodapé */
  color: white; /* Define a cor do texto como branco */
  text-align: center; /* Centraliza o texto do rodapé */
  padding: 1rem; /* Adiciona espaçamento interno de 1 rem ao redor do conteúdo */
}

@media (max-width: 768px) {
  .gallery {
    flex-direction: column; /* Em telas menores que 768px, exibe os elementos da galeria em coluna (verticalmente) */
  }
}
