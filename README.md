# OpenBaseNet.Web.Components.Package

[![NuGet Version](https://img.shields.io/nuget/v/w3ti.OpenBase.Web.Components.svg)](https://www.nuget.org/packages/w3ti.OpenBase.Web.Components/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Um pacote com helpers e middlewares úteis para acelerar o desenvolvimento de aplicações web ASP.NET Core.

O primeiro componente deste pacote é um **Middleware de Tratamento Global de Exceções**, 
projetado para padronizar as respostas de erro da sua API.

## Por que usar este pacote?

Toda API robusta precisa de um tratamento de exceções consistente. 
Em vez de usar blocos `try-catch` em todos os seus controllers ou deixar que o ASP.NET retorne uma página HTML de erro, 
este middleware intercepta qualquer exceção não tratada e a converte em uma resposta JSON padronizada e amigável.

Isso garante que sua API sempre se comporte de maneira previsível, mesmo quando ocorrem erros inesperados.

## Instalação

Você pode instalar o pacote diretamente do NuGet:

```bash
dotnet add package w3ti.OpenBase.Web.Components
```
