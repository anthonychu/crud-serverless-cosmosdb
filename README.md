# CRUD Serverless com Azure Functions & CosmosDb

[![bit-community.png](https://i.postimg.cc/zGhWZqX7/bit-community.png)](https://postimg.cc/bZzd1cnS)

Repositório responsável por persistir os verbos HTTP's (GET, POST, DELETE, PUT) via CosmosDb, fazendo uso da arquitetura Serverless com Azure Functions.

## Recursos Utilizados 🚀

- **[Visual Studio Code](https://code.visualstudio.com/?WT.mc_id=cosmosdbserverless-github-gllemos)**
- **[Node.js](https://nodejs.org/en/)**
- **[Extensão Visual Studio Code: Azure Functions](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azurefunctions&WT.mc_id=cosmosdbserverless-github-gllemos)**
- Mongodb Community Server **[DOWNLOAD AQUI](https://www.mongodb.com/download-center/community)**
- MongodB Compass GUI **[DOWNLOAD AQUI](https://www.mongodb.com/download-center/compass)**
- **[Conta Azure - Conta Gratuita](https://azure.microsoft.com/free/?WT.mc_id=cosmosdbserverless-github-gllemos)**

## Conta - Azure for Students ⭐️

Caso você seja um(a) estudante de alguma Instituição de Ensino de Faculdade ou Universidade, poderá criar sua conta no **[Azure for Students](https://azure.microsoft.com/pt-br/free/students/?WT.mc_id=cosmosdbserverless-github-gllemos)**. Essa conta te dará o benefício em possuir crédito de USD 100,00 para usar os serviços de maneira gratuita, sem necessidade de possuir um cartão de crédito. Para ativar essa conta, bastam acessar o link ao lado: **[AQUI](https://azure.microsoft.com/pt-br/free/students/?WT.mc_id=cosmosdbserverless-github-gllemos)**

## Sobre a Demo 💻

Aqui ensino como você pode persistir um dado usando o HTTP Trigger, via POST direto no MongoDb local.

## Executando localmente a aplicação

1. Para executar localmente a aplicação, você precisa primeiramente baixar o pacote npm do azure function tools globalmente na sua máquina por meio do comando:

```bash
> npm i -g azure-functions-core-tools --unsafe-perm true
```

2. Execute o MongoDb ou MongoDb Compass!

3. Agora, abre novamente o seu prompt de comando e execute o comando:

```bash
> func host start
```

Abre o Postman. Agora você poderá:

* Criar um novo 'Funcionário' em: [POST] `http://localhost:7071/api/funcionario` 
* Listar todos os Funcionários em: [GET] `http://localhost:7071/api/funcionarios` 
* Listar um Funcionário pelo Id em: [GET] `http://localhost:7071/api/funcionario/{id}` 
* Atualizar um Funcionário pelo Id em: [PUT] `http://localhost:7071/api/funcionario/{id}` 
* Excluir um Funcionário pelo Id em: [DELETE] `http://localhost:7071/api/funcionario/{id}` 

## Links & Recursos Importantes ❗️

Durante o workshop, comentei sobre importantes documentações, links e recursos que podem auxiliar o seu conhecimento sobre Serverless & Azure Functions

- ✅ **[Link dos Slides da Palestra](https://aka.ms/AA5vqcu)**
- ✅ **[Azure para devs JavaScript & Node.js](https://docs.microsoft.com/pt-br/javascript/azure/?WT.mc_id=cosmosdbserverless-github-gllemos&view=azure-node-latest)**
- ✅ **[Documentação Azure Functions](https://docs.microsoft.com/pt-br/azure/azure-functions/?WT.mc_id=cosmosdbserverless-github-gllemos)**
- ✅ **[Criando a sua Primeira Função no Visual Studio Code](https://docs.microsoft.com/pt-br/azure/azure-functions/functions-create-first-function-vs-code?WT.mc_id=cosmosdbserverless-github-gllemos)**
- ✅ **[Extensão Vs Code – Azure Functions](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azurefunctions&WT.mc_id=cosmosdbserverless-github-gllemos)**
- ✅ **[E-Book Grátis - Azure Serverless Computing Cookbook](https://azure.microsoft.com/pt-br/resources/azure-serverless-computing-cookbook/?WT.mc_id=cosmosdbserverless-github-gllemos)**
- ✅ **[Cursos Grátis - Azure Functions](https://docs.microsoft.com/pt-br/learn/paths/create-serverless-applications/?WT.mc_id=cosmosdbserverless-github-gllemos)**

## Dúvidas?! ❗️❗️

Se tiverem alguma dúvida referente ao código desenvolvido ou para configurar o ambiente de desenvolvimento, bastam criar uma **[ISSUE AQUI](https://github.com/glaucia86/crud-serverless-cosmosdb/issues)** no GitHub que estarei respondendo a vocês o mais breve possível!! :D :D