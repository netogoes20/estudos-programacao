````markdown
# Aula 4: Comentários em JavaScript

## 🧠 O que são comentários?
- São trechos de código **ignorados** pela engine do JavaScript.
- Servem para fazer **anotações** ou explicar partes do código sem afetar sua execução.

---

## 📝 Tipos de Comentários

### 1. Comentário de linha única
- **Sintaxe:** `// texto do comentário`
- **Exemplo:**
  ```js
  console.log("Olá, mundo!"); // Isso é um comentário e não será executado
````

* Funciona apenas na **linha atual**.

### 2. Comentário de bloco (multilinha)

* **Sintaxe:** `/* texto do comentário */`
* Pode abranger **várias linhas**.
* **Exemplo:**

  ```js
  /*
    Este é um comentário
    que ocupa múltiplas linhas.
    Nenhuma parte dele será executada.
  */
  ```

---

## 🎯 Para que servem?

* Explicar trechos complexos do código.
* Desativar temporariamente partes do código sem apagá-las (*útil para testes*).
* Documentar funções, bibliotecas ou autores.

---

## 💻 Exemplo Prático

```js
console.log("Linha 1");
// console.log("Linha 2 - comentada e ignorada");
/*
console.log("Linha 3 - também ignorada");
console.log("Linha 4 - dentro do bloco de comentário");
*/
console.log("Linha 5 - executada normalmente");
```

**Saída no console:**

```
Linha 1  
Linha 5 - executada normalmente
```

---

## ⚠️ Observações Importantes

* **Engine do JavaScript:** O Node.js e o Google Chrome usam a mesma engine (*V8*).
* **Cuidado:** Sempre salve o arquivo antes de executar (`Ctrl + S`).
* **Boas práticas:** Use comentários para clareza, mas evite excessos (código limpo é melhor).

---

## 🚀 Próxima aula

Continuaremos explorando conceitos básicos do JavaScript!

```