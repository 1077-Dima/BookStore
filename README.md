BookStore - Full Stack CRUD Application

Technologies:
- ASP.NET Core Web API
- React
- Entity Framework Core
- PostgreSQL

Features:
- Create books
- Edit books
- Delete books
- View list

How to run:

### Requirements
- .NET 8
- Node.js
- Docker

1. Start PostgreSQL database

Run PostgreSQL container:

docker run -d \
  --name bookstore-db \
  -e POSTGRES_USER=postgres \
  -e POSTGRES_PASSWORD=postgres \
  -e POSTGRES_DB=bookstore \
  -p 5432:5432 \
  postgres

2. Run backend

cd backend
dotnet run

3. Run frontend

cd frontend
npm install
npm start
