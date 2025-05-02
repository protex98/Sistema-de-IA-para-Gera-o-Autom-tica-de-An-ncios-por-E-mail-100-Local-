# Anunciator AI - Gerador de Anúncios por E-mail

Sistema local de IA para criação e envio automático de campanhas de marketing por e-mail.

## Instalação
1. `pip install -r requirements.txt`
2. Configure o arquivo `.env`
3. Execute `python main.py`

## Recursos
- Geração de anúncios com IA local
- Envio por SMTP
- Banco de dados SQLite
- Modelos personalizáveis

- anunciator-ai/
├── .env.example
├── README.md
├── requirements.txt
├── main.py
├── config/
│   ├── __init__.py
│   ├── settings.py
│   └── email_templates/
│       ├── promotional.json
│       ├── informational.json
│       └── transactional.json
├── core/
│   ├── __init__.py
│   ├── ai_generator.py
│   ├── email_sender.py
│   ├── database.py
│   └── models/
│       ├── __init__.py
│       ├── product.py
│       ├── customer.py
│       └── campaign.py
├── data/
│   ├── database.db
│   ├── migrations/
│   └── assets/
│       ├── images/
│       └── documents/
├── utils/
│   ├── __init__.py
│   ├── logger.py
│   ├── validator.py
│   └── helpers.py
└── tests/
    ├── __init__.py
    ├── test_ai_generator.py
    ├── test_email_sender.py
    └── test_database.py
