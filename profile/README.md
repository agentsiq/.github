# AgentsIQ — Multi-Domain AI Platform

AgentsIQ builds intelligent AI agents for infrastructure and operations teams. Each agent is a standalone plugin that connects to your existing tools and answers natural language questions about your data.

## Available Agents

| Agent | Description | Version | Status |
|-------|-------------|---------|--------|
| [CUR Analyser](https://github.com/agentsiq/cur-analyser) | AWS Cost & Usage Report intelligence | v1.1.0 | ✅ Available |
| [Alert Analyser](https://github.com/agentsiq/alert-analyser) | OpsGenie/JSM noise detection & suppression | v1.1.0 | ✅ Available |
| [Kafka Analyser](https://github.com/agentsiq/kafka-analyser) | Kafka cluster health monitoring, consumer lag detection & broker intelligence | v1.0.0 | ✅ Available |

## Getting Started

Clone any agent and follow its README — two env vars, docker compose up, done.

```bash
git clone https://github.com/agentsiq/cur-analyser.git
cd cur-analyser
cp .env.example .env
# fill in DATABASE_URL and ENCRYPTION_KEY
docker compose up
```

## Platform

Try the live demo at **[studio.agentsiq.net](https://studio.agentsiq.net)**

## Built by
Karthikeyan G · [studio.agentsiq.net](https://studio.agentsiq.net)
