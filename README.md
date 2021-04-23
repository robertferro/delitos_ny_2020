[dataset NY] https://data.cityofnewyork.us/Public-Safety/NYPD-Arrest-Data-Year-to-Date-/uip8-fykc

Por meio da API que está disponível no link acima, obtive dados referentes a série histórica de delitos praticados na cidade de Nova York, desde 2006 até o ano de 2019.

Foi feito uma preparação e exploração dos dados,  utilizando bibliotecas como Pandas, Numpy, Datetime, Seaborn e então geradas algumas visualizações.

Com os dados estarem pré-processados, foram testados alguns algoritmos de classificação da biblioteca Scikit-learn e também a biblioteca XGBoost.

O objetivo:
 - por meio dos dados fornecidos, encontrar um melhor algoritmo de classificação, para que a partir dos dados de entrada classificar possíveis regiões mais propícias a ocorrencia de assaltos.
 - Criar uma aplicação WEB com o modelo desenvolvido.
