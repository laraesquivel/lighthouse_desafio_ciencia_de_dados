# Desafio LightHouse de Ciência de Dados

Lara Esquivel de Brito Santos

## Instalação de depêndencias e Execução 

git clone 

### Windows

python3 -m venv venv
venv/Scripts/activate
pip install -r requirements.txt

python -m spacy download en_core_web_sm


### Linux 

python3 - m venv venv
venv\bin\activate
pip install -r requirements.txt

python -m spacy download en_core_web_sm

### Execução

jupyter lab

### Descrição 
requirements.txt : Arquivo de requisitos
analise_exploratoria.ipynb : Exploração dos dados respondendo as perguntas solicitadas
modelagem.ipynb : Tratammento e crianção de um modelo para os dados
ramdom_forest.pkl : Modelo produzido


## Dicionário de Dados

id – Atua como uma chave exclusiva para cada anúncio nos dados do aplicativo
nome - Representa o nome do anúncio
host_id - Representa o id do usuário que hospedou o anúncio
host_name – Contém o nome do usuário que hospedou o anúncio
bairro_group - Contém o nome do bairro onde o anúncio está localizado
bairro - Contém o nome da área onde o anúncio está localizado
latitude - Contém a latitude do local
longitude - Contém a longitude do local
room_type – Contém o tipo de espaço de cada anúncio
price - Contém o preço por noite em dólares listado pelo anfitrião
minimo_noites - Contém o número mínimo de noites que o usuário deve reservar
numero_de_reviews - Contém o número de comentários dados a cada listagem
ultima_review - Contém a data da última revisão dada à listagem
reviews_por_mes - Contém o número de avaliações fornecidas por mês
calculado_host_listings_count - Contém a quantidade de listagem por host
disponibilidade_365 - Contém o número de dias em que o anúncio está disponível para reserva

