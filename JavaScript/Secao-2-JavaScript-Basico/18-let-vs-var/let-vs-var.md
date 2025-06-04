```markdown
# 📚 Resumo da Aula: Diferenças entre `var` e `let`

## 🔍 Principais Diferenças

### 1. Redeclaração de Variáveis
|                | `var` | `let` |
|----------------|-------|-------|
| Permite redeclarar? | ✅ Sim | ❌ Não (`SyntaxError`) |
| Exemplo:       | `var x = 1;`<br>`var x = 2;` // OK | `let y = 1;`<br>`let y = 2;` // ERRO |

### 2. Variáveis Globais Não-Declaradas
```javascript
// ❌ Ruim (cria variável global)
nome = "Luiz";

// ✅ Bom (escopo controlado)
let nome = "Luiz";
const PI = 3.14;
```

## ⏳ Contexto Histórico
- **ES6/ES2015**: Introduziu `let`/`const` para resolver problemas do `var`
- **JavaScript vs ECMAScript**:
  - `JS`: Implementação prática
  - `ES`: Padrão oficial da linguagem

## 💡 Boas Práticas
1. **Nomenclatura**:
   - ❌ `alturaEm100m` (ambiguo)
   - ✅ `alturaEmMetros` (descritivo)

2. **Uso Moderno**:
   ```mermaid
   flowchart LR
   A[Variável] -->|Valor muda?| B{Sim?}
   B -->|Não| C[const]
   B -->|Sim| D[let]
   ```

3. **Regra de Ouro**:
   > "Prefira `const`, use `let` quando necessário, e evite `var`"

## 🚀 Próximos Tópicos
- Escopo de variáveis (global vs bloco)
- Hoisting e Temporal Dead Zone
- Diferenças práticas em loops

🔹 **Dica Final**: Sempre declare variáveis explicitamente para evitar vazamentos de escopo!
```