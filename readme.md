# Docker Image CI/CD with GitHub Actions

Este repositório demonstra como configurar uma pipeline de CI/CD usando GitHub Actions para construir e enviar uma imagem Docker para o Docker Hub.

## Estrutura do Projeto

- `Dockerfile`: Arquivo que contém as instruções para construir a imagem Docker.
- `.github/workflows/docker-image.yml`: Workflow do GitHub Actions que automatiza a construção e envio da imagem Docker para o Docker Hub.

## Pré-requisitos

1. **Conta no Docker Hub**: Crie uma conta gratuita em [Docker Hub](https://hub.docker.com/).
2. **Repositório no GitHub**: Este repositório onde você está lendo este README.
3. **Git instalado**: Certifique-se de ter o Git instalado em sua máquina.

## Configuração

### Passo 1: Clonar o Repositório

Clone este repositório para sua máquina local:

```bash
git clone https://github.com/usuario/nome-do-repositorio.git
cd nome-do-repositorio
