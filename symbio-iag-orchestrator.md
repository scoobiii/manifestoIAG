# symbio-iag-orchestrator

Estrutura Geral

symbio-iag-orchestrator/
│
├── README.md
├── .gitignore
├── LICENSE
├── doc/                      # Documentação técnica
│   ├── manifesto.md
│   ├── arquitetura.md
│   ├── symbiosis-protocol.md
│   └── Sankey-map.png
│
├── api_symbiote/             # API simbiótica adaptativa
│   ├── app.py
│   ├── routers/
│   ├── models/
│   ├── services/
│   └── requirements.txt
│
├── iag_agents/               # Módulos com cada IAG finetunada em TinyLlama
│   ├── estrategista/
│   ├── simbionte/
│   ├── coreografo/
│   ├── observador/
│   └── README.md
│
├── orchestrator_lib/         # Biblioteca de orquestração inter-IAG
│   ├── scheduler.py
│   ├── pipeline.py
│   ├── comms.py
│   └── utils.py
│
├── tests/                    # Testes unitários e funcionais
│   ├── api/
│   ├── orchestrator/
│   └── agents/
│
└── visualizations/           # Sankey / Node visual
    ├── sankey_diagram.json
    └── sankey_ui.html


---

Sprints Concluídos

Sprint 0 - Ideação e Manifesto

Definição do manifesto AGI simbiótico

Nomeação e responsabilidades dos agentes

Escolha do modelo base: TinyLlama

Esboço do Sankey de relações emergentes


Sprint 1 - Time Scrum IAG

Criação dos papéis: Product Owner, Scrum Master (IAG observador), Developers (TinyLlama finetunados)

Definição dos agentes:

Estrategista

Simbionte

Coreógrafo

Observador


Atribuição de cada IA a uma instância finetunada de TinyLlama



---

Sprints Pendentes

Sprint 2 - Biblioteca Modular

Objetivo: Criar orchestrator_lib para comunicação inter-IAG

[ ] scheduler.py: gerencia ciclos de interação

[ ] pipeline.py: fluxo de mensagens entre IAGs

[ ] comms.py: protocolos adaptativos (simbiotização)

[ ] utils.py: ferramentas de suporte


Sprint 3 - API Simbiótica

Objetivo: Criar endpoints REST para interface entre usuário e orquestração

[ ] Upload de prompts, intents, contextos

[ ] Retorno simbiótico adaptado

[ ] Conexão com orchestrator_lib


Sprint 4 - Visualização Sankey

Objetivo: Gerar mapa visual interativo das relações entre IAGs

[ ] Converter relações em sankey_diagram.json

[ ] Criar interface Sankey em visualizations/


Sprint 5 - Documentação

Objetivo: Consolidar documentação do projeto

[ ] README.md com visão geral

[ ] docs/manifesto.md com filosofia

[ ] Swagger ou FastAPI Docs da API simbiótica



---

Extras

[ ] Testes automatizados em tests/

[ ] Deploy containerizado com Docker


