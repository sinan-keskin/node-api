# 🟩 node-api

A simple and modern **Express-based REST API example** ⚡  
Includes validation, security middleware, and a minimal testing setup.

![Node](https://img.shields.io/badge/Node-%3E%3D18-green?style=flat-square)
![Express](https://img.shields.io/badge/Framework-Express-lightgrey?style=flat-square)

---

## 🧩 Features

- 🛡 **Security middleware**: CORS, Helmet, Rate-limit  
- 🧪 **Request validation** using **Zod**  
- 🧫 **Testing setup** with **Vitest**  
- ⚡ Minimal and clean Express server structure  
- 🔍 Includes `/health` endpoint for quick checks

---

## 📦 Example

```js
import express from "express";

const app = express();

app.get("/health", (_, res) => res.json({ ok: true }));

app.listen(3000, () => console.log("Server ready 🚀"));
```

## 🚀 Getting Started
Install dependencies
```bash
npm install
```
Run the server
```bash
node index.js
```
With nodemon (optional)
```bash
npm install -g nodemon
nodemon index.js
```
## 🧪 Testing
```bash
npm test
```
Vitest is included for lightweight and fast test execution.

## 📁 Project Structure
```pgsql
node-api/
│── index.js
│── package.json
└── README.md
```

## 🎯 Goal

To provide a minimal yet complete Express REST API template featuring:

- Modern middleware
- Input validation
- A lightweight testing environment
- Beginner-friendly clean code

Perfect for learning, prototyping, or starting small backend projects.

