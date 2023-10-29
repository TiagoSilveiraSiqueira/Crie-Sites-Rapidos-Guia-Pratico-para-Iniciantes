# Capítulo 3: CSS: Estilizando seu Site

Neste capítulo, você aprenderá como usar o CSS (Cascading Style Sheets) para dar estilo e aparência ao conteúdo de suas páginas da web. O CSS é fundamental para tornar seu site atraente e visualmente agradável.

## O que é CSS?

CSS, ou Cascading Style Sheets, é uma linguagem de estilo usada para controlar a apresentação visual de um documento HTML. Ele permite que você defina cores, fontes, espaçamento e layout, tornando seu site mais atraente e fácil de ler.

Aqui está um exemplo simples de como o CSS é usado:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Minha Página Estilizada</title>
    <style>
        h1 {
            color: blue;
        }
        p {
            font-size: 16px;
        }
    </style>
</head>
<body>
    <h1>Título em Azul</h1>
    <p>Este é um parágrafo com tamanho de fonte aumentado.</p>
</body>
</html>
```

Neste exemplo, o CSS é incorporado diretamente no documento HTML usando a tag `<style>`. As regras CSS definem que os cabeçalhos `<h1>` serão azuis e os parágrafos `<p>` terão um tamanho de fonte de 16 pixels.

## Seletores CSS

Os seletores CSS são usados para direcionar elementos HTML específicos e aplicar estilos a eles. Alguns exemplos de seletores incluem:

- `h1`: Seleciona todos os elementos `<h1>`.
- `p`: Seleciona todos os elementos `<p>`.
- `#id`: Seleciona um elemento com um ID específico, por exemplo, `<div id="conteudo">`.
- `.classe`: Seleciona elementos com uma classe específica, por exemplo, `<p class="destaque">`.

## Propriedades de Estilo

As propriedades CSS definem como os elementos HTML serão estilizados. Algumas propriedades comuns incluem:

- `color`: Define a cor do texto.
- `font-size`: Define o tamanho da fonte.
- `margin`, `padding`: Controlam o espaçamento em torno dos elementos.
- `background-color`: Define a cor de fundo de um elemento.

## Posicionamento de Elementos

Você também pode usar CSS para controlar o posicionamento de elementos na página. Propriedades como `position` e `float` permitem criar layouts personalizados.

Agora que você entende o básico do CSS, você está pronto para começar a estilizar seu site. No próximo capítulo, exploraremos como publicar seu site na web.

[Próximo: Publicando seu Site](publicando-seu-site.md)
```

Este capítulo apresenta os conceitos fundamentais do CSS, incluindo seletores CSS, propriedades de estilo e posicionamento de elementos. Os links no final do capítulo direcionam os alunos para o próximo capítulo sobre publicação de sites. Certifique-se de criar o arquivo "publicando-seu-site.md" e continuar a desenvolver o conteúdo para os capítulos subsequentes do curso.
