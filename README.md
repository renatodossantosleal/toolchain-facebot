# Chat bots com Watson no Facebook

## Passo 1 - Crie uma página no Facebook
Acesse a sua timeline e crie uma página para o seu bot.

## Passo 2 - Crie um app no Facebook
1. Acesse https://developers.facebook.com/
2. Adicione a funcionalidade do Messenger ao app
3. Crie um Token associado a página criada no item 1 e guarde esse token.

## Passo 3 - Adicione suas credenciais
1. Edite o arquivo .env com as credenciais do conversation e seu token do facebook
2. Edite o arquivo manifest.yml com o caminho para a sua aplicação.

## Passo 4 - Suba a sua aplicação
Utilizando o Cloud Foundry submeta a sua aplicação para o Bluemix. Como:
1. Instale o CF (https://github.com/cloudfoundry/cli#downloads)
2. Navegue via console (cmd) até a pasta do seu projeto
3. Digite o comando **cf login** e preencha as informações requisitadas (o endpoint público é https://api.ng.bluemix.net)
4. Digite o comando **cf push** para submeter automaticamente sua aplicação

## Passo 5 - Atualize sua aplicação no facebook
