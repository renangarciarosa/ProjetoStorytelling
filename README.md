# ProjetoStorytelling
Projeto de Storytelling para analisar e recomendar a abertura de um comércio usando robôs-garçons

# O Desafio
---
Você decidiu abrir um pequeno café controlado por robôs no Brasil. O projeto é promissor, mas caro, então você e seus parceiros decidem tentar atrair investidores. Eles estão interessados ​​nas condições atuais do mercado - você será capaz de manter seu sucesso quando a novidade dos garçons robôs passar?
Tire uma conclusão geral e forneça recomendações sobre o tipo de restaurante e o número de assentos. Faça uma apresentação de sua pesquisa para compartilhar com os investidores - o público-alvo .

# descrição de dados
Para esse projeto, utilizei Dados de código aberto sobre restaurantes em Los Angeles, onde existem projetos semelhantes a esse. O conjunto de dados está denominado como rest_data_us.csv, e tem como atributos:

* object_name - nome do estabelecimento
* cadeia - estabelecimento de cadeia (TRUE / FALSE)
* object_type - tipo de estabelecimento
* endereço - endereço
* número - número de assento

#Resumo da pesquisa de mercado do estabelecimento de LA:
---
#Estabelecimentos de LA:

* Contagem total de restaurantes: 9.651
* 62% não são franquias e 38% são.
* Estabelecimentos da rede - número de assentos em duas categorias:
  1. Poucos assentos (< 50) 
  2. e muitos assentos (> 61)

#Cafeteria:

* Aproximadamente 4,5% da participação de mercado
* É mais provável que seja uma rede (61,1%)
  1. De acordo com pesquisas de mercado, essa tendência deve continuar aumentando
* Estabelecimentos de rede menor parcela de muitos assentos (> 61) em relação a outro tipo de estabelecimento
  1. os caracteriza como pequenos locais
  2. Número médio de assentos = 25

# Restaurante:

* Grande parcela de estabelecimentos em LA : os restaurantes representam cerca de 75% dos estabelecimentos em LA - tornam-se relativamente mais fáceis de competir e prosperar devido ao serviço que irão fornecer
* Mais propensos a serem não correntes (68,4%)
* Correntes :
    1. 1/5 ou 20% têm muitos assentos (> 60)
    2. Têm em média 48 lugares
    3. 68% das ruas contêm 1 restaurante, enquanto 32% contêm mais de 1; As 10 principais ruas contêm entre 110 e 230 restaurantes.
* Ruas com mais de 10 restaurantes
    1. Ter uma média de 32 assentos
    2. A distribuição dos assentos pode ser dividida em dois grupos e não difere entre os estabelecimentos de rede e não rede.


# VISUALIZAÇÃO DE DADOS
---
As visualizações de dados geralmente servem a um de dois objetivos: apresentar ou explorar dados. Aqui, eu confio no primeiro e uso uma combinação do pacote Matplotlib e Seaborn do python para fazer isso.

# Conclusão

* Restaurantes com maior probabilidade de serem não franquias (68,4%)

* Grande parcela de estabelecimentos em LA : os restaurantes representam cerca de 75% dos estabelecimentos em LA - tornam-se relativamente mais fáceis de competir e prosperar devido ao serviço que irão fornecer

Ao pensar em se estabelecer em LA, dados: (1) estabelecimento escolhido (pequeno Café), (2) a novidade do serviço prestado (garçons robô), (3) as atuais condições de mercado, (4) custo do projeto, e (5) objetivo de longo prazo para manter um estabelecimento de sucesso, a seguinte conclusão é dada:

*A empresa deve pivotar no sentido de estabelecer um restaurante, pois há menos grandes players nesse mercado em relação aos cafés; pequenos cafés estão sendo superados por franquias de cafés. Além disso, a empresa deve considerar começar como uma não rede com 48 e (média para uma rede de restaurantes) e dependendo de sua estratégia, estabelecer-se em uma rua com muitos restaurantes e / ou um restaurante. Ela pode então crescer agressivamente e estabelecer uma rede a partir de então, dada a novidade do serviço prestado.*
