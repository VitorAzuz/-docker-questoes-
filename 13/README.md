# Questão 13 — Dockerfile para Node.js + Express

Este Dockerfile clona e executa o projeto [node-express-hello-world](https://github.com/eMahtab/node-express-hello-world).

## Instruções

```bash
docker build -t node-hello .
docker run -p 3000:3000 node-hello
