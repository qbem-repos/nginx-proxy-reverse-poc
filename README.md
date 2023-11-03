# poc-microfront
Foi realizado o deployment do Nginx Proxy Manager sem senhas importantes, por isso não há secrets. Também é perciso subir um mariadb antes para conectar o storage.

## TODO: 
* Usar Vault
* Usar pv e pvc para storage
* Ativar o ingress para ativação do LetsEncrypt
* Realizar o teste de um Host Proxy no Nginx Proxy Manager com o n8n e verificar a possibilidade de uso dele como gerenciador de rotas do Back for Friend do PEP
* Ocultar o hash do webhook do n8n

## Como criar um teste de webhook com hash no N8N
1. Abrir um workflow de teste
2. Criar um nó Webhook
3. Em path colocar /patients/:id como se estivesse buscando por id
4. Clicar em List for Test Event
