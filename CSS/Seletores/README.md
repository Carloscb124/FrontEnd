# Seletores CSS 🖌️

Este documento explica de forma simples os **seletores CSS**, que são
usados para "apontar" quais elementos do HTML vão receber estilos.

## O que são seletores?

Seletores são instruções que dizem ao navegador: **"aplique este estilo
neste elemento"**.\
Exemplo:

``` css
p {
  color: blue;
}
```

Esse seletor `p` altera a cor de **todos os parágrafos** para azul.

------------------------------------------------------------------------

## Tipos de Seletores

### 1. **Seletor Universal (`*`)**

Aplica estilo a **todos** os elementos da página.

``` css
* {
  margin: 0;
  padding: 0;
}
```

### 2. **Seletor de Tipo (Tag)**

Aplica a uma **tag específica** do HTML.

``` css
h1 {
  font-size: 32px;
}
```

### 3. **Seletor de Classe (`.nome`)**

Aplica a elementos que possuem um atributo `class`.

``` css
.titulo {
  color: red;
}
```

``` html
<h2 class="titulo">Sou vermelho</h2>
```

### 4. **Seletor de ID (`#nome`)**

Aplica a um elemento único que tem um atributo `id`.

``` css
#principal {
  background-color: lightgray;
}
```

``` html
<div id="principal">Área principal</div>
```

### 5. **Seletores de Atributo**

Selecionam elementos com base em atributos.

``` css
input[type="text"] {
  border: 1px solid black;
}
```

### 6. **Seletores Combinadores**

Permitem "navegar" entre elementos relacionados.

-   **Descendente (`espaço`)**\

``` css
div p {
  color: green;
}
```

(Seleciona `<p>` dentro de `<div>`)

-   **Filho direto (`>`)**\

``` css
ul > li {
  list-style: square;
}
```

-   **Irmão adjacente (`+`)**\

``` css
h1 + p {
  font-style: italic;
}
```

### 7. **Pseudoclasses (`:`)**

Estados ou condições especiais dos elementos.

``` css
a:hover {
  color: orange;
}
```

### 8. **Pseudoelementos (`::`)**

Criam partes "falsas" de um elemento.

``` css
p::first-letter {
  font-size: 24px;
  color: red;
}
```

------------------------------------------------------------------------

## Ordem de Prioridade (Especificidade)

Quando dois seletores diferentes afetam o mesmo elemento, existe uma
hierarquia:

1.  `!important` (evite usar, só em último caso)\
2.  `#id`\
3.  `.classe`\
4.  `tag`\
5.  `*`

------------------------------------------------------------------------

## Exemplo Completo

``` html
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Exemplo CSS</title>
  <style>
    * { margin: 0; padding: 0; }
    body { font-family: Arial; }
    h1 { color: darkblue; }
    .destaque { color: red; }
    #rodape { background: lightgray; text-align: center; }
    a:hover { color: green; }
  </style>
</head>
<body>
  <h1>Seletores em ação</h1>
  <p class="destaque">Sou um parágrafo destacado.</p>
  <div id="rodape">Rodapé da página</div>
</body>
</html>
```

------------------------------------------------------------------------

🔹 **Resumo:** Seletores CSS são a base para aplicar estilos em qualquer
página. Dominar classes, IDs e pseudoclasses é essencial para criar
layouts flexíveis e responsivos.
