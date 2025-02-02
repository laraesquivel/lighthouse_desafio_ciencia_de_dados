# Desafio LightHouse de Ciência de Dados

**Lara Esquivel de Brito Santos**

Este repositório contém a solução do desafio de Ciência de Dados da LightHouse. Para executar o projeto, é necessário ter o Git e o Python instalados.

## Clonando o Repositório

```sh
git clone https://github.com/laraesquivel/lighthouse_desafio_ciencia_de_dados.git
cd lighthouse_desafio_ciencia_de_dados
```

## Instalação de Dependências

### Windows

```sh
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python -m spacy download en_core_web_sm
```

### Linux

```sh
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python -m spacy download en_core_web_sm
```

## Execução

Para abrir os notebooks, execute:

```sh
jupyter lab
```

## Descrição dos Arquivos

- **`requirements.txt`**: Lista de dependências necessárias para executar o projeto.
- **`analise_exploratoria.ipynb`**: Notebook com a exploração dos dados e respostas para as perguntas do desafio.
- **`modelagem.ipynb`**: Notebook contendo o tratamento dos dados e a criação de um modelo preditivo.
- **`random_forest.pkl`**: Arquivo contendo o modelo treinado utilizando Random Forest.

## Dicionário de Dados

| Coluna                          | Descrição |
|---------------------------------|-------------|
| `id`                            | Identificador exclusivo do anúncio |
| `nome`                          | Nome do anúncio |
| `host_id`                       | Identificador do anfitrião |
| `host_name`                     | Nome do anfitrião |
| `bairro_group`                  | Nome do bairro onde o anúncio está localizado |
| `bairro`                        | Nome da área onde o anúncio está localizado |
| `latitude`                      | Latitude do local |
| `longitude`                     | Longitude do local |
| `room_type`                     | Tipo de espaço anunciado |
| `price`                         | Preço por noite (em dólares) |
| `minimo_noites`                 | Número mínimo de noites para reserva |
| `numero_de_reviews`             | Quantidade de avaliações recebidas |
| `ultima_review`                 | Data da última avaliação |
| `reviews_por_mes`               | Média de avaliações por mês |
| `calculado_host_listings_count` | Quantidade de anúncios do anfitrião |
| `disponibilidade_365`           | Dias do ano em que o anúncio está disponível para reserva |

---

Caso tenha dúvidas, entre em contato! 🚀

