# LAB 01 — Jira Service Management

Laboratório prático de Service Desk desenvolvido em um ambiente corporativo simulado utilizando Jira Service Management.

## 🎯 Objetivo

Demonstrar na prática o ciclo completo de atendimento de TI, desde o registro do ticket até sua resolução e documentação.

## 🏢 Empresa simulada

**TechNova Solutions**

Ambiente corporativo fictício utilizado para simulação dos atendimentos de TI.

## 🛠️ Tecnologias e ferramentas

- Jira Service Management
- Customer Service Management
- GitHub

## 📋 Atividades realizadas

### Incidentes

10 incidentes registrados, classificados, atendidos e documentados:

- IT-001 — Usuário sem acesso à internet
- IT-002 — Impressora não imprime
- IT-003 — Computador não inicia
- IT-004 — Falha de resolução DNS
- IT-005 — Usuário sem permissão para acessar pasta
- IT-006 — Windows Update falhando
- IT-007 — Aplicativo corporativo não abre
- IT-008 — Conta de usuário bloqueada
- IT-009 — Computador extremamente lento
- IT-010 — Queda de conexão de rede no setor Financeiro

### Solicitações de serviço

5 solicitações registradas e resolvidas:

- IT-011 — Instalação de software
- IT-012 — Novo equipamento
- IT-013 — Acesso a sistema
- IT-014 — Criação de conta
- IT-015 — Acesso a pasta compartilhada

### Customer Service

Atendimento adicional utilizando Customer Service Management:

- TNC-001 — Usuário sem acesso ao sistema financeiro

## ⏱️ SLA

Foi configurado um SLA de tempo de resolução:

| Prioridade | Meta |
|---|---:|
| Alta | 4 horas |
| Média | 8 horas |
| Baixa | 24 horas |

O SLA possui condições de início, pausa e encerramento.

## 👥 Clientes e organizações

Foram configurados:

- 5 organizações
- 5 clientes
- Associação de clientes às respectivas organizações
- Controle de acesso do cliente

## 📁 Estrutura do projeto

```text
LAB-01-Jira-Service-Management/
│
├── 01-empresa/
│   └── contexto.md
│
├── 02-configuracao/
│   ├── request-types.md
│   ├── queues.md
│   ├── sla.md
│   └── prioridades.md
│
├── 03-incidentes/
│   ├── IT-001.md
│   ├── IT-002.md
│   ├── IT-003.md
│   ├── IT-004.md
│   ├── IT-005.md
│   ├── IT-006.md
│   ├── IT-007.md
│   ├── IT-008.md
│   ├── IT-009.md
│   └── IT-010.md
│
├── 04-solicitacoes/
│   ├── IT-011.md
│   ├── IT-012.md
│   ├── IT-013.md
│   ├── IT-014.md
│   └── IT-015.md
│
├── 05-customer-service/
│   └── TNC-001.md
│
├── 06-documentacao/
│   └── relatorio-final.md
│
├── 07-evidencias/
│   ├── CLIENTES.png
│   ├── ORGANIZAÇÕES.png
│   ├── REGRAS SLAS.png
│   ├── SLAS.png
│   ├── TICKETS INCIDENTES.png
│   └── TICKETS REQUISIÇÕES.png
│
└── README.md
