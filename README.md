# 🚀 SWARM INVEST AI

### Plataforma Inteligente para Educação Financeira, Bitcoin, Criptomoedas e Investimentos de Longo Prazo

![Status](https://img.shields.io/badge/status-MVP-blue)
![Python](https://img.shields.io/badge/Python-3.9+-green)
![Node.js](https://img.shields.io/badge/Node.js-18+-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 📌 Visão Geral

**SWARM INVEST AI** é uma plataforma baseada em **Arquitetura de Agentes de IA (Swarm Intelligence)** desenvolvida para auxiliar pessoas a compreender e gerenciar investimentos em:

- 💰 Bitcoin e criptomoedas
- 📈 ETFs e fundos de índice
- 🏦 Reserva patrimonial
- 🎯 Planejamento de aposentadoria
- 📚 Educação financeira
- 📊 Estratégias de longo prazo

O objetivo é **transformar dados complexos do mercado financeiro em informações simples e acessíveis**, utilizando inteligência artificial cooperativa.

---

## 🎯 Objetivo Principal

Criar uma plataforma educacional com inteligência artificial capaz de:

✅ Monitorar mercado cripto 24h em tempo real

✅ Explicar investimentos de forma simples e didática

✅ Simular patrimônio de longo prazo

✅ Auxiliar na construção de reserva financeira

✅ Utilizar agentes IA cooperativos e autônomos

✅ Integrar múltiplas fontes financeiras externas

✅ Gerar recomendações personalizadas baseadas em perfil

---

## 🏗️ Arquitetura do Sistema

```
                    ┌──────────────────────┐
                    │ APP WEB / MOBILE     │
                    │ Painel do Investidor │
                    └─────────┬────────────┘
                              │
                              ▼
┌──────────────────────────────────────────────────────┐
│                API GATEWAY FINANCE                  │
│ REST + GraphQL + WebSocket + Eventos                │
└───────────────────┬──────────────────────────────────┘
                    │
 ┌──────────────────┼──────────────────┬──────────────────┐
 │                  │                  │                  │
 ▼                  ▼                  ▼                  ▼

AGENTE 1        AGENTE 2          AGENTE 3         AGENTE 4
Mercado BTC     ETFs/Fundos       Longo Prazo      Risco

Monitoramento   HASH11            DCA              Volatilidade
24h             BITH11            Buy&Hold         Drawdown
On-chain        ETFs globais      Aposentadoria    Alertas

 │                  │                  │                  │
 └──────────────────┴──────────────────┴──────────────────┘
                    │
                    ▼
        MOTOR SWARM DECISION ENGINE
        (coordenação entre agentes)
                    │
                    ▼
          DATA LAKE + HISTÓRICO
     PostgreSQL + Mongo + Redis
                    │
                    ▼
     APIs externas e dados financeiros
```

---

## 🤖 Agentes Inteligentes

### 1️⃣ BTC Guardian Agent

Responsável por monitoramento de Bitcoin:

- **Preço BTC** em tempo real
- **Halving** e ciclos de mercado
- **Dominância** de Bitcoin
- **Dados On-chain** (carteiras ativas, volume)
- **Volatilidade** e drawdown

**Exemplo de resposta:**

```json
{
  "btc_price": 108500,
  "market_cap": 2100000000000,
  "dominance": 58.4,
  "fear_greed": 72,
  "status": "acumular",
  "volatilidade": "moderada"
}
```

---

### 2️⃣ ETF Builder Agent

Objetivo: Explicar investimentos de longo prazo e diversificação

**Carteira Conservadora:**
- 70% ETFs globais
- 20% Renda fixa
- 10% Bitcoin

**Carteira Moderada:**
- 50% ETFs
- 30% Renda fixa
- 20% BTC

**Carteira Agressiva:**
- 40% ETFs
- 30% Ações tech
- 20% Bitcoin
- 10% Caixa

---

### 3️⃣ Reserve Agent

Planejamento financeiro e reserva patrimonial:

**Exemplo de Entrada:**
```
Idade: 40 anos
Investimento mensal: R$500
Horizonte: 20 anos
```

**Resultado Recomendado:**
```
ETF: R$300 (60%)
BTC: R$100 (20%)
Reserva: R$100 (20%)
```

**Projeção:** Patrimônio estimado em 20 anos

---

### 4️⃣ Education Agent

Modo iniciante para educação financeira:

**Pergunta:** "Tenho R$300 mensais para investir"

**Resposta:**
- R$200 → ETF (educação + segurança)
- R$50 → Bitcoin (aprendizado cripto)
- R$50 → Reserva (emergência)

---

## 📊 Estratégias Implementadas

### 💵 DCA — Dollar Cost Averaging

Compra recorrente, independente do preço:

```
Aporte: R$100 BTC todo mês
Benefícios:
✓ Reduz emoção
✓ Evita FOMO
✓ Ideal para longo prazo
✓ Histórico de sucesso
```

### 📈 Buy and Hold

Estratégia de acumulação de longo prazo:

```
1. Comprar
2. Guardar
3. Reinvestir dividendos
4. Manter horizonte de 10-20 anos
```

### 🎯 Diversificação Inteligente

| Perfil | Renda Fixa | ETFs | BTC | Outros |
|--------|-----------|------|-----|--------|
| Conservador | 50% | 30% | 10% | 10% Ouro |
| Moderado | 30% | 40% | 20% | 10% Ações |
| Agressivo | 10% | 50% | 30% | 10% Cash |

---

## 🧠 Swarm Decision Engine

Algoritmo de decisão coordenado entre agentes:

```python
score = (
    btc_agent * 0.30 +
    risk_agent * 0.20 +
    etf_agent * 0.25 +
    macro_agent * 0.25
)
```

**Resultado Final:**
```json
{
  "mercado": "neutro",
  "btc": "acumular",
  "risco": "baixo",
  "etf": "comprar",
  "recomendacao": "aporte mensal"
}
```

---

## 📡 Fontes de Dados

### APIs Financeiras
- 📊 **CoinGecko API** — Preços e dados cripto
- 📊 **CoinMarketCap** — Market cap e rankings
- 📊 **Binance API** — Dados de trading em tempo real
- ⛓️ **Blockchain.com** — Dados on-chain Bitcoin

### Educação Financeira
- 🏦 XP Investimentos
- 🏦 Toro Investimentos
- 📚 APIs de notícias financeiras

---

## 🛠️ Stack Tecnológica

### Frontend
```
✓ React 18+
✓ Next.js
✓ TailwindCSS
✓ Chart.js / D3.js
✓ Socket.io (WebSocket)
```

### Backend
```
✓ Python 3.9+
✓ FastAPI
✓ Node.js + Express
✓ GraphQL
✓ REST API
```

### Inteligência Artificial
```
✓ LangChain
✓ CrewAI
✓ AutoGen
✓ GPT Agents
✓ RAG Finance
```

### Banco de Dados
```
✓ PostgreSQL (Dados estruturados)
✓ MongoDB (Documentos)
✓ Redis (Cache + Real-time)
✓ TimescaleDB (Séries temporais)
```

### Mensageria e Eventos
```
✓ Apache Kafka
✓ RabbitMQ
✓ Redis Streams
```

### Cloud & DevOps
```
✓ Docker
✓ Kubernetes
✓ AWS (EC2, S3, Lambda)
✓ Azure (App Service, Cosmos DB)
```

---

## 📊 Dashboard - Módulos Principais

| Módulo | Descrição |
|--------|-----------|
| 💰 BTC Hoje | Preço, variação, gráficos 24h |
| 💼 Carteira | Resumo de investimentos |
| 🎯 Meta Aposentadoria | Simulação de patrimônio futuro |
| 🛡️ Reserva | Fundo de emergência |
| ⚠️ Risco | Análise de volatilidade |
| 🤖 IA Recomendação | Sugestões personalizadas |
| 📱 Simulador | Projections e backtesting |
| 📢 Alertas | Notificações em tempo real |

---

## 🗺️ Roadmap

### 📌 **Fase 1 - MVP** (Q1 2026)
- ✅ Dashboard BTC com gráficos
- ✅ Integração APIs de mercado
- ✅ Monitoramento 24h
- ✅ Sistema de alertas básico
- ✅ Educação ETF introductória

### 📌 **Fase 2 - Agentes IA** (Q2 2026)
- ✅ Implementação Swarm Engine
- ✅ 4 Agentes cooperativos
- ✅ Recomendações personalizadas
- ✅ Modelos de educação financeira
- ✅ RAG Finance integrado

### 📌 **Fase 3 - Dados On-Chain** (Q3 2026)
- ✅ Análise on-chain avançada
- ✅ Sentimento de mercado
- ✅ Backtesting de estratégias
- ✅ Machine Learning predictions
- ✅ Alertas inteligentes

### 📌 **Fase 4 - Plataforma Completa** (Q4 2026)
- ✅ Aplicativo mobile (iOS + Android)
- ✅ Assistente financeiro IA 24/7
- ✅ Planejamento de aposentadoria avançado
- ✅ Gestão de patrimônio familiar
- ✅ Integração bancária

---

## 📁 Estrutura do Repositório

```
SWARM-INVEST-AI/
│
├── README.md
├── LICENSE
├── .gitignore
├── requirements.txt
├── docker-compose.yml
│
├── docs/
│   ├── arquitetura/
│   │   ├── arquitetura-geral.md
│   │   ├── microservicos.md
│   │   ├── swarm-engine.md
│   │   └── fluxo-dados.md
│   ├── agentes/
│   │   ├── btc-agent.md
│   │   ├── etf-agent.md
│   │   ├── reserve-agent.md
│   │   └── education-agent.md
│   └── roadmap/
│       ├── mvp.md
│       ├── v1.md
│       └── backlog.md
│
├── backend/
│   ├── api/
│   │   ├── routes.py
│   │   └── websocket.py
│   ├── agents/
│   │   ├── btc_guardian.py
│   │   ├── etf_builder.py
│   │   ├── reserve_agent.py
│   │   └── education_agent.py
│   ├── services/
│   │   ├── market_service.py
│   │   ├── portfolio_service.py
│   │   └── recommendation_service.py
│   ├── pipelines/
│   │   └── data_ingestion.py
│   ├── scheduler/
│   │   └── tasks.py
│   └── tests/
│
├── frontend/
│   ├── pages/
│   ├── components/
│   ├── charts/
│   ├── hooks/
│   └── styles/
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── analytics/
│
├── infra/
│   ├── docker/
│   ├── kubernetes/
│   ├── terraform/
│   └── monitoring/
│
├── ml/
│   ├── prediction/
│   ├── sentiment/
│   ├── backtesting/
│   └── rag-finance/
│
├── notebooks/
│   └── exploration/
│
├── scripts/
│   └── setup.sh
│
└── CONTRIBUTING.md
```

---

## 💻 Começando

### Pré-requisitos
```bash
Python 3.9+
Node.js 18+
Docker & Docker Compose
PostgreSQL 13+
Redis 6+
```

### Instalação

**1. Clone o repositório:**
```bash
git clone https://github.com/Jonathanfonseca85/SWARM-INVEST-AI.git
cd SWARM-INVEST-AI
```

**2. Configure variáveis de ambiente:**
```bash
cp .env.example .env
# Edite .env com suas credenciais
```

**3. Inicie com Docker:**
```bash
docker-compose up -d
```

**4. Instale dependências backend:**
```bash
pip install -r requirements.txt
```

**5. Inicie o backend:**
```bash
python main.py
```

**6. Inicie o frontend:**
```bash
cd frontend
npm install
npm run dev
```

---

## 🧪 Testes

```bash
# Testes unitários
pytest tests/ -v

# Testes de integração
pytest tests/integration/ -v

# Cobertura
pytest --cov=.
```

---

## 📈 Diferencial Técnico

Este projeto demonstra expertise em:

### 🔧 **Arquitetura**
- Microserviços
- Event-Driven Architecture
- API Gateway Pattern
- WebSocket Real-time
- Mensageria distribuída

### 📊 **Engenharia de Dados**
- Pipeline ETL
- Streaming de dados
- Data Lake
- Analytics em tempo real
- Time series analysis

### 🤖 **Inteligência Artificial**
- Multi-Agent Systems
- Swarm Intelligence
- LLM Integration
- RAG (Retrieval Augmented Generation)
- Autonomous Agents

### 💰 **Mercado Financeiro**
- Bitcoin & Criptomoedas
- ETFs & Fundos
- DCA & Buy & Hold
- Análise técnica
- Risk Management

### ☁️ **Cloud & DevOps**
- Containerização Docker
- Orquestração Kubernetes
- Infrastructure as Code
- CI/CD Pipelines
- Monitoring & Observability

---

## ⚠️ Aviso Legal

**Este projeto possui finalidade:**

- 📚 **Educacional**
- 🔬 **Pesquisa e Desenvolvimento**
- ⚖️ **Apoio à decisão financeira**

**IMPORTANTE:**

❌ Não constitui recomendação financeira automática

❌ Criptomoedas possuem alta volatilidade e risco

❌ Sempre consulte um profissional antes de investir

✅ Use como ferramenta de apoio à educação financeira

✅ Faça sua própria análise antes de qualquer decisão

---

## 👨‍💻 Autor

**Jonathan Nascimento (Jo)**

- 🎓 Técnico em Equipamentos Biomédicos
- 📚 Estudante de Engenharia de Dados
- 🚀 Especialização futura: IA + Dados + Finanças + Agentes Inteligentes
- 🔗 GitHub: [@Jonathanfonseca85](https://github.com/Jonathanfonseca85)

---

## 📚 Documentação Adicional

- [Arquitetura Detalhada](docs/arquitetura/arquitetura-geral.md)
- [Guia dos Agentes](docs/agentes/README.md)
- [Roadmap Completo](docs/roadmap/README.md)
- [Contribuindo](CONTRIBUTING.md)

---

## 📄 Licença

Este projeto está licenciado sob a **MIT License** — veja o arquivo [LICENSE](LICENSE) para detalhes.

---

## 🌟 Apoie o Projeto

Se este projeto foi útil, considere dar uma ⭐ no GitHub!

---

## 📞 Suporte

Para dúvidas, sugestões ou relatar bugs:

- 📧 Email: [seu-email]
- 💬 Issues: [GitHub Issues](https://github.com/Jonathanfonseca85/SWARM-INVEST-AI/issues)
- 📝 Discussions: [GitHub Discussions](https://github.com/Jonathanfonseca85/SWARM-INVEST-AI/discussions)

---

**Desenvolvido com ❤️ para democratizar educação financeira através de IA**

*Última atualização: Maio 2026*
