```markdown
# 14. Constantes com `const`

## 🔒 O que são Constantes?
- **Definição**: Variáveis com valores fixos que não podem ser alterados após declaração
- **Características**:
  - Declaradas com `const`
  - Devem ser inicializadas imediatamente
  - Ideal para valores que não mudam no programa

---

## 📝 Regras para Nomear Constantes

| Regra | Exemplo Válido | Exemplo Inválido |
|-------|----------------|------------------|
| Não use palavras reservadas | `const MAX_SIZE = 100;` | `const const = 5;` ❌ |
| Nomes significativos | `const PI = 3.14;` | `const x = 3.14;` ❌ |
| Não comece com números | `const user1 = "João";` | `const 1user = "João";` ❌ |
| Use camelCase | `const fontSize = 16;` | `const font-size = 16;` ❌ |

---

## 🔄 Diferenças: Constantes vs Variáveis

```javascript
// Variável (mutável)
let contador = 0;
contador = 1; // ✅ Permitido

// Constante (imutável)
const MAX_USERS = 10;
MAX_USERS = 20; // ❌ TypeError: Assignment to constant variable
```

---

## 💡 Boas Práticas

### ✅ Recomendado
```javascript
const DEFAULT_COLOR = "#FFFFFF";
const TAX_RATE = 0.2;

// Cálculos com constantes
const preco = 100;
const total = preco * (1 + TAX_RATE); // 120
```

### ❌ Evitar
```javascript
const temp = 30; // Nome pouco descritivo
temp = 40;       // Tentativa de reatribuição (erro)
```

---

## 🧠 Tipos de Dados Dinâmicos

JavaScript é **fracamente tipado** - o tipo é definido pelo valor:

```javascript
const idade = 25;        // number
const nome = "Maria";    // string
const ativo = true;      // boolean

console.log(typeof idade); // "number"
console.log(nome + idade); // "Maria25" (coerção automática)
```

---

## 🏆 Dicas Profissionais

1. **Princípio**: 
   > "Use `const` por padrão, `let` quando necessário, e evite `var`" - Padrão ES6+

2. **Quando usar**:
   - `const`: Valores fixos (configurações, constantes matemáticas)
   - `let`: Contadores, valores que mudam em loops

3. **Benefícios**:
   - Código mais seguro (imutabilidade)
   - Mais fácil de entender (intenção clara)
   - Evita bugs por modificações acidentais

---

## 🔜 Próximo Tópico: Escopo de Variáveis
- Diferenças entre `let` e `const` em blocos
- Hoisting e Temporal Dead Zone
Here's the improved Markdown version with better structure, clarity, and visual elements:

```markdown
# 14. Constantes com `const`

## 🔒 O que são Constantes?
- **Definição**: Variáveis com valores fixos que não podem ser alterados após declaração
- **Características**:
  - Declaradas com `const`
  - Devem ser inicializadas imediatamente
  - Ideal para valores que não mudam no programa

---

## 📝 Regras para Nomear Constantes

| Regra | Exemplo Válido | Exemplo Inválido |
|-------|----------------|------------------|
| Não use palavras reservadas | `const MAX_SIZE = 100;` | `const const = 5;` ❌ |
| Nomes significativos | `const PI = 3.14;` | `const x = 3.14;` ❌ |
| Não comece com números | `const user1 = "João";` | `const 1user = "João";` ❌ |
| Use camelCase | `const fontSize = 16;` | `const font-size = 16;` ❌ |

---

## 🔄 Diferenças: Constantes vs Variáveis

```javascript
// Variável (mutável)
let contador = 0;
contador = 1; // ✅ Permitido

// Constante (imutável)
const MAX_USERS = 10;
MAX_USERS = 20; // ❌ TypeError: Assignment to constant variable
```

---

## 💡 Boas Práticas

### ✅ Recomendado
```javascript
const DEFAULT_COLOR = "#FFFFFF";
const TAX_RATE = 0.2;

// Cálculos com constantes
const preco = 100;
const total = preco * (1 + TAX_RATE); // 120
```

### ❌ Evitar
```javascript
const temp = 30; // Nome pouco descritivo
temp = 40;       // Tentativa de reatribuição (erro)
```

---

## 🧠 Tipos de Dados Dinâmicos

JavaScript é **fracamente tipado** - o tipo é definido pelo valor:

```javascript
const idade = 25;        // number
const nome = "Maria";    // string
const ativo = true;      // boolean

console.log(typeof idade); // "number"
console.log(nome + idade); // "Maria25" (coerção automática)
```

---

## 🏆 Dicas Profissionais

1. **Princípio**: 
   > "Use `const` por padrão, `let` quando necessário, e evite `var`" - Padrão ES6+

2. **Quando usar**:
   - `const`: Valores fixos (configurações, constantes matemáticas)
   - `let`: Contadores, valores que mudam em loops

3. **Benefícios**:
   - Código mais seguro (imutabilidade)
   - Mais fácil de entender (intenção clara)
   - Evita bugs por modificações acidentais

---