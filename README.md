## Criação de container docker para deploy

#### Detalhes do projeto
Aplicação nodejs utilizando o express com uma simples rota na porta 3000

#### Rodar em ambiente dev
```bash
# Entre na pasta do projeto
cd nodejs-deploy

# Rode o comando up para subir a aplicação
docker-compose up

# Abra outro terminal e rode o comando
docker ps

# Vá para o navegador http://localhost:3000/
# Uma lista de containers será exibida, assim você pode verificar se o container está rodando
# Para finalizar o container basta utilizar o comando CTRL + C no terminal que foi executado o docker-compose
```

#### Próximos passos
- Estudar docker-machine para deploy
- Estudar traefik para redirecionamento de portas