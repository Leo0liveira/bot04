# 🟢 Avaliação Sprint 4 - Programa de Bolsas Compass.uol e UFMS 🟢 

Quarta sprint do programa de bolsas Compass.uol para formação em chatbot Rasa.

---

## 🤖 ChatBot 
O chatbot construído tem como objetivo criar uma conversa com o usuário onde ele pode realizar uma consulta com base na [API](https://openweathermap.org/current) para visualizar a temperatura de uma determinada cidade no planeta, agora com o banco de dados funcional, é possível armazenar as  buscas que o usuário faz durante sua conversa com o bot.

---

# 🔨 Desenvolvimento
## 📚 Bibliotecas utilizadas 
* [Action](https://rasa.com/docs/rasa/actions/)
* [Tracker](https://rasa.com/docs/action-server/sdk-tracker/)
* [SlotSet](https://rasa.com/docs/action-server/sdk-events/)
* [CollectingDispatcher](https://rasa.com/docs/action-server/sdk-dispatcher/)
* [PyMongo](https://pymongo.readthedocs.io/en/stable/)
* [MongoClient](https://mongodb.github.io/node-mongodb-native/api-generated/mongoclient.html)
* [Docker](https://docs.docker.com/)
* [Kubernetes por meio do Okteto](https://kubernetes.io/docs/home/)
  
---

## Dependências
* Rasa
* Python
* Pymongo
* MongoDB
* Docker
* Kubernetes

---

## 🤖 Utilizando o Rasa ChatBot com MongoDB

1. Faça a clonagem deste repositório em sua máquina.
   
2. No seu terminal de preferência, execute os comandos abaixo:
   
```
rasa train

rasa run actions

rasa shell
```
Com a aplicação rodando, siga o seguinte fluxo:

* Dê os cumprimentos ao chatbot
* Informe sua intensão
* Informe seu nome
* Informe a cidade que deseja conferir a temperatura

O nome e a cidade buscada pela usuário ficam guardados em um banco de dados, junto com os resultados da pesquisa pela cidade.
---

## 🐳 Docker

A partir de agora bastará ao usuário digitar o seguinte comando no terminal da aplicação "docker-compose run -u " root" rasa" no console de preferência e a aplicação estará funcional, sem o uso dos outros comandos.

---

## ⚓Kubernetes & Okteto

Graças ao desenvolvimento do arquivo docker-compose, foi possível realizar o deploy e acessar a aplicação na plataforma Okteto, [clicando aqui](https://).

## Desenvolvido por 
- 👨‍💻 Leonardo Oliveira
---