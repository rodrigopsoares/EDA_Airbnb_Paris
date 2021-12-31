# Análise Exploratória e Visualização de Dados

Autor: Rodrigo Pompermayer Soares

* Linguagem: Python 

## Objetivo:
Fundado em 2008, o Airbnb é um serviço online de reserva de casas e apartamentos. A empresa atua como um intermediário entre os hóspedes e os anfitriões que oferecem desde um quarto individual até um imóvel completo.

Por ser uma empresa Open Data, o Airbnb disponibiliza este dataset e outros em seu [website](http://insideairbnb.com/get-the-data.html).

Neste projeto, será feita uma análise descritiva e exploratória dos dados contidos no dataset da cidade de Paris, fornecido no [website](http://insideairbnb.com/get-the-data.html) da empresa. O dataset disponibilizado é de 09 de outubro de 2021.

## Conjunto de Dados:

 - ``id`` - identificador único utilizado para identificar o imóvel
 - ``name`` - nome do imóvel
 - ``host_id`` - identificador único do proprietário (anfitrião) do imóvel
 - ``host_name`` - nome do proprietário (anfitrião) do imóvel
 - ``neighbourhood_group`` - esta coluna do dataset não apresenta nenhum valor válido
 - ``neighbourhood`` -  nome do bairro
 - ``latitude`` - coordenada da latitude do imóvel, obtida a partir do WGS84 (World Geodetic System - Sistema de geodésico global)
 - ``longitude`` - coordenada da longitude do imóvel, obtida a partir do WGS84 (World Geodetic System - Sistema geodésico global)
 - ``room_type`` - tipo de acomodação oferecido
 - ``price`` - valor da diária na moeda local
 - ``minimum_nights`` - número mínimo de noites para reservar a acomodação 
 - ``number_of_reviews`` - número de avaliações que o imóvel possui
 - ``last_review`` - a data da última avaliação recebida pelo imóvel
 - ``reviews_per_month`` - número de avaliações recebidas por mês
 - ``calculated_host_listings_count`` - quantidade de acomodações do mesmo anfitrião
 - ``availability_365`` - número de dias de disponibilidade denrto de 365 dias
 - ``number_of_reviews_ltm`` -  número de avaliações recebidas nos últimos 12 meses
 - ``license`` - número da licença
