# Components HTML

componentes html personalizados para facilitar o desenvolvimento de paginas web e reduzir o código repetido

## Instalação

Para instalar e utilizar os componentes HTML personalizados em seu projeto, siga os passos abaixo:

1. Baixe o arquivo `customComponents.js` do repositório.
1. Adicione o arquivo baixado ao seu projeto.
1. Inclua o arquivo `customComponents.js` em seu arquivo HTML usando a tag `<script>`. Por exemplo:

```html
<script src="caminho/para/o/arquivo/customComponents.js"></script>
```

## Uso

Por padrão, o script `customComponents.js` tenta listar os componentes a partir da URL `/components`. No entanto, se necessário, você pode alterar essa configuração padrão.

### Exemplo

Se você tiver um arquivo chamado `navbar.html` na pasta de componentes, você pode usar o componente personalizado correspondente em seu HTML simplesmente criando a tag `<c-navbar></c-navbar>`.

Este padrão se aplica a qualquer arquivo na pasta de componentes. Para usar o componente personalizado, basta criar uma tag com o prefixo `c-` seguido pelo nome do arquivo.

Por exemplo, se você tiver um arquivo `header.html`, você pode usar o componente correspondente com a tag `<c-header></c-header>`.

## Configuração

Você pode personalizar o caminho e o prefixo dos componentes personalizados ao incluir o script `customComponents.js` em seu arquivo HTML.

Aqui está um exemplo de como você pode fazer isso:

```html
<script path="/components" prefix="c-" src="customComponents.js"></script>
```

Neste exemplo, o atributo path define o caminho de onde o script vai listar os componentes. O atributo prefix define o prefixo que será usado para criar as tags dos componentes personalizados.

Por exemplo, se você definir o prefixo como `v-`, você usaria a tag `<v-navbar></v-navbar>` para usar o componente navbar.html.

Você pode definir o prefixo como qualquer string que desejar, desde que seja compatível com a sintaxe de tags HTML.
