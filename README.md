# Idades

### Tarefa: Desenvolvimento de sistema cliente-servidor (para 25/3, às 10h)

Desenvolva um sistema cliente-servidor que forneça a idade de pessoas cujos nomes são entrados dentro do cliente.

O cliente deve ter uma GUI onde o usuário entra com o nome. Aí o cliente manda este nome para o servidor e ele retorna a idade da pessoa ou então a expressão "Não sei", se a pessoa não estiver cadastrada.

O servidor não precisa acessar um banco de dados. Vocês podem armazenar uns 20 nomes na memória mesmo (ou carregar de um arquivo texto, quando iniciarem a operação do servidor). O objetivo é apenas vocês desenvolverem este aplicativo simples.

Vocês devem mandar os fontes e os executáveis tanto do cliente quanto do servidor, assim como um pequeno manual ou instruções claras o suficiente para que eu use os programas de vocês. Os programas devem ser claros e compreensíveis - comentem o que for necessário.

Vocês podem usar fragmentos de código da Internet, mas se copiarem integralmente algum programa, vocês receberão nota zero pelo plágio.

### Tecnologias

AspNetCore 3.0 Preview
React 16.0.0

### Instruções

É Nescessario:
Runtime ou SDK do DotNet Core 3.0 Preview 3 https://dotnet.microsoft.com/download/dotnet-core/3.0
Nodejs LTS https://nodejs.org/en/

Na pasta ClientApp execute no seu Terminal o comando "npm i".
Na pasta raiz execure "dotnet run".
Navegue na url https://localhost:5001 ou http://localhost:5000 no seu navegador.
