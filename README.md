# poc-microfront
Foi realizado o deployment do Nginx Proxy Manager sem senhas importantes, por isso não há secrets. Também é perciso subir um mariadb antes para conectar o storage.

TODO: 
* Usar Vault
* Usar pv e pvc para storage
* Ativar o ingress para ativação do LetsEncrypt
* Realizar o teste de um Host Proxy no Nginx Proxy Manager com o n8n e verificar a possibilidade de uso dele como gerenciador de rotas do Back for Friend do PEP