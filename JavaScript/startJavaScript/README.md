# 🐉 Projeto: Introdução ao JavaScript com Pokémons

Este mini projeto tem como objetivo demonstrar **conceitos básicos de variáveis, constantes e arrays (vetores e matrizes)** em **JavaScript**, usando o universo do **Pokémon** como exemplo.  
É um exercício simples e divertido para fixar fundamentos essenciais da linguagem.

---

## 💡 Conceitos abordados

### 🧱 `const`
- Usada para **valores que não mudam** durante a execução do programa.  
  ```js
  const notificacao = "Pokemon GO diz: "
  ```

### 🔁 `let`
- Usada para **variáveis que podem ser alteradas**.  
  ```js
  let poteCafe = "Café 123"
  poteCafe = "Café 3 Corações"
  ```

---

## 🧾 Exemplos de saída no console

```js
console.log(notificacao + "Tem um novo Pokémon na região")
console.log(notificacao + "Você foi derrotado por um líder")
```

E com as variáveis de cozinha:
```js
console.log(menssagem + poteCafe + " - " + poteAcucar + " - " + poteBiscoito)
```

---

## 🧩 Trabalhando com vetores e matrizes

### Vetor (array simples)
Lista de Pokémons:
```js
let nomesPokemon = ["pikachu", "charmander", "bulbassaur"]
```

### Matriz (array dentro de array)
Time de Pokémons com nome, gênero e level:
```js
let timePokemon = [
    ["pikachu", "M", 1],
    ["charmander", "F", 7]
]
```

### Exemplo de acesso:
```js
console.log(
  "O Pokémon " + timePokemon[1][0] +
  " é do sexo " + timePokemon[1][1] +
  " e está no level " + timePokemon[1][2]
)
```

---

## ⚙️ Como executar

1. Crie um arquivo chamado `index.js`.
2. Cole o código dentro dele.
3. Execute no terminal com:
   ```bash
   node index.js
   ```
4. Observe as saídas no console.

---

## 🧠 Dica extra
Sempre que trabalhar com **arrays dentro de arrays**, lembre-se:
- O primeiro índice (`[0]`, `[1]`, etc.) representa **a linha**.
- O segundo índice (`[0]`, `[1]`, `[2]`, etc.) representa **a coluna** dentro daquela linha.

---

## 🕹️ Resultado esperado
Saídas semelhantes a:
```
Pokemon GO diz: Tem um novo Pokémon na região
Pokemon GO diz: Você foi derrotado por um líder
Na cozinha hoje têm: Café 123 - Açúcar cristal - Biscoito maizena
Os potes que você tem: Café 3 Corações - Açúcar cristal - Biscoito maizena
O Pokémon charmander é do sexo F e está no level 7
```

---

## 🧑‍💻 Autor
**Carlos** — estudante de programação e tecnologia, explorando o mundo do JavaScript de forma prática e divertida.
