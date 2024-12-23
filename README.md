# 📊 Análise do Fluxo de Passageiros no Aeroporto

Este projeto foi desenvolvido durante o curso "**Profissão: Analista de Dados**" na **EBAC** (Escola Britânica de Artes Criativas) com o auxílio do meu professor **André Perez**.
O objetivo foi analisar o fluxo mensal de passageiros utilizando o dataset **"flights"**, para apoiar a equipe de operações de um grande aeroporto na tomada de decisões relacionadas à manutenção, obras e otimização de processos. A análise e visualização dos dados foram realizadas com o objetivo de identificar tendências sazonais e picos de demanda.

---
## Descrição do Projeto

Como analista de dados de um grande aeroporto, propus a criação de um **dashboard interativo** para monitorar o fluxo de passageiros mensalmente. O time de operações pode usar o dashboard para:
- Identificar tendências e picos de demanda de passageiros.
- Planejar recursos e realizar manutenções de forma mais eficiente.
- Otimizar as operações do aeroporto, como o agendamento de voos e a alocação de gate.

---
### Metodologia

1. **Carregamento e Pré-processamento dos Dados**:  
   O dataset utilizado é o **"flights"** disponível no Seaborn. Ele contém dados mensais sobre o número de passageiros de voos de 1949 a 1960.

2. **Análise Exploratória de Dados (EDA)**:  
   - Identificação da granularidade temporal dos dados: mensal.
   - Identificação de padrões sazonais e picos de passageiros ao longo dos anos.

3. **Visualização no Looker Studio**:  
   A construção de um dashboard foi realizada no **Looker Studio** para facilitar a análise dos dados pelos membros da equipe de operações.

---
## Dados

- **Fonte**: Dataset **"flights"** (Seaborn).
- **Granularidade Temporal**: Mensal.
- **Intervalo de Tempo**: De Janeiro de 1949 até Dezembro de 1960.
- **Descrição do Dataset**: O dataset contém o número de passageiros em voos mensais ao longo de vários anos.

### Exemplo de Dados:

| Ano  | Mês  | Passageiros |
|------|------|-------------|
| 1949 | Jan  | 112         |
| 1949 | Feb  | 118         |
| 1949 | Mar  | 132         |
| ...  | ...  | ...         |
| 1960 | Dec  | 378         |

---
## Dashboard

[Link para o Dashboard no Looker Studio](https://lookerstudio.google.com/reporting/61af7c1b-eb40-465e-bf5d-7509797eae02)

Para a visualização dos dados, utilizei o **Google Data Studio** (agora conhecido como **Looker Studio**) para criar um dashboard interativo que facilita a análise do fluxo de passageiros ao longo do tempo. O processo de criação do dashboard foi dividido em duas etapas principais:

### **1.1. Fonte de Dados**

A fonte de dados foi criada através do **upload** do arquivo [`flights.csv`](https://github.com/Bezemon/flights_report_dashboard/blob/main/flights.csv). A partir dessa fonte, foi possível construir as visualizações e realizar análises detalhadas.

### **1.2. Relatório**

O relatório interativo, intitulado **"flights-report"**, foi criado utilizando a fonte de dados `flights-data`. Durante a construção do relatório, editei o layout de acordo com o que considerava mais útil para o time de operações, personalizando cores, textos e outras opções visuais. 

### Funcionalidades do Dashboard

- **KPI de Passageiros**: Mostra a soma de passageiros por ano. O valor é dinâmico e muda conforme o filtro temporal.
- **Gráfico de Série Temporal**: Exibe a soma de passageiros por mês, ajustando-se conforme o ano selecionado.

---
### Aqui está uma visualização do dashboard:

![Dashboard](https://github.com/Bezemon/flights_report_dashboard/blob/main/flights_report.png)
