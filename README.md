# Image Processors API v2

Este repositório contém uma API para processamento de imagens (image-processors-api-v2) e uma aplicação frontend (image-processors-app) para interagir com a API. As instruções abaixo irão guiar você para configurar o ambiente, rodar a API e o frontend localmente.

## Pré-requisitos

Antes de começar, certifique-se de ter as seguintes ferramentas instaladas em seu sistema:

- [Java JDK 17+](https://www.oracle.com/java/technologies/javase-jdk17-downloads.html)
- [Maven](https://maven.apache.org/install.html)
- [Node.js](https://nodejs.org/en/download/) (v16+ recomendado)
- [Docker](https://www.docker.com/products/docker-desktop) (opcional, se for usar o docker-compose)

## Instruções para rodar a API

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/image-processors-api-v2.git
cd image-processors-api-v2
```

Abra o IntelliJ IDEA.
•	Selecione Open e navegue até a pasta image-processors-api-v2.
•	Localize e abra o arquivo ImageProcessorsApplication.java no caminho src/main/java/com/example/processors/ImageprocessorApplication.java.

3. Executar a API

	•	Com o arquivo ImageProcessorsApplication.java aberto, clique com o botão direito no arquivo e selecione Run ‘ImageProcessorsApplication’.
	•	A API será iniciada no endereço http://localhost:8080.

Você deverá ver logs no console do IntelliJ IDEA confirmando que o servidor foi iniciado com sucesso.

```bash
cd image-processors-app/my-app
npm install
npm run dev
```
	O frontend será iniciado em http://localhost:3000.

Acessando a aplicação

Com a API rodando em localhost:8080 e o frontend rodando em localhost:3000, você pode acessar o frontend no navegador via http://localhost:3000. Ele estará configurado para interagir com a API para realizar o processamento de imagens.

