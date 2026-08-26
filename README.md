# JavaScript & Node.js

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)

Read in: [Português](README.pt.md) | English

Collection of vanilla JavaScript (ES6+) and Node.js exercises, covering language fundamentals, DOM manipulation, core Node modules, and a minimal Express server.

## Structure

```
.
├── es6/                    (ES6+ array/object methods exercises)
│   ├── index.html
│   └── scripts.js
├── javascript/              (JS fundamentals course, 10 sections)
│   ├── Seção 01/            (types, operators, template literals)
│   ├── Seção 02/ ... 09/
│   └── Seção 10/            (DOM manipulation, events)
└── nodejs/                  (Node.js exercises)
    ├── Express/              (minimal Express server)
    └── Seção 01/              (fs, http core modules)
```

## Contents

- **es6/** — vanilla JavaScript demonstrating ES6+ array methods (`filter`, etc.) on arrays and objects, run directly in the browser.
- **javascript/** — 10 standalone HTML/JS lessons progressing from JS fundamentals (`typeof`, operators, template literals) to DOM manipulation and event handling (`querySelector`, click handlers).
- **nodejs/Express/** — minimal Express (`^5.2.1`) app with a basic GET route on port 3000.
- **nodejs/Seção 01/** — Node core modules: `fs.readFile`/`writeFile` file exercises and a plain `http` server on port 9000.

## Setup

Browser lessons (`es6/`, `javascript/`) just need to be opened directly in a browser — no build step or dependencies.

```
cd nodejs/Express
npm install
node server.js
```

## Author

Lucas Nicolau — Software Engineering Student at @UFAM
