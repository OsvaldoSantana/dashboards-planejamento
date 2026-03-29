# Dashboards de Planejamento e Controle

Documentação da lógica, estrutura de dados e indicadores utilizados em dashboards de planejamento e controle de obras.

## Contexto

Dashboards de obra só funcionam quando o modelo de dados é bem estruturado e os indicadores são relevantes para quem toma decisão. Este repositório documenta a lógica por trás dos painéis, não apenas o visual.

## Dashboards documentados

### Dashboard 1 — Acompanhamento Físico-Financeiro
- **Indicadores:** % executado vs % previsto, curva S, desvio acumulado
- **Fontes de dados:** cronograma (MS Project), medições (SIENGE/Excel), orçamento
- **Atualização:** semanal
- **Público-alvo:** coordenação de obras e diretoria

### Dashboard 2 — Produtividade e Equipes
- **Indicadores:** produtividade por equipe (m²/dia, m³/dia), histograma de mão de obra
- **Fontes de dados:** apontamentos de campo, controle de efetivo
- **Atualização:** diária
- **Público-alvo:** engenheiro de campo e planejamento

### Dashboard 3 — Controle de Medições
- **Indicadores:** medições por contrato, valores acumulados, projeção de desembolso
- **Fontes de dados:** planilhas de medição, contratos
- **Atualização:** mensal (pós-medição)
- **Público-alvo:** gerência e financeiro

## Modelo de dados

Cada dashboard segue a estrutura:
