# 📘 Guia de Atributos HTML

Os **atributos HTML** são usados para fornecer informações adicionais sobre os elementos.  
Eles sempre aparecem dentro da **tag de abertura** e seguem o padrão:

```html
<tag atributo="valor">Conteúdo</tag>
```

---

### Exemplo:

```html
<img src="./assets/Github.png" alt="Logotipo" width="100">
```

Aqui:

- `src` → caminho da imagem.  
- `alt` → texto alternativo (acessibilidade).  
- `width` → largura da imagem.  

---

## 🔹 Atributos Globais (funcionam na maioria das tags)

| Atributo  | Função |
|-----------|--------|
| **id** | Identifica um elemento de forma única. |
| **class** | Define uma ou mais classes para estilizar via CSS ou manipular com JS. |
| **style** | Adiciona estilos inline diretamente no elemento. |
| **title** | Mostra uma dica/tooltip quando passa o mouse. |
| **hidden** | Esconde o elemento sem removê-lo. |
| **draggable** | Define se o elemento pode ser arrastado (`true` ou `false`). |

### Exemplo:

```html
<p id="paragrafo1" class="texto" style="color:blue;" title="Sou uma dica!">
    Este é um parágrafo.
</p>
```

---

## 🔹 Atributos Específicos de Formulários

| Atributo  | Uso |
|-----------|-----|
| **type** | Tipo do campo (`text`, `number`, `email`, `password`, `file`...). |
| **name** | Nome do campo (identificação no envio do formulário). |
| **value** | Valor padrão do campo. |
| **placeholder** | Texto de exemplo dentro do campo. |
| **required** | Torna o campo obrigatório. |
| **disabled** | Desabilita o campo (não pode ser editado). |
| **checked** | Marca `checkbox` ou `radio` como selecionado. |
| **maxlength** | Limite de caracteres permitidos. |

### Exemplo:

```html
<form>
  <input type="text" name="usuario" placeholder="Digite seu nome" required>
  <input type="password" name="senha" maxlength="12">
  <input type="checkbox" name="newsletter" checked> Receber novidades
</form>
```

---

## 🔹 Atributos para Links e Imagens

| Tag  | Atributo | Função |
|------|----------|--------|
| `<a>` | **href** | Define o destino do link. |
| `<a>` | **target="_blank"** | Abre o link em nova aba. |
| `<a>` | **download** | Força o download do recurso. |
| `<img>` | **src** | Caminho da imagem. |
| `<img>` | **alt** | Texto alternativo. |
| `<img>` | **width, height** | Define tamanho da imagem. |

### Exemplo:

```html
<a href="https://www.google.com" target="_blank">Ir para o Google</a>

<img src="logo.png" alt="Logotipo da empresa" width="200">
```

---

## 📝 Regras Importantes

- Todo atributo fica na abertura da tag.  
- Alguns atributos podem ser **booleanos**: só escrever o nome já ativa.  

```html
<input type="checkbox" checked>
```
*(equivalente a `checked="checked")`.*

- Use atributos para semântica e comportamento, mas para estilo prefira **CSS**.  

---

