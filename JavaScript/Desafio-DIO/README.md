# 🦸‍♂️ Desafio Classificador de Nível de Herói

## 🧩 Sobre o Desafio
Projeto proposto pela **Digital Innovation One (DIO)** com o objetivo de praticar lógica de programação utilizando **JavaScript**.  
A missão é criar um programa que classifique o nível de um herói com base na quantidade de experiência (XP).

---

## 🧠 O que foi utilizado
- **Variáveis**
- **Operadores**
- **Estruturas de decisão (`if`, `else if`, `else`)**
- **Laços de repetição (opcional, se quiser testar vários heróis)**

---

## 🎯 Objetivo

Criar uma variável para armazenar o **nome** e a **quantidade de experiência (XP)** de um herói e, com base nesse valor, exibir o nível correspondente de acordo com as faixas abaixo:

| Faixa de XP          | Nível        |
|----------------------|--------------|
| Menor que 1.000      | Ferro        |
| 1.001 até 2.000      | Bronze       |
| 2.001 até 5.000      | Prata        |
| 5.001 até 7.000      | Ouro         |
| 7.001 até 8.000      | Platina      |
| 8.001 até 9.000      | Ascendente   |
| 9.001 até 10.000     | Imortal      |
| Maior ou igual a 10.001 | Radiante  |

---

## 💻 Exemplo de Código

```javascript
let nome = "Carlos";
let xp = 6500;
let nivel;

if (xp < 1000) {
  nivel = "Ferro";
} else if (xp <= 2000) {
  nivel = "Bronze";
} else if (xp <= 5000) {
  nivel = "Prata";
} else if (xp <= 7000) {
  nivel = "Ouro";
} else if (xp <= 8000) {
  nivel = "Platina";
} else if (xp <= 9000) {
  nivel = "Ascendente";
} else if (xp <= 10000) {
  nivel = "Imortal";
} else {
  nivel = "Radiante";
}

console.log(`O Herói de nome ${nome} está no nível de ${nivel}`);
```

---

## 🧾 Saída Esperada

```
O Herói de nome Carlos está no nível de Ouro
```

---

## 🚀 Como executar

1. Copie o código em um arquivo chamado `index.js`.
2. Execute no terminal com:
   ```bash
   node Desafio-DIO/index.js
   ```
3. Veja a mensagem exibindo o nome e o nível do herói.

---

## 🧙‍♂️ Autor
**Carlos Eduardo**  

