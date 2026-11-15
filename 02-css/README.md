# Etapa 2 — Estilização com CSS

Nesta segunda etapa, utilizei CSS para melhorar a apresentação visual do site desenvolvido anteriormente. A estrutura em HTML foi mantida, mas agora a página conta com cores, bordas, espaçamentos e ajustes na aparência dos elementos.

O objetivo foi deixar o conteúdo mais organizado e agradável de visualizar, mantendo um estilo simples.

## Organização do CSS

O arquivo `style.css` foi separado por elementos da página, facilitando a identificação e a manutenção das regras de estilo.

Utilizei seletores de elementos e seletores combinados para aplicar estilos em partes específicas do site, como `header`, `nav`, `section`, `article` e `footer`.

## Cabeçalho

O cabeçalho foi estilizado para destacar meu nome e minha apresentação.

- `background-color`: define a cor de fundo.
- `text-align`: centraliza os textos.
- `padding`: define o espaçamento interno.
- `border-bottom`: adiciona uma borda inferior para separar o cabeçalho do restante da página.
- `font-size`: ajusta o tamanho dos textos.
- `color`: define as cores dos títulos e parágrafos.

Na imagem de perfil, utilizei `width` e `height` para definir suas dimensões, `border-radius` para deixá-la circular e `object-fit: cover` para ajustar a imagem sem distorcer suas proporções.

## Navegação

A área de navegação recebeu um fundo próprio e foi centralizada para facilitar o acesso às seções do site.

- `list-style: none`: remove os marcadores padrão da lista.
- `display: inline-block`: permite posicionar os itens do menu lado a lado.
- `margin`: define o espaçamento entre os links.
- `text-decoration: none`: remove o sublinhado padrão dos links.
- `font-weight: bold`: destaca os textos do menu.
- `:hover`: altera a aparência dos links quando o cursor passa sobre eles.

## Seções e artigos

Para diferenciar as partes do conteúdo, utilizei estilos específicos para `section` e `article`.

Nas seções, foram aplicados:

- `background-color`: define o fundo branco.
- `padding`: cria espaçamento interno.
- `margin-bottom`: separa uma seção da outra.
- `border`: adiciona bordas para delimitar o conteúdo.

Nos artigos, utilizei um fundo levemente diferente, além de espaçamentos e bordas próprias, criando uma separação visual entre informações relacionadas.

Também defini cores diferentes para os títulos de segundo e terceiro nível, facilitando a identificação da hierarquia dos conteúdos.

## Formulário de contato

O formulário recebeu ajustes para melhorar a apresentação dos campos e facilitar o preenchimento.

- `display: inline-block`: permite posicionar os rótulos ao lado dos campos.
- `width`: define a largura dos rótulos e dos campos.
- `padding`: adiciona espaçamento interno aos campos.
- `border`: define as bordas dos campos de preenchimento.
- `vertical-align: middle`: alinha verticalmente a área de mensagem em relação aos demais elementos.
- `cursor: pointer`: altera o cursor ao passar sobre o botão.
- `:hover`: modifica a cor do botão quando o cursor passa sobre ele.

## Resultado

Ao final desta etapa, o site passou a contar com uma identidade visual própria, utilizando principalmente tons de azul e roxo, além de fundos claros e bordas para organizar as informações.

A estrutura HTML da primeira etapa foi preservada, enquanto o CSS ficou responsável por toda a apresentação visual da página.