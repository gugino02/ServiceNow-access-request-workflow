# 🔐 Portal de Acessos — ServiceNow

Projeto prático desenvolvido na plataforma ServiceNow com foco em automação de processos, gestão de aprovações e controle de acesso corporativo.

---

## 📋 Sobre o Projeto

Este projeto simula um ambiente corporativo real onde colaboradores podem solicitar acesso a setores ou sistemas diretamente pelo Service Catalog. O processo passa por um fluxo de aprovação multinível com notificações automáticas, SLA e geração de tarefas para a equipe de TI.

---

## ⚙️ O que foi configurado

- **Catalog Item** — formulário de solicitação com variáveis e auto-preenchimento via Client Script
- **Flow Designer** — fluxo de aprovação multinível (Gestor → TI) com lógica de urgência
- **Notificações** — 4 e-mails automáticos disparados em cada etapa do processo
- **SLA** — prazo normal de 2 dias úteis e prazo urgente de 4 horas
- **Catalog Task** — tarefa criada automaticamente para execução pela equipe de TI
- **ACL** — 3 regras de controle de acesso na tabela sc_req_item
- **Assignment Rules** — atribuição automática de tarefas ao grupo IT Securities

---

## 🔄 Fluxo do Processo
---

## 📸 Screenshots

### Formulário de Solicitação
![Formulário](screenshots/01-formulario.png)

### Catalog Item — Configuração
![Catalog Item](screenshots/02-catalog-item.png)

### Flow Designer — Visão Geral
![Flow Designer](screenshots/03-flow-designer.png)

### Catalog Task criada e vinculada
![Catalog Task](screenshots/04-catalog-task.png)

### Aprovadores — Fluxo Multinível
![Approvers](screenshots/05-approvers.png)

### SLA Definitions
![SLA](screenshots/06-sla-definitions.png)

### Access Control List
![ACL](screenshots/07-acl.png)

---

## 🛠️ Tecnologias e Recursos Utilizados

- ServiceNow (PDI — Personal Developer Instance)
- Flow Designer
- Service Catalog
- SLA Management
- Access Control (ACL)
- Email Notifications
- Catalog Tasks

---

## 👨‍💻 Sobre

Projeto desenvolvido como parte do meu portfólio prático em ServiceNow, com foco em ITSM, automação de processos e soluções corporativas.

> Aberto a oportunidades júnior na área de ServiceNow e automação de processos.