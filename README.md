# Dashboard-DRE

Visão Geral

Este projeto apresenta um dashboard desenvolvido no Power BI com foco na análise da Demonstração do Resultado do Exercício (DRE) referente ao dados de venda da empresa fictícia "XPBucks".

O objetivo é fornecer uma visão clara do desempenho financeiro da empresa em cada filial, permitindo comparar valores realizados, orçados e previstos, identificar desvios e entender os principais fatores que impactam o resultado.

Objetivo

O dashboard foi desenvolvido para:

- Monitorar indicadores financeiros chave (Receita, Despesas, Margem e Resultado)
- Comparar desempenho real vs planejamento (orçado e previsto)
- Identificar tendências ao longo do tempo
- Compreender os fatores que mais influenciam no resultado líquido (análise vertical)
- Apoiar decisões com base nos dados

Conceitos Utilizados

O projeto utiliza três perspectivas principais:

Lançamento: valores efetivamente registrados
Orçado: planejamento financeiro inicial definido para o período
Previsto: revisão do planejamento com base no desempenho observado

Essa abordagem permite avaliar:

Qualidade do planejamento (Real vs Orçado)
Qualidade da execução (Real vs Previsto)
Ajustes de cenário (Orçado vs Previsto)

Estrutura do Dashboard

O dashboard foi estruturado com base em storytelling de dados, dividido em três páginas:

1. Overview — Visão Geral

Elementos principais:

KPIs: Receita Bruta, Margem de Contribuição, Despesas e Resultado Líquido
Filtros dinâmicos (Empresa, Período, Tipo de Meta)
Matriz DRE completa com destaque visual por performance

Esta página permite avaliar o desempenho das filiais em relação ao orçado e ao previsto, com filtros por ano e mês.
Os cartões apresentam os quatro principais indicadores da DRE, evidenciando sua participação na receita bruta (análise vertical) e o desvio em relação à meta, destacando resultados acima ou abaixo do planejado.
A matriz consolida o comportamento das linhas da DRE por filial no período selecionado, enquanto os tooltips permitem aprofundar a análise do atingimento das metas e seus respectivos desvios.

Exemplo: <img width="1336" height="750" alt="Screenshot 2026-04-14 222149" src="https://github.com/user-attachments/assets/391102f4-fd48-4cc5-9063-bb1148b519a0" />

2. Análises — Tendência e Desvios

Elementos principais:

Evolução do resultado acumulado (YTD)
Comparação entre realizado, orçado e previsto
Análise de variações percentuais (mensal e acumulado)

Esta página destaca o desvio percentual dos resultados em relação às metas (previsto e orçado).
Apresenta a evolução dos resultados mensais e o acumulado no ano (YTD), permitindo uma visão clara do desempenho frente ao planejado.

Exemplo: <img width="1315" height="746" alt="Screenshot 2026-04-14 231052" src="https://github.com/user-attachments/assets/735580c6-5d82-42ed-b354-56f1a3b37d9b" />

3. Detalhes — Análise Profunda

Elementos principais:

Análise vertical (participação das contas na receita)
Detalhamento por conta gerencial
Comparação entre empresas

Esta página detalha o desempenho mensal das filiais, permitindo a análise comparativa dos resultados ao longo do tempo.
O gráfico principal apresenta a evolução dos lançamentos por empresa, facilitando a identificação de tendências e variações entre as filiais.
A análise vertical evidencia a composição dos resultados ao longo dos meses, destacando a participação relativa de cada unidade.
A matriz consolida a estrutura completa da DRE, com visão mensal e acumulada (YTD), permitindo avaliar a contribuição de cada linha no resultado total e apoiar análises mais aprofundadas por filial.

Exemplo: <img width="1316" height="737" alt="Screenshot 2026-04-14 232019" src="https://github.com/user-attachments/assets/dc8c4b4f-6528-4462-97fb-2586d438e650" />

Experiência do Usuário

O dashboard foi projetado para oferecer:

- Leitura rápida através de cores e indicadores visuais
- Navegação intuitiva entre páginas (Overview → Análises → Detalhes)
- Uso de tooltips explicativos para contextualização dos dados
- Layout planejado previamente no Figma
