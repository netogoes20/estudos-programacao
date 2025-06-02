```markdown
# 13. Variáveis com `let`

## 📌 Conceito de Variáveis
- **Definição**: Elementos fundamentais em programação para armazenamento de dados
- **Funções**:
  - 🧠 Armazenar valores na memória durante a execução
  - 🔄 Permitir reutilização de valores sem repetição
  - ✏️ Exemplo: Substituir "João" por `nome` em múltiplos lugares

---

## 📝 Declaração de Variáveis em JavaScript

### 1. `let` (Recomendado)
```javascript
let nome = "João";  // Declaração com valor inicial
let idade;          // Declaração sem valor (undefined)
```
- ✅ Moderno
- 🔄 Mutável (valor pode ser alterado)
- 🏷️ Escopo de bloco (mais seguro)

### 2. `var` (Legado)
- ⚠️ Funciona, mas possui peculiaridades de escopo
- 🔄 Mutável como `let`
- 📅 Será detalhado em tópicos futuros

---

## ⚠️ Regras para Nomear Variáveis

| Regra | Exemplo Válido | Exemplo Inválido |
|-------|----------------|-------------------|
| Não use palavras reservadas | `nomeUsuario` | `let = "João"` |
| Nomes significativos | `saldoConta` | `x` |
| Não comece com números | `item1` | `1item` ❌ |
| Use camelCase | `dataNascimento` | `data-nascimento` ❌ |
| Case-sensitive | `nome` ≠ `Nome` | |

---

## 💡 Boas Práticas

### ✅ Recomendado
```javascript
let clienteAtivo = true;  // Nome descritivo
clienteAtivo = false;     // Modificação permitida
```

### ❌ Evitar
```javascript
let x = 10;               // Nome pouco descritivo
let nome = "A";
let nome = "B";           // Redeclaração (erro)
```

---

## 🧠 Exemplo Prático

**Antes (repetição)**:
```javascript
console.log("Otávio nasceu em 1984.");
console.log("Em 2002, Otávio conheceu Maria.");
```

**Depois (com variável)**:
```javascript
let nome = "Otávio";
console.log(`${nome} nasceu em 1984.`);
console.log(`Em 2002, ${nome} conheceu Maria.`);
```

**Vantagem**: Alteração em único ponto

---

## 🔜 Próximos Passos
- **Constantes com `const`**: Valores imutáveis
- **Escopo de variáveis**: Diferenças entre `let` e `var`

## 💎 Dica Profissional
> "Prefira sempre `let` para variáveis mutáveis e escolha nomes que revelem a intenção do código." - Clean Code Principles
```