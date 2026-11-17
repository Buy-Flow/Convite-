# Convite digital | Clicar Veículos

Convite interativo para a inauguração em 21/11/2026, com formulário de confirmação e painel administrativo.

## Executar

Requer Node.js 20+.

```bash
npm install
ADMIN_PASSWORD='defina-uma-senha-forte' npm start
```

Acesse http://localhost:3000 e o painel em http://localhost:3000/admin.html.

## Publicação

Hospede em serviço que execute Node.js e tenha **armazenamento persistente** para o SQLite. Configure `ADMIN_PASSWORD` como segredo e `DATA_DIR` apontando para volume persistente. GitHub Pages sozinho não suporta o backend, portanto não armazena confirmações. Nunca envie o banco de dados ou senhas ao GitHub. Configure HTTPS, privacidade e retenção de dados antes de distribuir aos clientes.
