🌐 WebAPI ASP.NET Core

Projeto de exemplo de uma API Web desenvolvida com ASP.NET Core Minimal API utilizando .NET 10.

A aplicação disponibiliza um endpoint simples para geração de previsões climáticas aleatórias, servindo como base para estudos de APIs REST, rotas, OpenAPI e desenvolvimento backend com C#.

🚀 Tecnologias Utilizadas
C#
ASP.NET Core Minimal API
.NET 10
OpenAPI / Swagger

⚙️ Funcionalidades
API REST utilizando Minimal API
Endpoint GET para previsão do tempo
Geração aleatória de temperaturas
Integração com OpenAPI
Suporte a HTTPS
📌 Endpoint Disponível
GET /weatherforecast

Retorna uma lista com previsões climáticas aleatórias.

Exemplo de resposta
[
  {
    "date": "2026-05-21",
    "temperatureC": 28,
    "summary": "Warm",
    "temperatureF": 82
  }
]
▶️ Como Executar o Projeto
1. Clonar o repositório
git clone https://github.com/seu-usuario/webapi.git
2. Acessar a pasta do projeto
cd webapi
3. Restaurar dependências
dotnet restore
4. Executar a aplicação
dotnet run
🌍 Acessando a API

Após executar o projeto, a API estará disponível em:

https://localhost:xxxx/weatherforecast

A porta pode variar conforme a configuração do ambiente.

📖 OpenAPI

Em ambiente de desenvolvimento, a documentação OpenAPI é habilitada automaticamente.

🧪 Arquivo de Testes HTTP

O projeto possui o arquivo:

webapi.http

Ele pode ser utilizado para realizar testes rápidos da API diretamente no Visual Studio Code ou Visual Studio.

🎯 Objetivo do Projeto

Este projeto foi criado com foco em aprendizado e prática de:

Desenvolvimento de APIs REST
ASP.NET Core
Minimal APIs
Estruturação de projetos backend
Configuração de rotas e endpoints
Desenvolvido para estudos e prática com ASP.NET Core Web API.
