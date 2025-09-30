# Combinadores CSS 🔗

Os **combinadores CSS** permitem selecionar elementos HTML com base em
suas relações entre si. Eles ajudam a ser mais específico e organizado
na hora de aplicar estilos.

------------------------------------------------------------------------

## Tipos de Combinadores

### 1. **Combinador Descendente (`espaço`)**

Seleciona **todos os elementos dentro de outro**, em qualquer nível de
profundidade.

``` css
div p {
  color: green;
}
```

👉 Todos os `<p>` dentro de um `<div>` ficam verdes, mesmo que estejam
em níveis aninhados.

------------------------------------------------------------------------

### 2. **Combinador de Filho Direto (`>`)**

Seleciona apenas os **filhos diretos** de um elemento.

``` css
ul > li {
  list-style: square;
}
```

👉 Apenas os `<li>` diretamente dentro de `<ul>` terão marcadores
quadrados.

------------------------------------------------------------------------

### 3. **Combinador de Irmão Adjacente (`+`)**

Seleciona o **primeiro elemento imediatamente após outro**.

``` css
h1 + p {
  font-style: italic;
}
```

👉 Apenas o `<p>` logo após um `<h1>` ficará em itálico.

------------------------------------------------------------------------

### 4. **Combinador de Irmãos Gerais (`~`)**

Seleciona **todos os elementos irmãos seguintes**.

``` css
h1 ~ p {
  color: blue;
}
```

👉 Todos os `<p>` que aparecem depois de um `<h1>` (no mesmo nível)
ficarão azuis.

------------------------------------------------------------------------

## Exemplo Completo

``` html
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Exemplo de Combinadores</title>
  <style>
    div p { color: green; }       /* Descendente */
    ul > li { color: red; }       /* Filho direto */
    h1 + p { font-weight: bold; } /* Irmão adjacente */
    h2 ~ p { font-style: italic;} /* Irmãos gerais */
  </style>
</head>
<body>
  <div>
    <p>Sou descendente do div</p>
    <section>
      <p>Também sou descendente (mesmo aninhado)</p>
    </section>
  </div>

  <ul>
    <li>Sou filho direto</li>
    <ol>
      <li>Não sou filho direto do ul</li>
    </ol>
  </ul>

  <h1>Título H1</h1>
  <p>Sou irmão adjacente do H1</p>
  <p>Não sou adjacente, mas poderia ser pego pelo ~</p>

  <h2>Título H2</h2>
  <p>Sou irmão geral do H2</p>
  <p>Eu também sou irmão geral</p>
</body>
</html>
```

------------------------------------------------------------------------

## Resumo 📌

-   `A B` → todos os descendentes\
-   `A > B` → apenas filhos diretos\
-   `A + B` → apenas o próximo irmão\
-   `A ~ B` → todos os irmãos seguintes

Dominar combinadores deixa o CSS mais **preciso e limpo**, evitando
excesso de classes e IDs.
