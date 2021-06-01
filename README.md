[dataset NY] https://data.cityofnewyork.us/Public-Safety/NYPD-Arrest-Data-Year-to-Date-/uip8-fykc

Neste projeto, foi feito a coleta dos dados por meio de uma  API, onde consegui os registros referentes a diferentes tipos de delitos praticados na cidade de Nova York  desde 2006 até o ano de 2019.

O objetivo é fazer a previsão dos crimes de assalto de acordo com os dados fornecidos. 

Na primeira etapa os dados foram preparados,  utilizando bibliotecas como Pandas, Numpy, Datetime, e após foram geradas algumas visualizações por meio das bibliotecas Matplotlib, Seaborn e Plotly, que foram úteis para determinar as caraterísticas dos assaltos em cada bairro, como por exemplo horário e dia da semana que mais acontecem.

Após um pré-processamento dos dados, foram testados alguns algoritmos de classificação da biblioteca Scikit-learn e também a biblioteca XGBoost, onde cheguei a um modelo com um recall de 62%, que significa que o classificador encontra os exemplos da classe positiva em 62% dos casos. Já com relação aos casos em que não ocorre assaltos, o classificador se saiu ainda melhor, com recall 65% e precisão de 79% , o que significa que quando o classificador diz que o evento não será assalto, acerta em 79% das vezes.

