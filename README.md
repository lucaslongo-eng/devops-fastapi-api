# DevOps FastAPI API

REST API desenvolvida com foco em arquitetura limpa, containerização e integração contínua, aplicando práticas modernas de DevOps desde a concepção até o deploy.

Este projeto demonstra a construção de uma API pronta para produção utilizando **FastAPI, PostgreSQL, Docker e CI/CD com GitHub Actions**, com foco em organização, automação e escalabilidade.

---

## Objetivo do Projeto

Construir uma API REST seguindo boas práticas de:

- Arquitetura backend moderna
- Separação de responsabilidades
- Containerização com Docker
- Integração contínua (CI)
- Versionamento estratégico com Git
- Estrutura organizada de branches e Pull Requests
- Mentalidade DevOps aplicada desde o início

---

## Stack Utilizada

### Back-end
- Python
- FastAPI
- SQLAlchemy
- Pydantic

### Banco de Dados
- PostgreSQL

### DevOps & Infra
- Docker
- Docker Compose
- GitHub Actions (CI/CD)

### Versionamento
- Git
- GitHub (Issues, Projects, Pull Requests, Branch Strategy)

---

## Arquitetura

A aplicação foi estruturada com:

- Separação por camadas (routers, services, models, schemas)
- Injeção de dependências
- Validação de dados com Pydantic
- Conexão desacoplada com banco de dados
- Estrutura preparada para escalabilidade

---

## CI/CD

Pipeline automatizada com GitHub Actions contendo:

- Instalação de dependências
- Lint
- Testes automatizados
- Build da imagem Docker
- Verificação de integridade da aplicação

Cada Pull Request passa obrigatoriamente pelo pipeline antes de merge na branch principal.

---

## Estratégia de Branches

- `main` → versão estável
- `develop` → integração de features
- `feature/*` → novas funcionalidades
- `hotfix/*` → correções emergenciais

Fluxo baseado em Git Flow simplificado.

---

## Execução Local (Ambiente Containerizado)

A aplicação pode ser executada integralmente via Docker Compose, garantindo:

- Ambiente isolado
- Reprodutibilidade
- Configuração padronizada

---

## Conceitos Aplicados

- Clean Architecture (conceitos)
- API RESTful
- Containerização
- Continuous Integration
- Organização de backlog com GitHub Projects
- Controle de versionamento estruturado

---

## Motivação

Este projeto foi desenvolvido com o objetivo de consolidar conhecimentos em DevOps, arquitetura backend e automação, simulando um ambiente próximo ao cenário real de produção.

A proposta foi ir além de apenas “criar uma API”, estruturando o projeto como se estivesse inserido em um fluxo profissional de engenharia.

---------

## Status

Projeto concluído como laboratório prático de aplicação de práticas DevOps em backend.
