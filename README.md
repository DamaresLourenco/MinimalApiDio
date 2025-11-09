Projeto exemplo de **Minimal API** em .NET, criado para o desafio da DIO.

## Estrutura

```
MinimalApiDio/
├─ Program.cs
├─ MinimalApiDio.csproj
├─ Models/
│  └─ Todo.cs
├─ .gitignore
└─ README.md
```

## Requisitos

- .NET 8 SDK (ou ajuste o `<TargetFramework>` no `.csproj` para a sua versão, ex: `net7.0`)

## Rodando localmente

```bash
# dentro da pasta MinimalApiDio
dotnet restore
dotnet run
```

A API estará disponível em `https://localhost:5001` (ou a porta informada no terminal).
Para testar a API, abra o Swagger em `https://localhost:5001/swagger`.

## Endpoints

- `GET /` - Mensagem de boas-vindas
- `GET /todos` - Lista todas as tarefas
- `GET /todos/{id}` - Busca tarefa por id
- `POST /todos` - Cria uma nova tarefa
- `PUT /todos/{id}` - Atualiza uma tarefa
- `DELETE /todos/{id}` - Remove uma tarefa

