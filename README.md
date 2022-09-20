# Aplicação de Series Temporais na Produção de Aço Bruto de 2013 a 2022

Este projeto faz parte do curso [Data Science: análise de series temporais](https://cursos.alura.com.br/course/data-science-series-temporais) da trilha de Ciência de Dados da Alura, decidi por aplicar os conhecimentos na minha área de atuação analisando dados da Produção de Aço Bruto.

| :placard: Vitrine.Dev |     |
| -------------  | --- |
| :sparkles: Nome        | **Evolução da Produção do Aço Bruto**
| :label: Tecnologias | python, statsmodels
| :rocket: URL         | [Notebook](https://github.com/douglascdsantos/alura_data-science-series-temporais/blob/main/comercial_aco.ipynb)
| :fire: Desafio     | [Instituto do Aço Brasil](https://acobrasil.org.br/site/)

<!-- Inserir imagem com a #vitrinedev ao final do link -->
![](https://uploaddeimagens.com.br/images/004/028/650/original/download_%282%29.png#vitrinedev)

## Detalhes do projeto


A base de dados utilizada no projeto foi uma planilha disponibilizada pelo Instituto do Aço Brasil onde temos os dados dispostos de maneira colunar, ao invés de tabular, este foi o primeiro desafio.

![](https://uploaddeimagens.com.br/images/004/028/653/original/Captura_de_tela_2022-09-20_121044.png?1663686670)

Após tratamento temos os dados dispostos no formato tabular

![](https://uploaddeimagens.com.br/images/004/028/661/full/Captura_de_tela_2022-09-20_121303.png?1663686799)

Por meio do metódo [diff do pandas](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.diff.html) podemos calcular a diferença entre a produção do aço para avaliar o aumento e aceleração.

![](https://uploaddeimagens.com.br/images/004/028/709/original/download_%283%29.png?1663688096)

Também foi avaliada a [autocorreção pelo pandas](https://pandas.pydata.org/docs/reference/api/pandas.plotting.autocorrelation_plot.html), a sazonalidade, tendência e os atributos residuais por meios da decomposição sazonal com [statsmodels](https://www.statsmodels.org/dev/generated/statsmodels.tsa.seasonal.seasonal_decompose.html).

![](https://uploaddeimagens.com.br/images/004/028/717/full/download_%284%29.png?1663688265)

E a média móvel de 3 e 6 meses, conforme mostrada no inicio deste repositório, e a autocorreção dos mesmos.

![](https://uploaddeimagens.com.br/images/004/028/723/full/download_%285%29.png?1663688524)


Elaborado por

# [![Linkedin Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white) douglascdsantos](https://www.linkedin.com/in/douglascdsantos/)
