Business Model Canvas - Sleepwear (Rastreio QR) - Esse Canvas foi desenvolvido para um projeto de inovação que participei no Senai Cataguases

Este projeto é uma representação digital e interativa do Business Model Canvas (Quadro de Modelo de Negócios), desenvolvido em arquivo único (HTML/CSS) e focado em um modelo de negócios de pijamas (Sleepwear) com tecnologia de rastreabilidade via QR Code.

O objetivo deste código é fornecer uma forma rápida, elegante e pronta para impressão de visualizar e apresentar as 9 áreas fundamentais do seu negócio.

Principais Funcionalidades

Layout Fiel ao Original: Utiliza CSS Grid para recriar com exatidão a estrutura clássica do Business Model Canvas, com blocos de tamanhos proporcionais (Parcerias, Oferta de Valor, Custos, Receitas, etc.).

Pronto para PDF e Impressão: Inclui uma configuração específica de CSS (@media print) que ajusta automaticamente o tamanho da tela para uma folha A4 e esconde elementos desnecessários (como o botão de imprimir) na hora de gerar o documento final.

Sem Dependências: Código 100% nativo. Não é necessário instalar bibliotecas como Bootstrap ou frameworks complexos. Basta abrir e usar.

Exportação com 1 Clique: Um botão interativo no final da página que aciona nativamente a janela de impressão do navegador.

Tecnologias Utilizadas
HTML5: Estruturação semântica de todo o conteúdo.

CSS3: Estilização visual e posicionamento em grade (display: grid).

JavaScript: Um simples evento onclick="window.print()" inline para facilitar a exportação do Canvas.

Como Usar e Customizar

Este template é muito flexível e pode ser adaptado para qualquer outro modelo de negócios.

1. Rodando o projeto
Faça o download ou clone este repositório.

2. Editando o conteúdo
Abra o arquivo HTML em seu editor de código favorito (como o VS Code) e altere os textos dentro das tags ul e li de cada um dos 9 blocos. Você pode mudar o título, os emojis e as descrições de acordo com a sua necessidade.

Exemplo - Mudando a Oferta de Valor:

HTML div class="block oferta"
    h3 Oferta de Valor/h3
    ul
    li Sua nova proposta de valor aqui./li
    li Outro diferencial competitivo./li
    /ul
    /div

Dê um duplo clique no arquivo index.html (ou o nome que você salvou) para abri-lo diretamente em seu navegador (Chrome, Edge, Firefox, etc.).

3. Gerando o PDF
Com o arquivo aberto no navegador, role até o final da página e clique no botão verde "Clique aqui para Gerar PDF / Imprimir". Na janela que se abrir, selecione a opção de destino como "Salvar como PDF". Deve ser gerado em folhas maiores que A4.
