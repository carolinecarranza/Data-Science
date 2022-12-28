# Data-Science
Repositorio com o meu projeto de TCC para a pós em Ciência de Dados do ICMC-USP

## Projeto: Regressão Linear Multipla aplicada ao E-commerce brasileiro

### Objetivo do projeto 
Criar um modelo de Regressão Linear Multipla utilizando a variável dependente `Receita` e as variaveis independentes `Valor do frete, tempo de entrega, itens vendidos e tipo de pagamento`. 

### Base de dados
Utilizei a base para estudo do site `kaggle.com` com o dataset público sobre e-commerce da empresa `Olist Store`. Olist Store é uma plataforma para loja de departamentos (marketplace) no Brasil, é responsável por conectar os lojistas que cadastram seus produtos dentro de sua plataforma aos principais marketplaces do Brasil, tais como Americanas. A Olist também é responsável pela entrega dos produtos aos clientes.

#### Pontos importantes
1. Um pedido pode ter vários itens; 
2. Cada item pode ser de um vendedor distinto;
3. Todas as colunas referentes a lojas e parceiros foram substituídas pelos nomes das casas de Game of Thrones. 

### Esquema de dados
![https://i.imgur.com/HRhd2Y0.png](https://i.imgur.com/HRhd2Y0.png)

Para o desenvolvimento desse trabalho irei utilizar apenas as bases: 
   - olist_orders_dataset
   - olist_order_payments_dataset
   - olist_order_items_dataset
   
Pois o foco da pesquisa é predição e análise explorátoria da variável `Receita`.
