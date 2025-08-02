<h1 align="center">
  Organização TrackPromo
</h1>

<p align="center">
  Uma plataforma colaborativa para rastreamento de promoções locais.
</p>

---

## 🎯 Sobre o Projeto

O **TrackPromo** é um projeto acadêmico desenvolvido para a disciplina de **Desenvolvimento de Software Integrado à Operação da Infraestrutura**.

Nosso objetivo é construir uma plataforma funcional onde usuários possam cadastrar e encontrar promoções no comércio local. O projeto é totalmente desenvolvido sobre uma arquitetura de microsserviços e utiliza um pipeline de CI/CD para automação, servindo como uma aplicação prática dos conceitos de DevOps.

### Nossos Objetivos
- **Conectar** pessoas a oportunidades de economia em sua cidade.
- **Fortalecer** o comércio local, dando mais visibilidade às suas ofertas.
- **Aplicar** na prática os conceitos de CI/CD, Docker, Kubernetes e Monitoramento.

---

## 🛠️ Stack de Tecnologias

Esta é a stack principal que estamos utilizando para construir o TrackPromo:

| Categoria | Tecnologia |
| :--- | :--- |
| **Frontend** | React, Vite, MUI (Material-UI), TanStack Query |
| **Backend** | NestJS, TypeScript |
| **Banco de Dados** | PostgreSQL (Dados Principais) e Redis (Cache/Sessões) |
| **Comunicação com BD**| TypeORM (ORM) |
| **Testes** | Jest & React Testing Library |
| **DevOps** | Docker, Kubernetes, GitHub Actions (CI/CD), Prometheus, Grafana |

---

## 📚 Nossos Repositórios

A arquitetura do TrackPromo é dividida nos seguintes microsserviços e componentes:

| Repositório | Descrição |
| :--- | :--- |
| 🔗 **[front](https://github.com/trackpromo/src-front-trackpromo)** | Frontend da aplicação construído com React, responsável pela interface do usuário. |
| 🔗 **[users](https://github.com/trackpromo/src-users-trackpromo)** | Microsserviço de **Usuários**, que gerencia cadastro, login e autenticação. |
| 🔗 **[promos](https://github.com/trackpromo/src-promo-trackpromo)** | Microsserviço de **Promoções**, responsável pela lógica de negócio principal do sistema. |
| 🔗 **[notifier](https://github.com/trackpromo/src-notifier-trackpromo)** | Microsserviço de **Notificações**, que envia alertas aos usuários sobre novas promoções. |
| 🔗 **[search](https://github.com/trackpromo/src-search-trackpromo)** | Microsserviço de **Busca**, otimizado para consultas complexas e filtragem de promoções. |

---

## 👨‍💻 Equipe

| Foto | Nome | GitHub |
| :--- | :--- | :--- |
| <img src="https://avatars.githubusercontent.com/u/54083776?v=4" width="50" style="border-radius: 50%"> | Caio Victor | [@CaioVFA](https://github.com/CaioVFA) |
| <img src="https://avatars.githubusercontent.com/u/95772104?v=4" width="50" style="border-radius: 50%"> | João Gabriel | [@jgluiggi](https://github.com/jgluiggi) |
| <img src="https://avatars.githubusercontent.com/u/129864914?v=4" width="50" style="border-radius: 50%"> | Nome do Colega | [@losout0](https://github.com/losout0) |
