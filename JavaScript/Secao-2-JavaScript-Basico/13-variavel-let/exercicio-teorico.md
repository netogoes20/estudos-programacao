
```markdown
# Exercícios de Fixação – Variáveis em JavaScript

## 1. Qual é a principal função de uma variável em programação?  
a) Executar operações matemáticas  
b) Definir estilos CSS  
c) Armazenar dados temporariamente   
d) Criar elementos HTML  

## 2. Qual palavra-chave é usada para declarar uma variável mutável em JavaScript?  
a) `const`  
b) `var`  
c) `variable`  
d) `let`   

## 3. O que ocorre ao declarar uma variável sem atribuir valor?  
a) Recebe automaticamente o valor `null`  
b) O código retorna um erro  
c) Seu valor fica vazio (`""`)  
d) Recebe o valor `undefined`   

## 4. Qual formato segue a convenção de nomenclatura para variáveis compostas?  
a) `nome-cliente`  
b) `NomeCliente` (PascalCase)  
c) `nome_cliente`  
d) `nomeCliente` (camelCase)   

## 5. Qual nome de variável é **inválido** em JavaScript?  
a) `_idade`  
b) `nomeCompleto`  
c) `2alunos`   
d) `$saldo`  

## 6. O que significa "case-sensitive" no contexto de variáveis?  
a) Nomes devem ter apenas letras minúsculas  
b) Palavras reservadas não podem ser usadas  
c) Maiúsculas/minúsculas diferenciam variáveis   
d) Espaços são permitidos nos nomes  

## 7. Qual comportamento acontece ao tentar redeclarar `let x = 5` com `let x = 10`?  
a) A variável é atualizada para `10`  
b) O JavaScript ignora a segunda declaração  
c) Um erro é gerado   
d) Ambas as variáveis coexistem  

## 8. Qual será o valor impresso no console?  
```javascript
let cor = "azul";
cor = "verde";
console.log(cor);
```  
a) `azul`  
b) `verde`   
c) `undefined`  
d) Nenhuma das anteriores  

## 9. Por que evitar nomes genéricos como `x` ou `a` para variáveis?  
a) O JavaScript não os reconhece  
b) Tornam o código menos legível   
c) Causam erros de sintaxe  
d) Limitam o escopo da variável  

## 10. Qual palavra-chave **não** deve ser usada para declarar variáveis modernamente?  
a) `let`  
b) `const`  
c) `var`  
d) `def`   

---

## 🔍 Gabarito  
| Questão | Resposta | Explicação |  
|---------|----------|------------|  
| 1 | c | Variáveis armazenam dados na memória |  
| 2 | d | `let` é a forma moderna para variáveis mutáveis |  
| 3 | d | Variáveis não inicializadas são `undefined` |  
| 4 | d | camelCase é a convenção padrão em JS |  
| 5 | c | Nomes não podem começar com números |  
| 6 | c | JS diferencia maiúsculas/minúsculas |  
| 7 | c | Redeclaração com `let` gera erro |  
| 8 | b | A última atribuição prevalece |  
| 9 | b | Nomes descritivos melhoram legibilidade |  
| 10 | d | `def` não existe em JS |  

```
