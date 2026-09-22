# TripleTen — Data Science

Portfólio dos projetos desenvolvidos no bootcamp de Ciência de Dados da TripleTen.

| Sprint | Projeto | Tema | Principais ferramentas |
|---|---|---|---|
| 1 | [Store 1 — Qualidade de dados](01-store1-qualidade-de-dados/store1_qualidade_de_dados.ipynb) | Fundamentos de Python: tipos, strings, listas, laços e tratamento de erros | Python |
| 2 | [Se liga na música](02-se-liga-na-musica/se_liga_na_musica.ipynb) | Pré-processamento e teste de hipótese sobre a atividade de usuários de streaming em duas cidades | pandas |
| 3 | [Instacart](03-instacart/instacart_manipulacao_de_dados.ipynb) | Limpeza de dados e análise exploratória de pedidos de supermercado online | pandas, matplotlib |
| 4 | [Megaline — Qual é o melhor plano?](04-megaline-melhor-plano/megaline_melhor_plano.ipynb) | Análise estatística de receita por plano de telefonia e testes de hipótese | pandas, NumPy, SciPy, matplotlib |
| 5 | [Web app](https://github.com/lucasscmperez-bot/Sprint_5_project) | Aplicação web de análise de dados (repositório separado) | Python, Render |
| 6 | [Ice — Videogames](06-ice-video-games/ice_video_games.ipynb) | Análise de vendas de jogos por plataforma, gênero e região; testes de hipótese e matriz BCG | pandas, seaborn, SciPy |
| 7 | [Zuber — Chicago](07-zuber-chicago/zuber_chicago.ipynb) | Análise de corridas de táxi, concentração de mercado (Pareto, Gini, HHI) e impacto do clima | pandas, SciPy, requests, BeautifulSoup |
| 8 | [Megaline — Classificação de planos](08-megaline-classificacao-de-planos/megaline_classificacao_de_planos.ipynb) | Modelo de classificação para recomendar planos (árvore de decisão, random forest, regressão logística) | scikit-learn |

## Como executar

Os notebooks foram desenvolvidos no ambiente da TripleTen, que lê os dados de `/datasets/`. Os conjuntos de dados não estão incluídos neste repositório; para rodar localmente, coloque os arquivos CSV correspondentes em uma pasta `datasets/` e ajuste os caminhos de leitura.

```bash
pip install pandas numpy scipy matplotlib seaborn scikit-learn requests beautifulsoup4 jupyter
jupyter notebook
```

## Autor

Lucas Gonçalves — [LinkedIn](https://www.linkedin.com/in/lucas-gon%C3%A7alves-35007084)
