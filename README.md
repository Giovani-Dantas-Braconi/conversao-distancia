
# 🚀 Conversão de Distâncias - Desafio "DevOps & Cloud"

  

Projeto desenvolvido como parte do desafio **DevOps & Cloud** do curso online.

A proposta foi criar um ambiente containerizado para uma aplicação de conversão de distâncias, utilizando **Docker**.

  

---

  

## 📝 Descrição do Desafio

  

O desafio foi dividido em três partes:

  

### 1. Configuração do Ambiente

- Fazer o fork do repositório original e clonar a aplicação **Conversão de Distâncias**.

- Criar um **Dockerfile** para a aplicação.

  

### 2. Criação e Teste do Contêiner

- Gerar uma imagem Docker a partir do Dockerfile.

- Executar o contêiner na porta **5000**.

- Testar a funcionalidade da conversão de métricas.

  

### 3. Entrega

- Publicar o código no repositório forkado.

- Criar um arquivo `dockerhub.md` com o link da imagem no Docker Hub.

  

---

  

## 🛠️ Tecnologias Utilizadas

  

-  **Python 3**

-  **Flask**

-  **Docker**

  

---

  

## 🔗 Links Importantes

  

- 📂 Repositório GitHub: [Conversão de Distâncias](https://github.com/Giovani-Dantas-Braconi/conversao-distancia)

- 🐳 Docker Hub: [giovanidbraconi/conversor-medidas](https://hub.docker.com/r/giovanidbraconi/conversor-medidas)

  

---

  

## ▶️ Como Executar a Aplicação via Docker

  

### Pré-requisitos

- Docker instalado na máquina.

  

### Passos para rodar o contêiner

1.  **Puxar a imagem diretamente do Docker Hub:**

```bash

docker pull giovanidbraconi/conversor-medidas
```
2. **Rodar a imagem dentro de um container**
```bash
docker container -d -p 5000:5000 giovanidbraconi/conversor-medidas:latest(#ou 01)
```

3. **Após isso já é possível acessar a porta 5000 para ver a aplicação funcionando**
```bash
localhost:5000
```

4.**Para cancelar a execução, como evitamos de o docker matar 1 cmd utilizamos o -d e isso "impossibilita" de matar a aplicação**
* Para fazer isso é muito simples
```bash
docker rm -f giovanidbraconi/conversor-medidas
```

#
## Esse projetinho é um exemplo de como rodar docker, entender sobre imagens, sobre os containers, como eles funcionam  