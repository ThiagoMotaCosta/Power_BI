
## Modelo Financeiro

<p>
  <img src="Images/Financeiro.png" width="650" alt="Imagem Relatório Financeiro">
</p>

**Dataset:** 
-  Base Financeiro Modelo.xlsx (Base com as movimentações de lojas com pagamentos e recebimentos
-  Calendário (A ser substituído por tabela a ser construída no Power Query - melhor prática)
 
**Tratamento:**
- Exclusão de linhas superiores desnecessárias (rótulo de relatório)
- Utilização de primeira linha como cabeçalho
- Tipagem correta de dados
- Remoção de colunas
- Substituição de valores
 
**Métricas**
- Segmentação das métricas própria para fácil identificação
- Utilização de DAX como: 
  - CALCULATE: para somas contextualizadas
  - SUMX e TOPN: para soma soma e contagem de lojas com maior lucratividade
 
**Visualização**
- Image Grid: Imagem como filtragem de dados
- Scroller: Texto dinâmico na parte superior
- Enligten Data Story: Texto com variáveis metrificadas
- Gráfico cascata: Fluxo de caixa
- Barras clusterizadas: Top 3 Lojas com maior lucratividade
- Gráfico Rosca: Margem




