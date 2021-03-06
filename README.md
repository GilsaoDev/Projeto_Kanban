# Projeto_Kanban API

Desafio Técnico - Backend
O propósito desse desafio é a criação de uma API que fará a persistência de dados de um quadro de kanban. Esse quadro possui listas, que contém cards.

A API foi feita em c# usando .net core 6.0 com a implementanção do padrão MinimalAPI.

O recurso do .NET 6.0 - Minimal APIs - para a ASP .NET Core 6, permite criar APIs com o mínimo de dependência do framework WebAPI e o mínimo de código e arquivos necessários para o desenvolvimento minimalista de APIs.


Para executar os Endpoints siga os passos: 

1- Após clonar o repositório Projeto_Kanban, via CLI acesse a pasta da API, construa e execute o projeto:
 
Sequência de Comandos a serem executandos no Console:

 - cd Projeto_Kanban/Back/Kanban.API/
 - dotnet build 
 - dotnet run

2- Após executar a API, será aberto o SwaggerUI no navegador. Realize a autenticação no SwaggerUI com o Endpoint: Autenticacao (AutenticacaoEndpoints). No corpo do método insira as informações conforme abaixo:

{
  "login": "letscode",
  "senha": "lets@123"
}

Se tudo estiver ok, será gerado um Token como resposta. Copie no Buffer (Ctrl + C).

3 - Clique no botão Authorize (o primeiro que tem o cadiado). 
    No formulário modal que abrirá insira: "Bearer espaço 'Token gerado no item anterior'". 

    Ex: "Bearer #5994471ABB01112AFCC18159F6CC74B4F511B99806D787987129347987CADFADGFHADAER5"

Se ocorrer tudo bem o formulario exibira a informação: "Authorized".

4 - Use os endpoints de Cards a vontade.

