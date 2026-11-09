## Classificação dos Preços de Combustíveis

Projeto desenvolvido para a disciplina de Aprendizado de Máquina I, com o objetivo de classificar os preços de combustíveis no Brasil como altos ou baixos, utilizando técnicas de aprendizado supervisionado.

# Base de Dados

Foram utilizados dados públicos da Agência Nacional do Petróleo, Gás Natural e Biocombustíveis (ANP), referentes ao primeiro semestre de 2026.

A classificação foi realizada com base na mediana dos preços de cada combustível:

* 0 — Baixo: preço menor ou igual à mediana.

* 1 — Alto: preço acima da mediana.

Fonte: Série Histórica de Preços de Combustíveis — ANP

# Modelos Utilizados

Foram implementados e comparados dois modelos de classificação:

* Árvore de Decisão

* Random Forest

Os modelos foram avaliados utilizando métricas como acurácia e F1-score.

# Tecnologias

Python, Pandas, Matplotlib, Scikit-learn e Jupyter Notebook.

# Como Executar

Abra o notebook .ipynb no Google Colab ou VS Code.

Execute as células na ordem apresentada.

A base de dados está disponível neste repositório e pode ser carregada diretamente pelo código do notebook.
