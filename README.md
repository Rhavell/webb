Luiz Rhavell silva de Oliveira
Primeiro, aqui está uma
estrutura de diretório básica:
```
meu-projeto/
├── frontend/
│ ├── index.html
│ ├── styles.css
│ └── scripts.js
└── backend/
 ├── server.js
 └── items.js
```
Aqui está um exemplo de código simples para a parte frontend (index.html):
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>Lista de Itens</title>
 <link rel="stylesheet" href="styles.css">
</head>
<body>
 <h1>Lista de Itens</h1>
 <ul id="item-list"></ul>
 <script src="scripts.js"></script>
</body>
</html>
```
Aqui está um exemplo de código simples para o frontend (scripts.js) que usa
JavaScript para exibir uma lista de itens:
```javascript
const itemList = document.getElementById("item-list");
// Suponhamos que você tenha uma lista de itens
const items = ["Item 1", "Item 2", "Item 3"];
// Popule a lista de itens
items.forEach(item => {
 const li = document.createElement("li");
 li.textContent = item;
 itemList.appendChild(li);
});
```
Agora, para a parte do backend (server.js), usando Node.js e Express.js:
```javascript
const express = require("express");
const app = express();
const port = 3000;
// Rota para obter a lista de itens
app.get("/api/items", (req, res) => {
 // Suponhamos que você tenha uma lista de itens aqui
 const items = ["Item 1", "Item 2", "Item 3"];

 res.json(items);
});
app.listen(port, () => {
 console.log(`Servidor rodando na porta ${port}`);
});
```
Primeiro, aqui está uma estrutura de diretório básica:
```
meu-projeto/
├── frontend/
│ ├── index.html
│ ├── styles.css
│ └── scripts.js
└── backend/
 ├── server.js
 └── items.js
```
Aqui está um exemplo de código simples para a parte frontend (index.html):
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>Lista de Itens</title>
 <link rel="stylesheet" href="styles.css">
</head>
<body>
 <h1>Lista de Itens</h1>
 <ul id="item-list"></ul>
 <script src="scripts.js"></script>
</body>
</html>
```
Aqui está um exemplo de código simples para o frontend (scripts.js) que usa
JavaScript para exibir uma lista de itens:
```javascript
const itemList = document.getElementById("item-list");
// Suponhamos que você tenha uma lista de itens
const items = ["Item 1", "Item 2", "Item 3"];
// Popule a lista de itens
items.forEach(item => {
 const li = document.createElement("li");
 li.textContent = item;
 itemList.appendChild(li);
});
```
Agora, para a parte do backend (server.js), usando Node.js e Express.js:
```javascript
const express = require("express");
const app = express();
const port = 3000;
// Rota para obter a lista de itens
app.get("/api/items", (req, res) => {
 // Suponhamos que você tenha uma lista de itens aqui
 const items = ["Item 1", "Item 2", "Item 3"];

 res.json(items);
});
app.listen(port, () => {
 console.log(`Servidor rodando na porta ${port}`);
});
```
Primeiro, aqui está uma estrutura de diretório básica:
```
meu-projeto/
├── frontend/
│ ├── index.html
│ ├── styles.css
│ └── scripts.js
└── backend/
 ├── server.js
 └── items.js
```
Aqui está um exemplo de código simples para a parte frontend (index.html):
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>Lista de Itens</title>
 <link rel="stylesheet" href="styles.css">
</head>
<body>
 <h1>Lista de Itens</h1>
 <ul id="item-list"></ul>
 <script src="scripts.js"></script>
</body>
</html>
```
Aqui está um exemplo de código simples para o frontend (scripts.js) que usa
JavaScript para exibir uma lista de itens:
```javascript
const itemList = document.getElementById("item-list");
// Suponhamos que você tenha uma lista de itens
const items = ["Item 1", "Item 2", "Item 3"];
// Popule a lista de itens
items.forEach(item => {
 const li = document.createElement("li");
 li.textContent = item;
 itemList.appendChild(li);
});
```
Agora, para a parte do backend (server.js), usando Node.js e Express.js:
```javascript
const express = require("express");
const app = express();
const port = 3000;
// Rota para obter a lista de itens
app.get("/api/items", (req, res) => {
 // Suponhamos que você tenha uma lista de itens aqui
 const items = ["Item 1", "Item 2", "Item 3"];

 res.json(items);
});
app.listen(port, () => {
 console.log(`Servidor rodando na porta ${port}`);
});
