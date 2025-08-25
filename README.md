# DAM Systems – Projeto MES

Este repositório contém o código-fonte e a estrutura modular do sistema **MES (Manufacturing Execution System)** desenvolvido pela **DAM Systems Automação Industrial**. O projeto é composto por múltiplos módulos e serviços integrados que atendem às necessidades de controle, rastreabilidade e eficiência industrial.



## Dependências principais
- Laravel 10
- Breeze + Inertia.js + Vue
- DomPDF
- PhpSpreadsheet
- Bacon QRCode
---
## Ambiente de Desenvolvimento
"Ubuntu 22.04.5 LTS"

- Node.js: v18.18.2  
- NPM: v9.8.1
- Composer: 2.8.11
- PHP: 8.1.33

## Estrutura do Projeto

```bash
mes/
├── apps/                 # Aplicações front-end
│   └── web/              # Interface web (Vue.js, Tailwind, Inertia)
│
├── services/             # Módulos de backend (Laravel, REST, etc.)
│   └── pcm/              # PCM - Planejamento e Controle de Manutenção
│
├── shared/              # Recursos e bibliotecas compartilhadas
│   ├── libs/
│   ├── types/
│   └── config/
│
├── docs/                # Documentação técnica e arquitetural
├── docker/              # Dockerfiles e docker-compose
├── .env.example         # Modelo de variáveis de ambiente
├── .gitignore
└── README.md            # Este arquivo
