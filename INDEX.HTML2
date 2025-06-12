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



Estrutura sugerida = style.css

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
