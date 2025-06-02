```markdown
## 12. Navegador vs Node (HTML + JavaScript)

### Introdução  
- A aula aborda como mesclar JavaScript com HTML, começando com uma revisão rápida.  

### Integrando JS com HTML  

1. **Arquivo HTML básico:**  
   - Criado **`index.html`** com a estrutura padrão (atalho no VS Code: **`!`** ou **`html:5`**).  

2. **Incluindo JavaScript:**  
   - **Método 1 (não recomendado):**  
     - Dentro do **`<head>`** ou **`<body>`**.  
     - Problema: Pode atrasar o carregamento da página.  
     ```html
     <script>
       console.log("Olá Mundo");
     </script>
     ```  

   - **Método 2 (recomendado):**  
     - Arquivo externo (**`index.js`**) vinculado ao final do **`<body>`**:  
     ```html
     <script src="index.js"></script>
     ```  
     - Vantagem: Organização e performance.  

---

### Diferença entre Ambientes  

- **Navegador vs Node.js:**  
  - **Navegador:**  
    - Tem objetos como **`alert()`** e acesso ao **DOM** (ex.: manipular elementos da página).  
    ```js
    alert("Meu nome é Luiz Otávio"); // Funciona no navegador
    ```  

  - **Node.js:**  
    - Não tem **`alert()`** (gera erro: *`alert is not defined`*).  
    - Usado para back-end (servidores, bancos de dados).  

---

### Boas Práticas  

- **Separação de Códigos:**  
  - Manter HTML, CSS e JS em arquivos distintos.  
  - Exemplo: Criar pasta **`/js`** para scripts.  
  ```html
  <script src="js/index.js"></script>
  ```  

- **Formatação:**  
  - No VS Code, usar **"Format Document"** (botão direito) para organizar o código.  
```