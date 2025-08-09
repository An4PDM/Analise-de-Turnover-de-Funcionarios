**Análise de Turnover (Rotatividade) de Funcionários**

## Sobre o Projeto
Este projeto tem como objetivo analisar o turnover (rotatividade) de funcionários de uma empresa fictícia, identificando padrões e fatores que podem estar relacionados à saída de colaboradores.  

Foram realizadas etapas de **limpeza de dados**, **análise exploratória** e **visualização interativa** para auxiliar na tomada de decisões estratégicas.

---

## Etapas do Projeto

### 1. Limpeza de Dados
- Remoção de valores nulos e inconsistências.
- Ajuste de tipos de dados (numéricos e categóricos).
- Filtragem das colunas usadas no cenário.
- Detecção e análise de **outliers** (ex.: `MonthlyIncome`).

### 2. Análise Exploratória
- Contagem de funcionários com e sem risco de rotatividade (`Attrition` = "Yes"/"No").
- Análise da distribuição de variáveis como:
  - `JobSatisfaction`
  - `EnvironmentSatisfaction`
  - `MonthlyIncome`
  - `YearsAtCompany`
- Identificação de cargos e departamentos mais afetados pelo turnover.
- Comparação de médias de renda e tempo de empresa entre quem ficou e quem saiu.

### 3. Visualização no Power BI
O dashboard interativo contém:
- **Cartões**:
  - Total de funcionários
  - Funcionários com risco de rotatividade
  - Percentual de turnover
- **Gráficos de Barras**:
  - Satisfação no trabalho (`JobSatisfaction`) por departamento
  - Satisfação com o ambiente (`EnvironmentSatisfaction`) por departamento
  - Turnover por departamento/cargo
- **Gráfico de Pizza**:
  - Distribuição de funcionários por `Attrition` (Yes/No)
- **Filtros (Slicers)**:
  - Departamento, Cargo e Gênero

---

## Tecnologias Utilizadas
- **Python** (Pandas, Matplotlib, Seaborn) – limpeza e análise exploratória
- **Power BI** – visualização e dashboard interativo
- **Git/GitHub** – versionamento do projeto

---

## 📈 Principais Insights
- Determinados departamentos apresentam maiores taxas de turnover.
- Funcionários com menor tempo de empresa tendem a ter maior rotatividade.
- Há diferença significativa na renda média entre quem saiu e quem permaneceu.
- Satisfação no trabalho e com o ambiente impactam diretamente na permanência.

---

## 📂 Estrutura do Repositório

