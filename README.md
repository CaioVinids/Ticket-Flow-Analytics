# Dashboard Ticket-Flow-Analytics — Power BI

## Descrição do Projeto

Este projeto consiste no desenvolvimento de um dashboard analítico de chamados técnicos utilizando Power BI, com foco no monitoramento operacional, análise executiva e identificação de tendências temporais.

A solução foi construída utilizando modelagem dimensional (Star Schema), medidas DAX, dashboards interativos e um menu lateral customizado desenvolvido em HTML para melhorar a navegação entre páginas e proporcionar uma experiência de uso mais intuitiva.

---

# Objetivos da Análise

O projeto foi desenvolvido com os seguintes objetivos:

* Monitorar indicadores operacionais da central de chamados
* Avaliar conformidade de SLA
* Acompanhar tempo médio de resolução (MTTR)
* Identificar gargalos operacionais
* Avaliar produtividade técnica
* Identificar padrões temporais e sazonalidade operacional

---

# Perguntas de Negócio Respondidas

O dashboard permite responder perguntas como:

* O SLA está sendo atendido?
* Qual o volume atual de backlog?
* Quais técnicos possuem melhor desempenho?
* Quais períodos apresentam maior demanda?
* Como o MTTR evolui ao longo do tempo?
* Qual turno concentra maior volume operacional?
* Quais categorias apresentam maior volume de chamados?
* Como está distribuída a carga operacional da equipe?

---

# Principais Insights

Durante a análise foi possível identificar:

* Distribuição operacional por turnos
* Tendências temporais de resolução
* Concentração da demanda por períodos específicos
* Impacto do backlog operacional
* Diferenças de desempenho entre equipes e níveis técnicos
* Variações de SLA conforme prioridade
* Comportamento temporal da operação ao longo dos meses

---

# Ferramentas Utilizadas

* Power BI
* Power Query
* DAX
* Excel
* HTML (menu lateral personalizado)
* Modelagem Dimensional (Star Schema)

---

# Principais Indicadores

## KPIs Gerais

* Total de Chamados
* Chamados Resolvidos
* Chamados Abertos
* Chamados Em Atendimento
* Chamados Pendentes
* Chamados Cancelados
* Chamados Reabertos
* Backlog Operacional

## Indicadores Percentuais

* % Abertos
* % Cancelados
* % Resolvidos
* % Em Atendimento
* % Pendentes
* % Reabertos
* % Backlog
* % por Canal

## Indicadores de SLA e Performance

* % SLA
* Chamados Dentro SLA
* Chamados Fora SLA
* SLA Gap
* MTTR (Tempo Médio de Resolução)

---

# Análises Desenvolvidas

## Visão Geral

Apresenta indicadores consolidados e visão estratégica da operação.

Principais elementos:

* KPIs principais
* Indicadores consolidados
* Visão geral da operação

---

## Análise Executiva

Foco em indicadores estratégicos e desempenho geral da operação.

Principais análises:

* Tendência de SLA
* Conformidade SLA por prioridade
* Distribuição de chamados por status
* Indicadores estratégicos de performance

---

## Análise Operacional

Foco em produtividade, eficiência e distribuição operacional.

Principais análises:

* Produtividade por técnico
* Distribuição da carga operacional
* Desempenho técnico
* MTTR por senioridade

---

## Análise Temporal

Foco em comportamento temporal e sazonalidade.

Principais análises:

* Chamados por turno
* Chamados por dia da semana
* Evolução temporal do MTTR
* Comparativo entre dias úteis e finais de semana

---

# Estrutura do Projeto

```text
data/
│
├── base_chamados.xlsx
│

powerbi/
│
├── dashboard_chamados.pbix
│

docs/
│
├── documentacao_projeto.pdf
├── guia_usuario.pdf
│

README.md
```

---

# Contexto

Este projeto foi desenvolvido com foco em análise de dados aplicada à gestão de chamados técnicos, utilizando boas práticas de modelagem dimensional, documentação analítica e construção de dashboards interativos.

Além da construção analítica, também foram aplicados elementos de personalização visual, incluindo um menu lateral desenvolvido em HTML para melhorar a navegação e experiência do usuário.

O objetivo principal foi transformar dados operacionais em informações úteis para acompanhamento de desempenho e suporte à tomada de decisão.

---

# Preview do Dashboard



