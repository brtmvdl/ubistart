# Desafio Ubistart

Desafio Fullstack para a vaga da [UBISTART](https://www.ubistart.com/)

[Front-end](https://github.com/brtmvdl/ubistart-frontend-challenge)

[Back-end](https://github.com/brtmvdl/ubistart-backend-challenge)

## Tecnologias

[React.js](https://reactjs.org/)

[Node.js](https://nodejs.org/en/)

[Docker](https://www.docker.com/)

[Swagger](https://swagger.io/)

## Estórias

[x] Cadastro da usuário (com e-mail e senha)

[x] Entrada (com e-mail e senha)

[x] CRUD de tarefas

[x] CRUD de tarefas (admin)

## Para configurar na [AWS Lightsail](https://aws.amazon.com/pt/lightsail/)

* A porta 3000 da maquina precisa estar disponível para a internet.

```sh
# Installing Docker and others
apt update -y
apt install -y docker-compose git nano
systemctl enable docker

# Downloading project files
git clone https://github.com/brtmvdl/ubistart-challenge
cd ubistart-challenge/
git clone https://github.com/brtmvdl/ubistart-backend-challenge
git clone https://github.com/brtmvdl/ubistart-frontend-challenge

# Setting up the project
sh ./env/production/up.sh 
```

## License

[MIT](./LICENSE)
