# 📦 Projeto de Estudo: Redis, Bull & RabbitMQ

# CACHE - FILAS --MENSAGERIA

Este repositório reúne estudos e experimentações com **Redis**, **Bull** e **RabbitMQ**, demonstrando aplicações práticas como:

- 📌 **Cache** com Redis
- 🔄 **Filas** com Redis e Bull
- 📣 **Pub/Sub** com Redis
- 🐇 **Mensageria com RabbitMQ**

---

## 🚀 Tecnologias Utilizadas

- [Node.js](https://nodejs.org/)
- [Redis](https://redis.io/)
- [BullMQ](https://docs.bullmq.io/)
- [RabbitMQ](https://www.rabbitmq.com/)
- [Docker](https://www.docker.com/)
- [TypeScript](https://www.typescriptlang.org/)

---

## 📂 Estrutura dos Estudos

| Módulo                     | Descrição                                                                 |
|---------------------------|---------------------------------------------------------------------------|
| `redis/cache`             | Exemplo de uso de cache com Redis                                         |
| `redis/pub-sub`           | Demonstração de comunicação publisher/subscriber com Redis                |
| `redis/bull`              | Integração de Redis com Bull para filas                                   |
| `rabbitmq/producer`       | Produtor de mensagens com RabbitMQ                                        |
| `rabbitmq/consumer`       | Consumidor de mensagens com RabbitMQ                                      |

---

## 🧪 Executando o Projeto

### Pré-requisitos

- [Docker](https://docs.docker.com/get-docker/)
- [Node.js](https://nodejs.org/)
- Redis e RabbitMQ já estão configurados no `docker-compose.yml`

---

### 1️⃣ Clonar o repositório

git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio


2️⃣ Subir os serviços com Docker

docker-compose build
docker-compose up -d


3️⃣ Rodar a aplicação

npm install
npm run start:dev


✅ Funcionalidades Demonstradas
🔥 Cache automático de respostas com Redis

⏱️ Processamento assíncrono com Bull

📢 Eventos em tempo real com Pub/Sub do Redis

📬 Mensageria desacoplada com RabbitMQ

