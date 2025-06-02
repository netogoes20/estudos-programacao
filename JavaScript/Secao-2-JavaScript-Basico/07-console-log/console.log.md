````md
# Resumo da Aula: 7. `console.log` - A primeira coisa que você vai ver em JS

## Introdução

- A função `console.log()` é essencial para exibir informações no console ou debugar códigos em JavaScript.
- Será uma ferramenta usada constantemente na carreira de desenvolvimento.

---

## Sintaxe do `console.log()`

- **Formato básico**:
  
  ```js
  console.log("Texto ou valor a ser exibido");
````

* **Ponto e vírgula (`;`)**:

  * Opcional em JavaScript, mas recomendado para organização e clareza do código.

---

## Exibindo Valores

### 1. Textos (Strings)

* Devem estar entre **aspas**: simples `' '`, duplas `" "`, ou crases `` ` ` ``.

  ```js
  console.log("Luís Otávio");  // Aspas duplas
  console.log('Luís Otávio');  // Aspas simples
  console.log(`Luís Otávio`);  // Crases (Template Strings)
  ```

* **Regra importante**:

  * Se o texto contiver **aspas simples**, use **aspas duplas** por fora (e vice-versa).

    ```js
    console.log("Otávio 'Miranda'");  // Aspas simples dentro do texto
    console.log('Otávio "Miranda"');  // Aspas duplas dentro do texto
    ```

### 2. Números

* Não usam aspas (são valores literais).
* Números decimais usam **ponto** (não vírgula):

  ```js
  console.log(35);       // Número inteiro
  console.log(15.85);    // Número decimal (ponto flutuante)
  ```

### 3. Múltiplos Valores

* Separe por vírgulas para exibir vários dados na mesma linha:

  ```js
  console.log(35, 15.85, "Luís Otávio");
  ```

---

## Tipos de Dados

* **String**: Texto entre aspas (ex.: `"JavaScript"`).
* **Number**: Números (inteiros ou decimais).

  * Em JavaScript, não há separação entre "inteiro" e "decimal" – tudo é do tipo `number`.

---

## Onde o `console.log()` Aparece?

* **Apenas no console**:

  * No VS Code (usando Node.js, por exemplo) ou no navegador (F12 > Console).
  * **Não aparece** para o usuário final – apenas para debug do desenvolvedor.

---

## Por Que Usar?

* **Debug**: Verificar valores de variáveis, fluxo do código, etc.
* **Praticidade**: Ferramenta fundamental para aprendizado e desenvolvimento.

---

## Próximos Passos

* Aprofundar em **variáveis**, **tipos de dados** e **Template Strings**.

> 💡 **Dica**: Use `console.log()` sempre que precisar testar algo no código!

```