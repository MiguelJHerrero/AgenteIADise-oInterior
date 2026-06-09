Creación de un agente de IA que cuando se le pase un plano o imagen con las medidas, la construya y ayude a decorarlo en función de la habitación

nexus-agent/
│
├── main.py                  # Orquestador principal de FastAPI
├── api/
│   └── routes.py            # Endpoints de comunicación
├── agents/
│   └── vision_agent.py      # Lógica del LLM para analizar el plano
├── scrapers/
│   └── extract_furniture.py # Scripts de Playwright para tiendas
└── requirements.txt
