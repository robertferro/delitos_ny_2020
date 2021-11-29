Fonte dos dados utilizados no projeto: https://data.cityofnewyork.us/Public-Safety/NYPD-Arrest-Data-Year-to-Date-/uip8-fykc

Link do artigo no medium: https://robertthiagodesousaferro.medium.com/usando-machine-learning-para-prever-assaltos-em-nova-york-29569c46bf95

**Resumo**

Neste projeto, foi feito a coleta dos dados referentes as delitos praticados na cidade de *New York* por meio de uma  *API(sodapy)*, onde foi possível extrair os registros referentes a diferentes tipos de delitos praticados entre os anos de 2006 até o ano de 2019, com o objetivo final de fazer a previsão dos crimes de assalto de acordo com os dados fornecidos. 

No repositório existem 3 diretórios,**Coleta e tratamento de dados**, ***EDA***, ***Machine Learning***:

**Coleta e tratamentode dados**
Nesta primeira etapa, após ser feito a requisição dosdados por meio da *API sodapy*, os dados foram preparados, com a exclusão de registros incompletos, informaçoes que não seriam necessárias para o projeto e foi feito um primeiro pré-processamento, removendovalores ausentes e criando algumass variáveis.
Foram utilizadas bibliotecas como *Pandas, Numpy, Datetime*.

**EDA**(*Exploratory data analysis)*

Nesta etapa com os dados já tratados, foram geradas algumas visualizações que nos trouxeramm informações sobre os delitos praticados, e identificar alguns padrões de comportamento dos delitos, que foram úteis para determinar as caraterísticas dos assaltos em cada bairro, como por exemplo horário e dia da semana que mais acontecem.
Foram utilizadas as bibliotecas *Matplotlib, Seaborn e Plotly.*

***Machine Learning***

Após um pré-processamento dos dados, foram testados alguns algoritmos de classificação da biblioteca *Scikit-learn* e também a biblioteca *XGBoost*, onde o melhor modelo encontrado, se aplicado poderá reduzir em até 62% os casos de assaltos nacidade de ***New York***

