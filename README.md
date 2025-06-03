# TaskMaster
🧠 TaskMaster — Kanban App para Gerenciamento de Tarefas
TaskMaster é um aplicativo de produtividade estilo Kanban, onde usuários podem criar quadros, colunas e cartões de tarefas para organizar seu fluxo de trabalho de forma visual e intuitiva. O projeto é full-stack e foi desenvolvido com Flutter no front-end e Node.js (TypeScript) no back-end, com infraestrutura completa na AWS.

Este projeto foi pensado para simular um ambiente real de desenvolvimento ágil, utilizando CI/CD, testes automatizados, autenticação segura e arquitetura em nuvem escalável.

🚀 Funcionalidades principais
🔐 Autenticação e autorização com AWS Cognito + JWT

📋 CRUD de Boards, Colunas e Tarefas

🧪 Testes automatizados com Jest e Supertest

📝 Documentação de API com Swagger (OpenAPI)

📦 Upload e download de arquivos via AWS S3 (em versões futuras)

📧 Notificações por e-mail usando AWS Lambda + SES (em versões futuras)

📱 App responsivo em Flutter com integração HTTP + interceptors

🧱 Stack Tecnológica
Camada	Tecnologias	Aprendizados/Práticas
Mobile	Flutter + Dart	State management, integração com API, UI responsiva
API	Node.js + TypeScript + Express	Arquitetura REST, validação, autenticação, testes
Banco de Dados	PostgreSQL (via Sequelize ORM)	Modelagem relacional, migrations, relações entre tabelas
Autenticação	AWS Cognito + JWT	User pools, OAuth, segurança de rotas
Storage	AWS S3	Buckets, URLs pré-assinadas (em versões futuras)
Serverless	AWS Lambda + EventBridge + SES	Lembretes por e-mail agendados (em versões futuras)
Infraestrutura	Docker, GitHub Actions, Beanstalk	CI/CD, containerização, deploy automatizado
Documentação	Swagger (OpenAPI)	APIs testáveis via Swagger UI

