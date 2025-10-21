# Case de Análise de Risco: Detecção de Fraude Transacional

Este repositório contém a resolução de um case prático focado na detecção de fraude em transações de cartão não presente (CNP).

O projeto envolveu duas frentes principais:
1.  **Análise de Dados Prática:** Análise de um dataset de transações para identificar comportamentos suspeitos e propor uma solução antifraude.
2.  **Conhecimento de Indústria:** Respostas a questões conceituais sobre o ecossistema de pagamentos.

---

## Dashboard Final (Power BI)

O principal entregável foi um dashboard interativo que resume os principais métricas e insights.

![Dashboard de Análise de Fraude](https://i.imgur.com/Naevykx.png)

---

## Principais Descobertas e Insights

A análise dos dados transacionais revelou padrões de compras suspeitos.

### 1. Descoberta dos dispositivos suspeitos
O insight mais impactante foi a detecção de uma ação concentrada.

* **17 dispositivos únicos** (menos de 1% do total) foram identificados com comportamento suspeito.
* Estes 17 dispositivos foram responsáveis por **120 chargebacks**.
* Isso significa que um pequeno grupo foi responsável por **30,69% de todo o prejuízo** por fraude no dataset.

### 2. A Solução Proposta
Com base nestes achados, a solução proposta não é apenas bloquear transações individuais, mas sim um **sistema de reputação de dispositivos** para identificar e bloquear esses dispositivos em tempo real.

---

## Ferramentas e Metodologia

* **Python (Pandas e Numpy):** Utilizado para a análise exploratória inicial, limpeza de dados e para a descoberta dos primeiros padrões.
* **Power BI (DAX e Power Query):** Ferramenta principal para a modelagem dos dados, criação das métricas de negócio (KPIs) e desenvolvimento do dashboard interativo.
