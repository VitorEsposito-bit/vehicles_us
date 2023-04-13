# Vehicles_us

Descrição do projeto

De forma fictícia, sou analista na Lista de Eixo de Manivela. Centenas de propagandas gratuitas de veículos são publicadas no site todos os dias. Vamos estudar os dados coletados nos últimos anos e determinar quais fatores influenciaram o preço de um veículo.
Primeiro, vamos estudar como os valores atípicos influenciam as diversas variáveis como: preço, idade do veículo, data que propaganda foi colocada e etc.
Depois, vamos trabalhar com um dataframe filtrado sem os valores atípicos e vamos utilizar ele como base para comparar os seus resultados com o dataframe não filtrado.
Por fim vamos analisar o número de propagandas e o preço médio para cada modelo de veículo e identificar/estudar o que influenciou no preço dos veículos.

## Descrição de Dados
O conjunto de dados contém os seguintes campos:
- price
- model_year
- model
- condition
- cylinders
- fuel — gasolina, diesel etc.
- odometer — a quilometragem do veículo quando a propaganda foi publicada
- transmission
- paint_color
- is_4wd — Se o veículo é 4 por 4 (tipo Booleano)
- date_posted — a data que a propaganda foi publicada
- days_listed — dias desde a publicação até a retirada

### Colunas criadas via análise:
 - week_day
 - month
 - year
 - vehicle_age
 - mean_odometer
