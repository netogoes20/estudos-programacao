```markdown
# 📝 10 Questões sobre Constantes em JavaScript

## 1. Qual palavra-chave é usada para declarar uma constante em JavaScript?
```javascript
a) let
b) var
c) const  
d) static
```

## 2. O que acontece se tentarmos reatribuir um valor a uma constante?
```javascript
a) O valor é atualizado sem erros
b) Um erro é lançado  
c) A constante é automaticamente convertida em variável
d) Nada, pois constantes são imutáveis apenas em TypeScript
```

## 3. Qual das seguintes declarações está correta?
```javascript
a) const PI; PI = 3.14;  // ❌ Falta inicialização
b) const PI = 3.14;  
c) let PI = 3.14;  // (válido mas não constante)
d) const 3PI = 3.14;  // ❌ Nome inválido
```

## 4. Por que usar `const` em vez de `let`?
```javascript
a) Para permitir mudanças de valor no futuro
b) Para garantir imutabilidade acidental  
c) Para melhorar a performance
d) Para declarar funções
```

## 5. Qual é o tipo de `const nome = "JavaScript";`?
```javascript
a) number
b) boolean
c) string  
d) object
```

## 6. O que retorna `const soma = 10 + "5";`?
```javascript
a) 15 (number)
b) "105" (string)  // Coerção de tipos
c) Erro de tipo
d) NaN
```

## 7. Qual regra NÃO se aplica a constantes?
```javascript
a) Não pode começar com número
b) Não pode conter espaços
c) Deve ser sempre minúsculas  // CamelCase é permitido
d) Não pode usar palavras reservadas
```

## 8. O que `typeof` retorna para `const ativo = true;`?
```javascript
a) "string"
b) "number"
c) "boolean"  
d) "undefined"
```

## 9. Qual operador concatena strings?
```javascript
a) +  
b) -
c) *
d) /
```

## 10. Como corrigir `const x = 5; x = 10;`?
```javascript
a) Trocar const por let  
b) Usar var
c) Declarar sem valor
d) Nenhuma
```

---

## 🔍 Gabarito Detalhado

| Questão | Resposta | Explicação |
|---------|----------|------------|
| 1 | c | `const` é a palavra-chave correta |
| 2 | b | Constantes não podem ser reatribuídas |
| 3 | b | Única sintaxe válida mostrada |
| 4 | b | Principal vantagem de `const` |
| 5 | c | Strings usam aspas |
| 6 | b | JavaScript faz coerção para string |
| 7 | c | CamelCase é convenção (ex: `MAX_SIZE`) |
| 8 | c | `true`/`false` são booleanos |
| 9 | a | Operador de concatenação |
| 10 | a | `let` permite reatribuição |

💡 **Dica**: Use `Ctrl + F` para buscar por ✅ e verificar respostas rapidamente!
```