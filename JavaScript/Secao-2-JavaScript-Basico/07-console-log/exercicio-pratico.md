````markdown
# Exercícios Práticos - `console.log()` em JavaScript

Aqui estão 5 exercícios práticos com seus respectivos gabaritos. Estes exercícios abordam desde usos básicos até aplicações mais avançadas do `console.log()`.

---

## Exercício 1: Saída Básica
Escreva um código que use `console.log()` para exibir:
- Seu nome entre aspas duplas  
- Sua idade (como número)  
- Sua cidade entre aspas simples  

---

## Exercício 2: Cálculos Matemáticos
Use `console.log()` para exibir os resultados destas operações numa única chamada:
- 15 + 3  
- 20 / 4  
- 7 * 2  

---

## Exercício 3: Concatenação de Strings
Crie um código que:
1. Declare uma variável `nome` com seu nome  
2. Declare uma variável `idade` com sua idade  
3. Exiba no console a frase:  
   `"Meu nome é [nome] e tenho [idade] anos"`

---

## Exercício 4: Debug de Variáveis
Dado o código abaixo, corrija os erros para que funcione corretamente:
```javascript
let produto = "Notebook";
let preco = 3500;
console.log(O produto + produto + custa R$ + preco);
````

---

## Exercício 5: Template Strings

Converta este `console.log()` para usar template strings:

```javascript
let animal = "gato";
let patas = 4;
console.log("Um " + animal + " tem " + patas + " patas");
```

---

# Gabarito

### Solução 1:

```javascript
console.log("Seu Nome");
console.log(25); // Substitua pela sua idade
console.log('Sua Cidade');
```

### Solução 2:

```javascript
console.log(15 + 3, 20 / 4, 7 * 2);
// Saída: 18 5 14
```

### Solução 3:

```javascript
let nome = "Maria";
let idade = 30;
console.log("Meu nome é " + nome + " e tenho " + idade + " anos");
```

### Solução 4 (Correção):

```javascript
let produto = "Notebook";
let preco = 3500;
console.log("O produto " + produto + " custa R$ " + preco);
```

### Solução 5 (Template String):

```javascript
let animal = "gato";
let patas = 4;
console.log(`Um ${animal} tem ${patas} patas`);
```

---

## Dicas Extras:

* No Exercício 2, experimente separar os cálculos com textos explicativos
* No Exercício 3, tente refazer usando template strings
* No Exercício 4, teste o que acontece se remover todas as aspas

---

Esses exercícios ajudam a treinar a saída de dados no console, além de praticar concatenação, variáveis, e template strings.

```