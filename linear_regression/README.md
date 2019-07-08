Aqui contém a solução para o exercicio de regressão linear feito durante o curso de Engenheiro de Machine Learning da Udacity.

Abaixo estão as instruções para resolução do problema.


Neste quiz, você trabalhará com dados sobre a expectativa de vida média ao nascimento e a média de IMC para homens ao redor do mundo. Os dados foram obtidos no site Gapminder.

O arquivo de dados pode ser encontrado sob a guia "bmi_and_life_expectancy.csv" no quiz abaixo. Ele inclui três colunas, contendo os seguintes dados:

Country – O país em que a pessoa nasceu. Life expectancy – A expectativa de vida média ao nascer para uma pessoa nesse país. BMI – O IMC médio para homens nesse país. Você precisará completar cada um dos passos a seguir:

Carregue os dados
Os dados estão em um arquivo chamado "bmi_and_life_expectancy.csv". Use o read_csv do pandas para carregar os dados em um dataframe (não se esqueça de importar pandas!) Atribua o dataframe à variável bmi_life_data.

Crie um modelo de regressão linear
Crie um modelo de regressão usando o método LinearRegression do scikit-learn e atribua a bmi_life_model. Ajuste o modelo aos dados.

Faça uma previsão usando o modelo
Faça uma previsão usando um IMC de 21.07931 e atribua o resultado à variável laos_life_exp
