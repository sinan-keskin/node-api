# 🟩 node-api

Express tabanlı **REST API** örneği ⚡  

![Node.js](https://img.shields.io/badge/Node-%3E=18-339933) ![Express](https://img.shields.io/badge/Framework-Express-blue)
```markdown
### 📦 Özellikler
- 🔐 CORS, Helmet, Rate-limit  
- 🧾 Zod ile istek doğrulama  
- 🧪 Vitest test altyapısı  

```js
import express from "express";
const app = express();
app.get("/health", (_, res) => res.json({ ok: true }));
app.listen(3000, () => console.log("Server ready 🚀"));
