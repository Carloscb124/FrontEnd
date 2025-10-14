# 🧙‍♂️ Aventura JavaScript: Explorando IF, SWITCH e Laços de Repetição!

Bem-vindo(a) à floresta encantada do **JavaScript**, onde nosso herói **João** enfrenta desafios mágicos usando o poder das **estruturas de decisão e repetição**!  
Aqui você vai aprender, de forma leve e divertida, como o JavaScript pensa, escolhe caminhos e repete ações para conquistar qualquer missão.

---

## 🌳 Estruturas Condicionais: O Poder do `if`, `else if` e `else`

Imagine que você é o **João**, um herói em busca da princesa perdida.  
Durante sua jornada, você chega a uma **encruzilhada** e precisa decidir qual caminho seguir.  
É aí que entra a **magia do `if`**, que ajuda você a tomar decisões com base em condições!

```javascript
if (caminhoEsquerdo === 'obstaculo') {
  seguirCaminhoDireito();
} else if (caminhoEsquerdo === 'ponteQuebrada') {
  procurarOutroCaminho();
} else {
  seguirCaminhoEsquerdo();
}
```

👉 **Como funciona:**  
- O `if` verifica uma condição.  
- O `else if` testa outra possibilidade.  
- O `else` é o plano B — o que acontece se nenhuma das condições anteriores for verdadeira.

### 🛒 Exemplo prático
```javascript
let possuiOvos = true;
let itensComprados = "";

if(possuiOvos){
  itensComprados = "Leite";
} else {
  console.log("passou na sessão de congelados");
  itensComprados = "Lasanha congelada";
}

console.log("Item comprado: " + itensComprados);
```

---

## 🎨 Estrutura `switch case`

Agora imagine que você está escolhendo **camisetas por cor**.  
Cada cor representa uma opção diferente. É exatamente isso que o `switch` faz: ele compara um valor com várias possibilidades e executa o bloco correspondente.

```javascript
let dia = "terça";

switch (dia) {
  case "segunda":
    console.log("Dia de começar a semana com energia!");
    break;
  case "terça":
    console.log("Hora de aprender coisas novas!");
    break;
  case "quarta":
    console.log("Metade da semana, continue firme!");
    break;
  case "quinta":
    console.log("Quase lá, um pouco mais de esforço!");
    break;
  case "sexta":
    console.log("Dia de comemorar, o fim de semana está chegando!");
    break;
  default:
    console.log("Final de semana! Descanse e divirta-se!");
}
```

✨ **Palavras mágicas:**
- `switch`: inicia a verificação.
- `case`: define uma opção.
- `break`: para o código após encontrar o caso certo.
- `default`: é o “plano reserva” se nenhuma opção corresponder.

---

## 🔁 Estruturas de Repetição

Nem todo desafio se resolve com uma única ação. Às vezes, João precisa **repetir** algo até atingir o objetivo — e é aí que entram os **laços de repetição**: `for`, `while` e `do-while`.

---

### ⚙️ `for` — o contador disciplinado
Quando sabemos **quantas vezes** algo precisa acontecer, usamos o `for`.

```javascript
const numeros = [1, 2, 3, 4, 5];

for (let i = 0; i < numeros.length; i++) {
  console.log(numeros[i]);
}
```

🧩 Serve para percorrer listas, contar itens, e repetir ações um número definido de vezes.

---

### 🎲 `while` — o aventureiro incansável
Usado quando **não sabemos quantas vezes** precisaremos repetir algo.

```javascript
let jogadas = 0;
let cara = false;

while(!cara) {
  jogadas++;
  cara = Math.random() < 0.5;
}

console.log(`A moeda caiu cara após ${jogadas} jogadas!`);
```

💡 O `while` continua executando **enquanto** a condição for verdadeira.

---

### 🧁 `do-while` — o guloso persistente
Esse laço **executa pelo menos uma vez**, mesmo que a condição seja falsa depois.

```javascript
let bolinhosComidos = 0;

do {
  bolinhosComidos++;
  console.log("Você comeu", bolinhosComidos, "bolinhos!");
} while (bolinhosComidos < 5);
```

🍰 Ideal para situações em que precisamos garantir **pelo menos uma execução** antes da verificação.

---

## 🌟 Conclusão

- **Tomar decisões** com `if`, `else if`, `else` e `switch`.
- **Repetir ações** com `for`, `while` e `do-while`.
  
Essas ferramentas são a base para criar **jogos, sistemas inteligentes e aventuras interativas** — como a jornada do nosso herói João!  

