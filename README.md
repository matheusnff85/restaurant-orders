# Restaurant orders

- Foi desenvolvido um programa que coleta informações sobre pedidos e clientes de um restaurante e as organiza em relatórios. Esses dados serão utilizados por uma agência de marketing para impulsionar as vendas e a atração de novos clientes. Ademais, o sistema possibilita um controle eficiente do estoque de ingredientes, de modo que o cardápio digital ofereça apenas os produtos disponíveis em estoque.

---

# Tecnologias utilizadas :books:

- Python

---

# Como Utilizar a aplicação

  1. Clone o repositório

  - Use o comando: `git clone git@github.com:matheusnff85/restaurant-orders.git`
  - Entre na pasta do repositório que você acabou de clonar:
    - `cd restaurant-orders`

  2. Crie o ambiente virtual para o projeto

  - `python3 -m venv .venv && source .venv/bin/activate`
  
  3. Instale as dependências

  - `python3 -m pip install -r dev-requirements.txt`

# Funções

  1. Gerar informações sobre pedidos de clientes.

  - A aplicação gerá um arquivo txt, utilizando o comando `python3 -m src.analyze_log` que pode ser encontrado em `./data/mkt_campaign.txt`, que se baseia nas informações abaixo:

      - Qual o prato mais pedido por 'maria'?

      - Quantas vezes 'Arnaldo' pediu 'hambúrguer'?

      - Quais pratos 'joão' nunca pediu?

      - Quais dias 'joão' nunca foi à lanchonete?

  2. Gerar informações sobre os pratos e os dias de serviço.

  - A aplicação gera informações sobre os pratos pedidos no estabelecimento e seus dias de funcionamento através do comando `python3 -m src.track_orders`, e se baseia nas informações abaixo:

      - Prato favorito por cliente;

      - Pratos nunca pedidos por cada cliente;

      - Dias nunca visitados por cada cliente;

      - Dia mais movimentado;

      - Dia menos movimentado;

  3. Controle do estoque de produtos.

  - A aplicação gera informações sobre os pratos que podem ser feitos com base nos produtos disponíveis no estoque, além de caso algum dos ingredientes acabe, pratos que utilizam o ingrediente em questão são removidos do cardápio eletrônico.

  
---

- Desenvolvido por [Matheus Marinho](https://www.linkedin.com/in/matheus-marinhodsp/).