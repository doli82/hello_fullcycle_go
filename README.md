<p align="center" style="background: #272727">
    <img alt="NextLevelWeek" title="#MaratonaFullCycle3.0" src="https://user-images.githubusercontent.com/39415174/86166659-85050100-baeb-11ea-9b1f-4474b76fae1a.png" />
</p>
<p align="center">
    <img alt="Repository size" src="https://img.shields.io/github/repo-size/doli82/hello_fullcycle_go?style=plastic" />
    <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/doli82/hello_fullcycle_go?color=brightgreen&style=plastic" />    
  <a href="https://www.linkedin.com/in/doli/">
    <img alt="Made by Daniel Oliveira" src="https://img.shields.io/badge/made%20by-doli82-important?style=plastic">
  </a>
  <a href="https://github.com/doli82/hello_fullcycle_go/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/DanielObara/NLW-1.0?style=plastic">
  </a>
  <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen?style=plastic">
</p>

# Maratona Full Cycle 3.0

A Maratona Full Cycle 3.0, realizada pela [School Of Net](https://www.schoolofnet.com/) e [Code Education](https://code.education/), propõe apresentar os desafios do processo de desenvolvimento de aplicações desde a arquitetura até o deploy e o monitoramento.

O estudo de caso desta maratona, é uma plataforma SASS de e-commerce baseada em micro serviços, que engloba o estudo de mensageria com `RabbitMQ` e o modelo multitenancy. Os microserviços usarão os frameworks `Buffalo (GoLang)`, `Nest.js (Typescript)` e `Django (Python)` e também aplicações `Serveless`.

[Informações do Desafio](#informações-do-desafio)&nbsp;&nbsp;|&nbsp;&nbsp;
[DockerHub](#dockerhub)&nbsp;&nbsp;|&nbsp;&nbsp;
[Começando](#começando)&nbsp;&nbsp;|&nbsp;&nbsp;
[Tecnologias](#tecnologias)&nbsp;&nbsp;|&nbsp;&nbsp;
[Licença](#licença)  

#  Desafio 1  

## Informações do desafio

O primeiro desafio dessa maratona consiste em criar um "Hello Full Cycle" utilizando a linguagem Golang.
Basicamente quando o arquivo compilado for executado, deverá ser exibido: Hello Full Cycle.
Se tudo estiver funcionando de forma adequada, gere uma imagem docker que quando executada deva rodar o programa criado em Golang.

Faça o push da imagem no Docker Hub e informe a url da imagem na área de entrega do desafio abaixo.

## DockerHub

Este repositório corresponde ao primeiro desafio apresentado na maratona, cujo resultado foi convertido em imagem docker e está presente no [Docker Hub](https://hub.docker.com/r/doli82/hello_fullcycle_go), e pode ser baixada caso precise, com o seguinte comando:

```
docker pull doli82/hello_fullcycle_go
```

## Começando
Este repositório pode ser usado para desenvolvimento de aplicações em `GoLang` com `Docker`.
Para usar, primeiro clone o repositório:
```
git clone https://github.com/doli82/hello_fullcycle_go.git
cd hello_fullcycle_go
```

Edite o arquivo `src\main.go` e em seguida execute o container docker com o docker-composer, como é mostrado abaixo. Na primeira execução pode demorar um pouco porque a imagem docker ainda não estará contruída.

```
docker-composer up
```

Para finalizar o container criado com p docker composer, use o comando:

```
docker-composer down
```

## Tecnologias
* [Docker](https://www.docker.com/) - Usado para empacotar o código e todas as suas dependências para que o aplicativo seja executado de maneira rápida e confiável de um ambiente de computação para outro.
* [Docker Compose](https://docs.docker.com/compose/) - Usado para configurar um arquivo YAML para os serviços da aplicação
* [GoLang](https://golang.org/) - Linguagem usada como base para o desenvolvimento

## Licença

Este projeto foi desenvovido sob a licença MIT. Veja o [LICENSE](./LICENSE) para detalhes.


Feito com ♥ por [Daniel Oliveira](https://www.linkedin.com/in/doli/)