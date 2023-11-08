# SalesWebMvc
Projeto MVC com .NET Core
Udemy
Professor: Nelio Alves

Este é o projeto final do curso Programação Orientada a Objetos utilizando C#. O objetivo é criar um sistema de vendedores com departamentos e registros de venda. Será abordado os fundamentos e a utilização do framework ASP .NET Core.
A persistência dos dados será feita a partir do Entity Framework, acessando um banco de dados MySQL. 

## Preparação do ambiente
- Criei um arquivo para documentar todo o processo
- Instalação do MySQL Server 8.1.0
- Instalação do .NET Core 2.1

## Desenvolvimento do Projeto
Para fins didáticos, na criação dos controllers e views, utilizei tanto a geração automática pelo Visual Studio quanto a implementação manual. A camada Serviços é responsável pelas regras de negócios e acesso aos dados. 
Foi utilizado o workflow CODE-FIRST, desenvolvendo as classes orientadas a objetos e a partir delas foi gerado o banco de dados utilizando migrations. 
O DB foi populado via SeedingService, independe de uma migration. 

## Operações assíncronas
Buscando um bom rendimento da aplicação quando é necessário fazer o acesso a dados. Durante o projeto foi abordado as operações assíncronas, utilizando a classe Task do System.Threading.Tasks. A atividade envolveu a refatoração de todos os métodos que acessam o banco de dados.


