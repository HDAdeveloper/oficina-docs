# Oficina Tech Service: documentação

Tech Challenge Fase 4, Pós-Tech SOAT turma 15 (FIAP). Autor: Henrique Dellagnesi Azevedo, RM372407.

Este repositório reúne **apenas a documentação**. O código está em um repositório por serviço.

| O que | Onde |
|---|---|
| Vídeo de demonstração (não listado) | https://youtu.be/S43pJ9iFAKM |
| Relatório de entrega (PDF) | [relatorio-entrega.pdf](relatorio-entrega.pdf) |
| OS Service (PostgreSQL) | https://github.com/HDAdeveloper/oficina-os-service |
| Billing Service (PostgreSQL) | https://github.com/HDAdeveloper/oficina-billing-service |
| Execution Service (DynamoDB) | https://github.com/HDAdeveloper/oficina-execution-service |
| Autenticação por CPF (Lambda) | https://github.com/HDAdeveloper/oficina-auth-lambda |
| Infraestrutura (Terraform) | https://github.com/HDAdeveloper/oficina-infra |

## Por onde começar

- [**Como subir o ambiente**](docs/como-subir-o-ambiente.md): passo a passo com LocalStack e na AWS.
- [**Contratos das APIs**](docs/contratos/): OpenAPI e coleções Postman de todos os serviços.
- [Arquitetura](docs/arquitetura.md): visão geral, serviços, mensageria e diagramas.
- [Decisões de arquitetura (ADRs)](docs/adr/): uma decisão por arquivo, com contexto e consequências.
- [Eventos e comandos](docs/eventos.md): contrato das mensagens e a Saga passo a passo.
- [DDD](docs/ddd.md) e [Event Storming](docs/event-storming.md): contextos, agregados e fluxos, com [diagramas](docs/diagramas/).
- [Cobertura de testes](docs/cobertura.md): como medir e os números por serviço.
- [Mercado Pago](docs/mercado-pago.md): pagamento por link, webhook e como ligar o provedor real.
- [Observabilidade](docs/observabilidade/): New Relic.
- [Evidências](docs/evidencias/): execuções reais na AWS e com o Mercado Pago.
- [Roteiro de deploy](docs/roteiro-deploy.md).