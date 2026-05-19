# minicurso-react-back

djakjsasal

Backend simples em Node.js + Express usado no mini-curso **Introdução ao React, Git e Boas Práticas**.

Devolve um `Hello World` em JSON na rota raiz para o front-end consumir.

## Como rodar

```bash
npm install
npm run dev
```

A API sobe em [http://localhost:3001](http://localhost:3001).

## Endpoint

| Método | Rota | Resposta                          |
| ------ | ---- | --------------------------------- |
| GET    | `/`  | `{ "message": "Hello World" }`    |
