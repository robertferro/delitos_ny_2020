Fonte dos dados utilizados no projeto: https://data.cityofnewyork.us/Public-Safety/NYPD-Arrest-Data-Year-to-Date-/uip8-fykc

Link do artigo no medium: https://robertthiagodesousaferro.medium.com/usando-machine-learning-para-prever-assaltos-em-nova-york-29569c46bf95

**Resumo**

Neste projeto, foi feito a coleta dos dados por meio de uma  API, onde consegui os registros referentes a diferentes tipos de delitos praticados na cidade de Nova York  desde 2006 até o ano de 2019.

O objetivo é fazer a previsão dos crimes de assalto de acordo com os dados fornecidos. 

Na primeira etapa os dados foram preparados,  utilizando bibliotecas como Pandas, Numpy, Datetime, e após foram geradas algumas visualizações por meio das bibliotecas Matplotlib, Seaborn e Plotly, que foram úteis para determinar as caraterísticas dos assaltos em cada bairro, como por exemplo horário e dia da semana que mais acontecem.

Após um pré-processamento dos dados, foram testados alguns algoritmos de classificação da biblioteca Scikit-learn e também a biblioteca XGBoost, onde cheguei a um modelo que se aplicado poderia reduzir em até 62% os casos de assaltos, um resultado considerável visto que iria melhorar a segurança pública da cidade de Nova York.


