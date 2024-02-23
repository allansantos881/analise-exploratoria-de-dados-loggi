# Análise Exploratória de Dados de Logística - Loggi

O Loggi Benchmark for Urban Deliveries (BUD) é um repositório do GitHub ([link](https://github.com/loggi/loggibud)) com dados e códigos para problemas típicos que empresas de logística enfrentam: otimização das rotas de entrega, alocação de entregas nos veículos da frota com capacidade limitada, etc. Os dados são sintetizados de fontes públicas (IBGE, IPEA, etc.) e são representativos dos desafios que a startup enfrenta no dia a dia, especialmente com relação a sua escala.

Neste projeto, concentraremos nossa análise na cidade de Brasília, Distrito Federal.

Para isso precisamos do arquivo "dataset": ([link](https://drive.google.com/file/d/1h0XtH4Utv6WdE1m6MYryHCBp8y3qwgbG/view?usp=sharing))

Utilizando as informações geoespaciais de latitude (lat) e longitude (log). Ao explorar os dados do Loggi, buscaremos insights valiosos para otimização de rotas e alocação estratégica de entregas em hubs de distribuição na capital federal.

# Pacotes e bibliotecas:

!pip3 install geopandas
!pip install tabula-py PyPDF2
