# 📑 Forms - Exemplos de Formulários HTML

Esta pasta contém exemplos práticos de **formulários em HTML**.  
O objetivo é mostrar diferentes tipos de entradas (`input`) e como usá-las em páginas web.

---

## 📂 Arquivos

### 1. `index.html` - Formulário de Cadastro Simples
Formulário básico de cadastro com campos essenciais:

- **Text (`<input type="text">`)** → Nome do usuário  
- **Number (`<input type="number">`)** → Idade  
- **Password (`<input type="password">`)** → Senha  
- **Botão de envio** → Ao clicar, dispara um `alert("enviei um formulário")` com `onsubmit`.

👉 Uso: Ideal para aprender envio de formulários com **validação básica** e comportamento padrão de submissão.

---

### 2. `input.html` - Exemplos de Tipos de Inputs
Mostra vários tipos de campos suportados pelo HTML5:

- **Text** → Entrada livre de texto  
- **Number (com min, max e step)** → Limita valor mínimo, máximo e salto de incremento  
- **Range** → Slider para selecionar valor em um intervalo  
- **Color** → Escolha de cor  
- **Email** → Campo com validação automática de formato de email  
- **Date** → Seletor de data  
- **Checkbox** → Seleção múltipla (sim/não, múltiplos itens)  
- **Radio** → Seleção única dentro de um grupo  
- **File (multiple)** → Upload de um ou mais arquivos  
- **Search** → Campo de busca estilizado pelo navegador  

👉 Uso: Serve como catálogo de referência para aprender e experimentar **todos os tipos principais de inputs HTML**.

---

### 3. `checkbox.html` - Pedido de Pizza 🍕
Simulação de formulário de pedido:

- **Checkboxes** → Opcionais da pizza (queijo, calabresa, cebola, azeitona)  
- **Radio buttons** →  
  - Escolha da borda (sim ou não)  
  - Escolha da bebida (suco, refrigerante, água ou nenhum)  
- **Botão de envio** → Envia as escolhas usando `method="get"`

👉 Uso: Demonstra **combinação prática de checkboxes e radio buttons**, típico em formulários de escolha de produtos.

---

### 4. `form-botoes.html` - Testando Botões
Formulário que apresenta os diferentes tipos de botões em HTML:

- **Text** → Nome  
- **Number** → Idade  
- **Password** → Senha  
- **Botões**:
  - `type="button"` → Apenas clicável, pode receber eventos JS (ex: `onmouseover="alert()"`)  
  - `type="reset"` → Limpa os campos do formulário  
  - `type="submit"` → Envia os dados do formulário  

👉 Uso: Mostra as diferenças entre botões de **ação customizada, reset** e **envio**.

---

## 🚀 Como utilizar

1. Abra qualquer arquivo `.html` no navegador.  
2. Interaja com os campos e veja como cada input funciona.  
3. Teste diferentes valores, formatos e submissões.  

---

### 5. `form-select.html` - Formulário com Select (Dropdown)
Formulário que inclui um campo de seleção de cargo:

- **Text** → Nome  
- **Select (`<select>`)** → Cargo do usuário (Gerente, Diretor, Presidente)  
- **Text** → Assunto  
- **Botão de envio**

👉 Uso: Ensina a trabalhar com **listas suspensas (dropdowns)** em formulários.

---

### 6. `form-textarea.html` - Formulário com TextArea
Versão expandida do anterior, adicionando campo para mensagens longas:

- **Text** → Nome  
- **Select (`<select>`)** → Cargo do usuário (Gerente, Diretor, Presidente)  
- **Text** → Assunto  
- **Textarea (`<textarea>`)** → Campo para mensagens de múltiplas linhas  
- **Botão de envio**

👉 Uso: Mostra como criar campos de **entrada de texto mais extensos**, úteis em formulários de contato, feedback e suporte.

---

## 🛠️ Aplicações Práticas

- Criar cadastros de usuários e formulários de login.  
- Montar formulários de pedidos (ex: e-commerce, pizzarias).  
- Treinar o uso de diferentes tipos de `input` e suas propriedades (`min`, `max`, `step`, `multiple`).  
- Entender a diferença entre **seleção múltipla (checkbox)** e **seleção única (radio)**.  

---

## 📌 Próximos Passos

- Adicionar **validações customizadas em JavaScript**.  
- Melhorar o design com **CSS**.  
- Integrar formulários com **back-end** para salvar dados.  

---
