# WebRest

Começo do sistema da Schafer Representações. O `package.json` descreve um frontend React com Vite, Bootstrap e SQLite. O `index.html` é a casca dessa página. O `index.js` tenta subir uma API Express na porta `3000` (ou `PORT`) com CORS e duas montagens:

- `/produtos`
- `/api/auth`

Os módulos `./routes/produtos`, `./routes/authRoutes` e `./config/database`, e também `src/main.jsx`, não estão neste commit. Sem esses arquivos o servidor e a página não sobem.

## Como rodar

```bash
npm install
node index.js
```
