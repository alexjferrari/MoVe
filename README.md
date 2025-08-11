# MoVe Backend - Inicial

## Como rodar (Docker)

1. Copie o .env.example para .env e ajuste se necessário.
2. `docker-compose up --build`

O serviço irá rodar em http://localhost:4000

## Rotas iniciais

- GET / -> status
- POST /auth/login -> login (body: { email, senha })
- GET /alertas -> lista alertas (requires Authorization: Bearer <token>)
- POST /alertas -> cria alerta (requires token)
