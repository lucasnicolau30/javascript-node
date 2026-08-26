# JavaScript & Node.js

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)

Leia em: Português | [English](README.md) 

Coleção de exercícios de JavaScript puro (ES6+) e Node.js, cobrindo fundamentos da linguagem, manipulação do DOM, módulos nativos do Node e um servidor Express minimalista.

## Estrutura

```
.
├── es6/                    (Exercícios de métodos de array/objeto ES6+)
│   ├── index.html
│   └── scripts.js
├── javascript/              (Curso de fundamentos JS, 10 seções)
│   ├── Seção 01/            (tipos, operadores, template literals)
│   ├── Seção 02/ ... 09/
│   └── Seção 10/            (manipulação do DOM, eventos)
└── nodejs/                  (Exercícios de Node.js)
    ├── Express/              (servidor Express minimalista)
    └── Seção 01/              (módulos nativos fs, http)
```

## Conteúdo

- **es6/** — JavaScript puro demonstrando métodos de array ES6+ (`filter`, etc.) em arrays e objetos, executado diretamente no navegador.
- **javascript/** — 10 aulas independentes em HTML/JS, progredindo de fundamentos de JS (`typeof`, operadores, template literals) até manipulação do DOM e eventos (`querySelector`, handlers de clique).
- **nodejs/Express/** — aplicação Express (`^5.2.1`) minimalista com uma rota GET básica na porta 3000.
- **nodejs/Seção 01/** — módulos nativos do Node: exercícios de arquivo com `fs.readFile`/`writeFile` e um servidor `http` simples na porta 9000.

## Configuração

As aulas de navegador (`es6/`, `javascript/`) só precisam ser abertas diretamente no navegador — sem build ou dependências.

```
cd nodejs/Express
npm install
node server.js
```

## Autor

Lucas Nicolau — Estudante de Engenharia de Software na @UFAM
