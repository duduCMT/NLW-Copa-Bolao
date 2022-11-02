## Comandos Úteis:
``npx prisma migrate dev``: Cria a migração do banco de dados do prisma

``npx prisma db seed``: Popula o banco com os dados do arquivo [seed.ts](./prisma/seed.ts)

``npx prisma studio``: Executa no navegador uma interface de gerênciamento de banco de dados do prisma.

``npx prisma generate``: Gera um diagrama de relacionamento do banco de dados configurado no prisma.

## Estrutura do Banco de Dados

Estrutura gerada pelo prisma:

<div align="center">
  <div style="display: flex;">
    <img src="./prisma/ERD.svg" style="height: 500px;">
  </div>
</div>