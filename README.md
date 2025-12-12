# Data Professional Survey Breakdown

## Visão Geral

Este projeto apresenta um dashboard interativo criado no Power BI para analisar respostas de profissionais da área de dados ao redor do mundo. Ele reúne informações sobre salários, preferências técnicas, satisfação profissional e características demográficas dos respondentes.

## Objetivo

Oferecer uma visão clara sobre o perfil dos profissionais de dados, permitindo identificar tendências em:

* País de atuação
* Nível salarial
* Linguagens preferidas
* Dificuldade de entrada na área
* Níveis de felicidade com salário e equilíbrio de vida
* Idade média e total de participantes

## Estrutura do Dashboard

O dashboard é composto por **6 gráficos** e **2 cartões (cards)**:

### 1. Country of Survey Takers (Treemap)

Exibe a distribuição dos participantes por país, permitindo entender onde a pesquisa teve maior representatividade.

### 2. Average Salary by Job Title (Stacked Bar Chart)

* **Eixo Y:** Job Title
* **Eixo X:** Average Salary
* **Legenda:** Job Title

Compara a média salarial entre diferentes cargos na área de dados.

### 3. Favorite Programming Language (Stacked Column Chart)

* **Eixo X:** Favorite Programming Language
* **Eixo Y:** Count of Voters
* **Legenda:** Job Title

Mostra as linguagens mais populares entre profissionais, segmentadas pelos tipos de função.

### 4. Difficulty to Break into Data (Donut Chart)

* **Legenda:** How difficult was it for you to break into Data
* **Valores:** Count de respostas

Representa a percepção dos participantes sobre a dificuldade de ingressar na área.

### 5. Happiness With Salary (Gauge Chart)

* **Valor:** Average da satisfação com salário
* **Mínimo:** Valor mínimo da escala de satisfação
* **Máximo:** Valor máximo da escala de satisfação

Apresenta um nível médio de felicidade relacionado ao salário atual.

### 6. Happiness With Work/Life Balance (Donut Chart)

* **Valor:** Average da satisfação com equilíbrio de vida e trabalho

Mostra o nível geral de contentamento com o balanceamento entre vida pessoal e profissional.

## Cards

### • Total de Participantes

Exibe o número total de pessoas que responderam à pesquisa.

### • Idade Média

Traz a idade média dos participantes, permitindo uma rápida leitura demográfica.

## Tecnologias Utilizadas

* Power BI Desktop
* Power Query (para tratamento dos dados)
* DAX (para cálculos e agregações)

## Como Usar

1. Baixe o arquivo `.pbix` disponível na pasta `dashboard/` (quando você adicionar).
2. Abra no Power BI Desktop.
3. Explore filtros e interações entre os gráficos.

## O que Aprendi

* Construção de visuais variados no Power BI (treemap, stacked bar, donut, gauge).
* Utilização de medidas DAX para criação de KPIs.
* Estruturação de dashboards temáticos focados em insights profissionais.

## Próximos Passos

* Adicionar segmentadores por gênero ou nível de experiência.
* Criar uma versão otimizada para publicação no Power BI Service.

---

*Este projeto integra meu portfólio de análise de dados. Feedbacks são bem-vindos!*
