# Update25 - Sistema Web com Banco de Dados

Este repositório contém um projeto web desenvolvido com ASP.NET Core, Entity Framework Core e SQL Server. O objetivo do projeto é fornecer um sistema funcional com integração a banco de dados para gerenciar informações.

## Tecnologias Utilizadas

- **ASP.NET Core** - Framework para desenvolvimento web em .NET
- **Entity Framework Core** - ORM para interação com banco de dados
- **SQL Server** - Banco de dados relacional
- **Bootstrap** - Framework CSS para estilização e responsividade

## Configuração do Ambiente

### Requisitos

Antes de iniciar, certifique-se de ter instalado:
- **.NET SDK** (versão compatível com o projeto)
- **SQL Server** ou **Azure SQL Database**
- **Visual Studio** ou **VS Code** (com extensão C#)

### Clonando o Repositório

```sh
git clone https://github.com/EduardoGiannini/Update25.git
cd Update25
```

### Configurando o Banco de Dados

1. Atualize a string de conexão no arquivo `appsettings.json`, caso necessário:

```json
"ConnectionStrings": {
  "DefaultConnection": "Server=SEU_SERVIDOR;Database=NOME_DO_BANCO;User Id=USUARIO;Password=SENHA;"
}
```

2. Execute as migrações para criar o banco de dados:

```sh
dotnet ef database update
```

### Executando o Projeto

Para rodar o projeto, utilize o comando:

```sh
dotnet run
```

A aplicação estará disponível em `https://localhost:5001` ou `http://localhost:5000`.

## Funcionalidades Implementadas

- Gerenciamento de usuários
- Cadastro e listagem de registros
- Integração com banco de dados


## Licença

Este projeto está licenciado sob a licença MIT.


