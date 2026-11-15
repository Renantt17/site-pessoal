# Etapa 3 — Mobile First e Responsividade

Nesta terceira etapa, adaptei o site para funcionar melhor em diferentes tamanhos de tela, utilizando a estratégia Mobile First. A ideia foi começar pensando nos dispositivos móveis e depois adicionar ajustes para tablets e computadores.

Também aproveitei para adicionar alguns recursos que melhoram a identificação e a apresentação do site quando ele é acessado ou compartilhado.

## Mobile First

A estrutura principal do CSS foi desenvolvida considerando primeiro as telas menores. Para isso, foram realizadas algumas alterações:

- Utilização de `width: 100%` para permitir que o conteúdo ocupe a largura disponível.
- Utilização de `max-width` para limitar a largura de elementos sem impedir sua adaptação.
- Ajustes nos campos do formulário para que não ultrapassem a tela.
- Organização inicial dos links de navegação em coluna.
- Ajuste das imagens com `max-width: 100%`, evitando que ultrapassem o espaço disponível.

## Media Queries

Foram utilizadas media queries para adaptar o layout conforme a largura da tela:

- **768px:** ajustes para tablets, colocando os itens de navegação lado a lado e modificando o posicionamento dos rótulos do formulário.
- **1200px:** ajustes para telas maiores, incluindo a alteração do tamanho do título principal.

As media queries permitem aplicar estilos específicos sem precisar criar uma página diferente para cada dispositivo.

## Configurações gerais

Também foram adicionadas algumas regras para melhorar o comportamento dos elementos:

- `box-sizing: border-box`: considera o preenchimento e as bordas dentro das dimensões definidas para os elementos.
- `margin: 0`: remove a margem padrão do navegador no corpo da página.
- `font-family`: mantém a fonte Arial utilizada nas versões anteriores.

## Recursos adicionais no HTML

Além da responsividade, foram adicionados alguns elementos ao `head` da página:

- **Favicon:** utiliza a imagem `icone.jpg` para identificar o site na aba do navegador.
- **Meta Description:** apresenta uma breve descrição do conteúdo do portfólio.
- **Open Graph:** define título, descrição, imagem, endereço e tipo de conteúdo para a pré-visualização ao compartilhar o site.
- **Twitter Cards:** define como o link será apresentado quando compartilhado no X.

## Imagens utilizadas

- `perfil.jpg`: utilizada como foto de perfil no cabeçalho e como imagem de pré-visualização nos compartilhamentos.
- `icone.jpg`: utilizada como favicon do site.

## Testes de responsividade

A página deve ser verificada em diferentes larguras utilizando o modo responsivo do DevTools do navegador:

- Mobile: aproximadamente 375px.
- Tablet: aproximadamente 768px.
- Desktop: 1200px ou mais.

Durante os testes, os principais pontos observados são a navegação, a organização dos textos, as imagens e o formulário de contato.

## Resultado

Com esta etapa, o site passou a contar com uma estrutura adaptável a diferentes dispositivos, mantendo a identidade visual desenvolvida anteriormente. Também foram adicionados recursos para melhorar sua identificação no navegador e sua apresentação quando compartilhado.