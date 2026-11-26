# Projeto B - Módulo 4 Full Cycle

Nivel escolhido: Projeto B (API de Domínio Único - Pedidos)

Como subir o projeto:

1. Clonar o repositorio e entrar na pasta:
   git clone <url-do-repositorio>
   cd marketplace-modular

2. Configurar o ambiente:
   cp .env.example .env

3. Instalar as dependencias:
   npm install

4. Subir os containers do Docker:
   docker-compose up -d

5. Rodar as migracoes do banco de dados:
   npx prisma migrate dev

6. Iniciar a aplicacao:
   npm run dev

O servidor vai rodar em http://localhost:3000.

Como testar:

Utilizar um cliente HTTP como Insomnia ou Postman para consumir os endpoints da API.s