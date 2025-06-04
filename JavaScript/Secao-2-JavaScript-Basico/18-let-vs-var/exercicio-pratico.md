```markdown
# 📝 Exercícios - `var`, `let` e `const` em JavaScript

## 1. Redeclaração de Variáveis
**Qual palavra-chave permite redeclarar uma variável no mesmo escopo sem erro?**  
```javascript
a) let
b) const
c) var ✅
d) Nenhuma
```
🔹 *Explicação: `var` permite redeclaração, enquanto `let`/`const` não.*

---

## 2. Erros com `let`
**O que acontece ao tentar redeclarar `let x = 1` com `let x = 2`?**  
```javascript
a) Sobrescreve silenciosamente
b) Ignora a segunda declaração
c) SyntaxError ✅ 
d) Torna global
```
⚠️ *Erro exato: `SyntaxError: Identifier 'x' has already been declared`*

---

## 3. Limitações do `const`
**Qual comportamento NÃO é permitido com `const`?**  
```javascript
a) Declarar sem valor inicial ❌
b) Reatribuir valor ✅ 
c) Usar em loops for
d) Ter escopo de bloco
```
💡 *`const` exige inicialização e é imutável após declaração*

---

## 4. Variáveis Globais
**Por que `nome = "Luiz"` (sem palavra-chave) é problemático?**  
```javascript
a) Vaza para o escopo global ✅
b) JS não reconhece
c) Não funciona em funções
d) Performance lenta
```
🚨 *Boas práticas: Sempre use `let`/`const` para evitar poluição global*

---

## 5. História do JavaScript
**Quando `let`/`const` foram introduzidos?**  
```javascript
a) ES5
b) ES6 (2015) ✅
c) ES3
d) ES2020
```
📜 *ECMAScript 6 trouxe melhorias no sistema de variáveis*

---

## 6. Escopo Seguro
**Qual declaração evita melhor vazamento de escopo?**  
```javascript
a) var x = 10
b) let x = 10 ✅
c) x = 10
d) const x = 10 ✅
```
📌 *`let`/`const` têm escopo de bloco, enquanto `var` vaza para funções*

---

## 7. Mensagens de Erro
**Qual erro aparece ao redeclarar `let nome`?**  
```javascript
a) ReferenceError
b) TypeError
c) SyntaxError ✅
d) Nenhum
```
🛑 *Erro específico: "Identifier 'nome' has already been declared"*

---

## 8. Diferença Fundamental
**Principal diferença entre `var` e `let`?**  
```javascript
a) var: bloco / let: global
b) var: função / let: bloco ✅
c) let não funciona em loops
d) var é mais moderno
```
🔍 *`var` tem escopo de função, `let` tem escopo de bloco*

---

## 9. Anti-Padrões
**O que EVITAR em código moderno?**  
```javascript
a) Usar const
b) Usar let
c) Usar var ✅
d) Nomes descritivos
```
💎 *Prefira `const` > `let` > `var` (último recurso)*

---

## 10. Comportamento do `var`
**O que este código imprime?**  
```js
var x = 10;
var x = 20;
console.log(x); // ?
```
```javascript
a) 10
b) 20 ✅
c) SyntaxError
d) undefined
```
🔄 *`var` permite redeclaração e a última atribuição prevalece*

---

## 📊 Gabarito Completo
| Q | Resposta | Conceito Testado |
|---|---|---|
| 1 | c | Redeclaração com `var` |
| 2 | c | Erros com `let` |
| 3 | b | Imutabilidade do `const` |
| 4 | a | Vazamento global |
| 5 | b | História do JS |
| 6 | b/d | Escopo seguro |
| 7 | c | Tipos de erro |
| 8 | b | Escopo var vs let |
| 9 | c | Boas práticas |
| 10 | b | Comportamento do `var` |

💡 **Dica**: Use `Ctrl + F` para buscar por 🔍 ou ✅ e revisar conceitos rapidamente!
```