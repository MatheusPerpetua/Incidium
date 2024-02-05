# Incidium
 Desafio Cientista de Dados

Você foi alocado(a) em um time da Indicium que está trabalhando atualmente junto a um cliente no processo de criação de uma plataforma de aluguéis temporários na cidade de Nova York. Para o desenvolvimento de sua estratégia de precificação, pediu para que a Indicium fizesse uma análise exploratória dos dados de seu maior concorrente, assim como um teste de validação de um modelo preditivo.

Seu objetivo é desenvolver um modelo de previsão de preços a partir do dataset oferecido, e avaliar tal modelo utilizando as métricas de avaliação que mais fazem sentido para o problema.

## Instalação

Este projeto requer Python 3.10.12 e as bibliotecas contidas em requeriments.txt

Você também precisará ter software instalado para rodar e executar um Jupyter Notebook eu utilizei a IDE do VSCode.

Execução
Em um terminal ou janela de comando, navegue até o diretório raiz do projeto (que contém este README) e execute os seguintes comandos: 

## Se estiver utilizando Ubuntu

A partir do terminal instale:

pip install python-3.10.12

pip install -r requirements.txt

## Se estiver utilizando Windows

A partir do terminal instale:

conda create -n stenv python=3.10.12

conda activate stenv

pip install -r requirements.txt

# Dados

Os dados do Airbnb para a cidade de Nova York estão disponíveis aqui. Aqui estão as descrições das colunas:

id: ID único para cada anfitrião

nome: nome do anfitrião

host_id: ID do anfitrião

host_name: nome do anfitrião

bairro_group: grupo de bairros
  
bairro: bairro

latitude: coordenada da latitude da propriedade

longitude: coordenada da longitude da propriedade

room_type: tipo de quarto

price: preço em dólares

minimo_noites: número mínimo de noites

numero_de_reviews: número de reviews

ultima_review: data da última review

reviews_por_mes: número de reviews por mês

calculado_host_listings_count: quantidade de locais que o anfitrião tem

disponibilidade_365: número de dias de disponibilidade dentro de 365 dias



