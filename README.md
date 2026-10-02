# Laboratório de Arquitetura — Node.js

Repositório de estudo prático de sistemas distribuídos, segurança,
infraestrutura e arquitetura de software. Cada cenário segue o ciclo:
Hipótese → Baseline → Falha induzida → Mitigação → Telemetria.

## Progresso

| Fase | Foco                          | Status |
| ---- | ----------------------------- | ------ |
| 0    | Ambiente e método             | ⏳     |
| 1    | Segurança + Node.js internals | ⏳     |
| 2    | Fundamentos distribuídos      | ⏳     |
| 3    | Resiliência e observabilidade | ⏳     |
| 4    | Arquitetura de software       | ⏳     |
| 5    | Escala e hiperescala          | ⏳     |
| 6    | Staff Engineer                | ⏳     |

## Stack do laboratório

- Node.js 20+
- PostgreSQL 16
- Redis 7
- Kafka 3
- Docker + Docker Compose
- Kubernetes (k3s local / minikube)
- Prometheus + Grafana + OpenTelemetry

## Como rodar qualquer cenário

```bash
cd fase-X-nome/X.Y-nome-do-cenario
docker-compose up -d
# Siga o README.md do cenário
```

## Diário de aprendizado

→ [DIARIO.md](./DIARIO.md)
