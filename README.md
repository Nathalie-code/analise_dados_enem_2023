<h1> Mapa de Desemepenho de Redação do Enem 2023 por Estado📉</h1>

<h2>Resumo</h2>

![Mapa de Calor ENEM-2023](mapa_media_enem.png)

</h2>Projeto de análise e visualização espacial do desempenho médio dos candidados na prova de Redaçãodo ENEM-2023. Utilizando ferramentas de Inteligência Geográfica, é apresentado a desigualdade regional entre os Estados. 

<h2>Bibliotecas aplicadas</h2>

- Linguagem: Python.
- Manipulação de dados: Pandas.
- Dados Geoespaciais: GeoPandas e GeoBr.
- Visualização: Matplotlib.

<h2>Metodologia</h2>

- Extração: média de redação utilizando a base de microdados.
- Geometria: Consumo da base oficial de mapas do IBGE via geobr.

- Tratamento: Limpeza de strings (remoção de espaços) para garantir o merge perfeito entre os dados tabulares e espaciais.

- Plotagem: Geração do mapa coroplético com marcação dos centróides (siglas dos estados).