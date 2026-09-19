# Projeto DevOps e Computação em Nuvem — N1

Projeto desenvolvido para a disciplina **DevOps e Computação em Nuvem**, com o objetivo de aplicar, na prática, conceitos e ferramentas relacionados ao desenvolvimento, versionamento, containerização, implantação e operação de uma aplicação web em ambiente de nuvem.

##  Objetivo

Construir e disponibilizar uma aplicação web funcional, utilizando práticas e ferramentas de DevOps desde o desenvolvimento até a disponibilização em produção.

O projeto contempla o fluxo:

**Código → Git → Docker → Cloud → DNS → HTTPS → CI/CD → Monitoramento**

A aplicação deverá ser disponibilizada publicamente e possuir uma infraestrutura capaz de demonstrar o processo de entrega de uma aplicação desde o código-fonte até o ambiente de produção.

##  Tecnologias e ferramentas

Durante o desenvolvimento do projeto serão utilizadas tecnologias e ferramentas como:

* HTML, CSS e JavaScript;
* Git e GitHub;
* Docker e Docker Compose;
* Servidor em ambiente Cloud;
* Linux;
* Nginx;
* DNS;
* SSL/TLS e HTTPS;
* GitHub Actions para CI/CD;
* Uptime Kuma para monitoramento.

##  Infraestrutura

A aplicação será executada em um ambiente de nuvem utilizando uma arquitetura baseada em:

```text
Usuário
   ↓
Domínio
   ↓
DNS
   ↓
Servidor Cloud
   ↓
Nginx + HTTPS
   ↓
Docker
   ↓
Container
   ↓
Aplicação Web
```

##  CI/CD

O projeto contará com uma pipeline de integração e entrega contínua, responsável por automatizar etapas do processo de publicação da aplicação.

Fluxo previsto:

```text
Git Push
   ↓
GitHub Actions
   ↓
Build
   ↓
Validação/Testes
   ↓
Build da imagem Docker
   ↓
Deploy
   ↓
Ambiente de produção
```

##  Monitoramento

Será utilizado um mecanismo de monitoramento para verificar a disponibilidade da aplicação e auxiliar na identificação de possíveis indisponibilidades do ambiente.

##  Segurança

O projeto adotará configurações básicas de segurança, incluindo:

* HTTPS;
* proteção das credenciais e segredos;
* não armazenamento de senhas diretamente no código;
* exposição apenas das portas necessárias;
* configuração de firewall quando aplicável;
* utilização de autenticação adequada para acesso ao servidor.

## 📚 Documentação

A documentação será desenvolvida ao longo do projeto e apresentará:

1. Descrição da aplicação;
2. Arquitetura do ambiente;
3. Tecnologias utilizadas;
4. Estrutura do projeto;
5. Processo de instalação;
6. Processo de deploy;
7. Configuração do Docker;
8. Configuração do DNS;
9. Configuração do HTTPS;
10. Processo de CI/CD;
11. Monitoramento;
12. Procedimentos básicos de recuperação.

##  Integrantes

* **Antonio Lucas**
* **Matheus Talon**

##  Disciplina

**DevOps e Computação em Nuvem**

**Atividade:** N1 — Construção do Projeto

**Instituição:** Centro Universitário São Lucas — Afya São Lucas
