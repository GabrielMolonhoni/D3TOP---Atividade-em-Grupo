# D3TOP - Atividade em Grupo

Participantes:

- Beatriz Andrade Luiz - CP3016307
- Gabriel Marques Molonhoni - CP3016129

## Classificação de comentários de compras no e-commerce

### 1. Motivação

A motivação para esse trabalho é poder classificar os comentários da área do varejo
para que esses dados possam ser aproveitados pelas empresas varejistas brasileiras na hora da
divulgação e oferecimento de promoções, incluindo, uma análise sazonal. Sendo assim, a oferta de
produtos pode se adequar a vontade do consumidor naquela época do ano, fazendo com que o
consumo e a economia varejista possam crescer. Além disso, pode-se oferecer uma análise em
tempo real dessas pesquisas e servindo também como entrada para algoritmos de recomendação.

### 2. Descrição

Esse trabalho busca estudar e implementar uma solução de análise de dados de
mecanismos de pesquisa online para o setor de varejo, fazendo com que o setor varejista possa
oferecer produtos específicos em determinados meses do ano com o intuito de adequar as vendas
às demandas da procura online.

O intuito da busca desse assunto deve-se ao crescimento da procura de produtos de
diversos setores de forma online, onde muitas vezes o consumidor não consegue adquirir o
produto desejado, ou pela falta de promoções atrativas daquele produto, ou pela falta de
divulgações da empresa varejista daquele produto específico. O objetivo é que com essa análise,
as empresas varejistas possam verificar quais são os produtos mais buscados e desejados em
determinada época do ano, para que possa ser feita uma melhor oferta daqueles produtos.

### 3. Base de dados

A base de dados pode ser acessada no Kaggle, através do link https://www.kaggle.com/datasets/jayeshsalunke101/brazilian-ecommerce-public-dataset?resource=download.

Há 8 conjuntos de dados que pode ser agrupados e contém dados de:

- Consumidores
- Vendedores
- Produtos
- Pedidos
- Artigos dos pedidos
- Avaliação de pedidos
- Pagamentos
- Geolocalização

Este trabalho terá foco na avaliação de pedidos e classificação (em positivo e negativo).

Os dados foram baixados localmente.

### 4. Arquivos

- model.ipynb - Notebook onde foram desenvolvido os modelos e testados
- app
  - app.py - Server em Flask onde está o modelo em produção
  - template
    - index.html - Front end
  - static
    - style.css - Front end

### 5. Como testar ?

Para testar o modelo em produção, basta executar o app.py. (que está dentro )
Será gerando uma URL parecida com: http://127.0.0.1:5000/
Basta acessar a URL gerada.

### Refêrencias

- https://www.kaggle.com/code/leandroal/an-lise-do-e-commerce-no-brasil-olist-dataset/notebook
