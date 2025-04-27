# Aplicação do docker para microserviços

Este projeto implementa uma simples estrutura de microserviço usando Docker e Docker e Docker compose. 


## Explicação Rápida dos arquivos e pastas

> service-api:

É a pasta que contem um serviço Flask que expõe uma API REST. Trata-se de um serviço de uma API REST feita em Flask. 

> service-web: 

É a pasta que contem um serviço Web estático o qual utilizar Nginx como base. 

> docker-compose.yml: 

Arquivo do Docker para a orquestração responsável por rodar ambos os serviços juntos. 

> README.md: 

Arquivo de texto utilizado para a orientação do projeto.

## Como executar

1. Clone este repositório 
2. Entre na pasta deste projeto 
3. Rode: 

```bash 
docker-compose up --build

4. Acesse os serviços de forma local pelos seguintes endereços

- API: http://localhost:5000/
- Web: http://localhost:8080/
