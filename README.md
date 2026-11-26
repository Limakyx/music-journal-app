Music Journal App
Aplicacao desenvolvida inicialmente como Projeto B e que evoluiu para a arquitetura de Monolito Modular (Projeto A), estruturada em cinco dominios principais: Catalog, Journal, Subscriptions, Orders e Payments.
Tecnologias Utilizadas
 * Node.js com Fastify e TypeScript
 * Prisma ORM com SQLite
 * Swagger para documentacao da API
 * Tailwind CSS
 * Docker e Docker Compose
Como Subir o Projeto
 * Clonar o repositorio e entrar na pasta:
git clone https://github.com/Limakyx/music-journal-app.git
cd music-journal-app

 * Configurar o ambiente:
cp .env.example .env

 * Instalar as dependencias:
npm install

 * Subir os containers do Docker:
docker-compose up -d

 * Rodar as migracoes do banco de dados:
npx prisma migrate dev

 * Iniciar a aplicacao:
npm run dev

O servidor ira rodar em http://localhost:3000.
Como Testar
Pode utilizar um cliente HTTP como o Insomnia, Postman ou aceder diretamente ao Swagger UI para explorar e consumir os endpoints da API.
