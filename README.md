# Data Usage Tracker

Sistema de simulação de controle de consumo de dados móveis.

![Data Usage Tracker](https://img.shields.io/badge/In_Progress-10%25-yellow)
![Node.js](https://img.shields.io/badge/Redis-red)
![Node.js](https://img.shields.io/badge/RabbitMQ-orange)
![Docker](https://img.shields.io/badge/Docker_Compose-blue)

## Sobre

Data Usage Tracker é um sistema backend que recebe requisições via API, de consumo de dados móveis e registra no banco de dados esse consumo, tornando possível o controle de uma operadora ou do cliente sobre o uso. O sistema também é capaz de enviar notificações caso ultrapasse métricas como 50%, 80% ou 100% do plano de dados cadastrado.

## Em breve

O sistema ainda está sendo desenvolvido, logo haverão atualizações. Até o momento, o sistema conta com:
- arquitetura baseada em camadas (layered) com adaptações REST API (model, service, controller, repository)
- containers criados com docker compose: PostgreSQL, Redis e RabbitMQ
- entidade Cliente (para conter os dados de clientes e planos cadastrados com relação 1:1)
- infraestrutura geral preparada

## 👤 Autor

**Gabriel Paliato**

- GitHub: [@Weskal](https://github.com/Weskal)
- LinkedIn: [Gabriel Paliato](https://www.linkedin.com/in/gabriel-paliato-49467b211/)

---