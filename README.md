# DataScienceAirbnb
Previsão de Preços de imóveis do Airbnb no Rio de Janeiro. Dataset: https://www.kaggle.com/allanbruno/airbnb-rio-de-janeiro

## Estratégia de Solução
#### 1. Coletar os dados e consolidar dataset;

#### 2. Filtrar atributos/colunas;

#### 3. Tratar valores faltantes;

#### 4. Checar e modificar a tipagem das variáveis;

#### 5. Análise Exploratória de Dados;

- Checar disposição dos dados
- Verificar e tratar outliers
- Eliminar colunas incoerentes ou não condizentes com o objetivo
- Agrupar valores pulverizados em variáveis categóricas
- Visualização de mapa baseado na localização dos imóveis

#### 6. Encoding;

- Variáveis booleanas True/False em valores 1/0
- Variáveis categórias pelo método One-Hot-Encoding

#### 7. Modelo de Predição;

Selecionar melhor modelo entre:
- RandomForestRegressor
- LinearRegression
- ExtraTreesRegressor

#### 8. Aprimoramento do modelo escolhido;

- Checar importância de cada variável
- Testar modelo sem atributos pouco relevantes

#### 9. Deploy do projeto;

- Criar um arquivo para o modelo (joblib)
- Criar um aplicativo na web utilizando Streamlit

## Explicação das Variáveis

- host_is_superhost           - Variável que diz se a pessoa que está anunciando o imóvel é um "superhost"
- latitude                    - coordenada da latitude da estadia
- longitude                   - coordenada da longitude da estadia
- accommodates                - O número de pessoas que cada airbnb pode acomodar
- bathrooms                   - Número de banheiros em formato numérico
- bedrooms                    - Número de quartos em cada estadia
- beds                        - Número de camas em cada estadia
- minimum_nights              - Número minímo de noites no airbnb
- room_type                   - Tipo da estadia
- property_type               - Tipo de propriedade (onde seria a nossa variável-alvo de classificação)
- extra_people                - Taxa adicional em reais para cada pessoa extra na locação- 
- ano                         - Ano da locação
- mes                         - Mês da locação, em número
- n_amenities                 - Número de "comodidades" do imóvel
- host_listing_counts         - Número de imóveis que o Dono anuncia.
- instant_bookable            - Variável que diz se o imóvel pode ser reservado imediatamente
- cancellation_policy         - Tipo de política de cancelamento.
- Price                       - Preço da diária de estadia (onde seria a nossa variável-alvo de previsão)

## Bibliotecas Utilizadas
- pandas
- pathlib
- numpy
- seaborn
- matplotlib.pyplot
- plotly.express
- sklearn
- joblib
- streamlit

## Vídeo do funcionamento após o Deploy

https://github.com/GabCarmona/DataScienceAirbnb/assets/118035572/cd93af37-8e15-457c-85f1-9df517098fd8

## Minha Experiência com o Projeto
O projeto de data science realizado foi de extrema importância para a ampliação dos conhecimentos nas áreas de machine learning, modelos de previsão e inteligência artificial. Essas disciplinas têm se destacado como pilares fundamentais para a transformação digital em diversas áreas do conhecimento. Ao explorar essas áreas, pude compreender a complexidade e a potencialidade dos algoritmos de machine learning, que são capazes de extrair insights valiosos a partir de grandes volumes de dados. Além disso, aprofundei-me nos modelos de previsão, que permitem antecipar tendências e comportamentos com base em dados históricos. A inteligência artificial, por sua vez, é uma vertente fascinante, com aplicações cada vez mais amplas. Por meio desse projeto, obtive uma visão abrangente dessas áreas e pude perceber como elas podem trazer benefícios significativos para a sociedade, como a melhoria de processos, a otimização de recursos e a tomada de decisões mais assertivas. Essa experiência foi enriquecedora e me permitiu adquirir conhecimentos sólidos e práticos, preparando-me para desafios futuros nesse campo em constante evolução.




