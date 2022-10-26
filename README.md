# Analise_vendas_lojas

Este projeto de análise de dados, desenvolvido a partir de uma base de dados fictícia de uma rede de lojas de roupas infantis. A base de dados inicialmente continha quatro planilhas relativas aos dados de vendas, consumidores, lojas e produtos:

Dados de vendas:

- ID: identificador único de uma venda
- ProductID: identificador único de um produto
- ClientID: identificador único de um cliente
- Discount: desconto aplicado em uma venda
- UnitPrice: preço unitário de um produto vendido
- Quantity: quantidade de produto vendido em uma venda
- StoreID: identificador único de uma loja
- Date: data de uma venda

Dados dos consumidores:

- ID: identificador único de um consumidor
- City: cidade/localidade onde um consumidor fez a compra
- State: Unidade Federativa onde um consumidor fez a compra
- DateOfBirth: data de nascimento de um consumidor
- Sex: sexo de um consumidor

Dados das lojas:

- ID: identificador único da loja
- Name: cidade/localidade da loja
- State: Unidade Federativa da loja

Dados dos produtos:
- ID: identificador único de um produto
- Name: nome de um produto
- Size: tamanho de um produto

Posteriormente foram adicionados mais duas planilhas, uma com o nome de banco de dados, que contêm um agrupamento de dados das outras 4 planilhas, e a outra com as tabelas dinâmicas que auxiliaram e orientaram as análises. 

## Análise de dados.
Neste projeto a análise de dados foi desenvolvida utilizando Excel, por meio do google sheets, e depois foi desenvolvido um dashboard em PowerBI.
![Dash_vendas](https://user-images.githubusercontent.com/107072611/198105403-6cdba5ab-b9cb-4ed3-9537-b76b10532195.png)

Durante o processo de análise foram gerados alguns insights relativos ao **produto mais vendido**, **a loja que mais vendeu**, **o faturamento mensal**, além de algumas características dos clientes.

Considerando todo o período estudado e todos os tamanhos disponíveis, o **produto mais vendido** foi o Iron Man, com um total de 1501 unidades vendidas. Contudo aos realizar uma divisão por tamanhos, o que mais vendeu foi o Bazinga tamanho G com 1020 unidades vendidas.

Observando por período anual, em 2018, o mais vendido foi o Thanos tamanho G com 601 unidades, em 2019, foi o BIXDream tambem de tamanho G 869 com unidades. 
* Vale ressaltar que em 2018 a coleta de dados começou em março, e isso influenciou a quantidade de itens vendidos. Já em 2020 foram coletados dados apenas em janeiro inviabilizando a análise.
* Um outro ponto é que o tamanho G é o mais vendido dentre os disponíveis.

Além disso é possível identificar o **produto mais rentável**, levando em conta todo o intervalo estudado, o produto mais lucrativo foi o BixDream tamanho G com quase 595 mil reais em vendas. Ao observarmos o período, em 2018 o mais rentável foi o DeadPool tamanho G com cerca de 140 mil reais em vendas, já em 2019 o mais lucrativo foi o BixDream também no tamanho G com aproximadamente 540 mil reais. 

A **loja de Florianópolis foi a que mais faturou**, alcançando um valor de quase um milhão e seissentos mil reais em vendas, para ser mais exato o valor vendido foi de R$ 1.759.625,76. Além disso, destado que esta loja é a que apresentou o melhor faturamento mesmo observando anualmente.

Aos se observar o **faturamento mensal**, pode-se evidenciar que no período de 2018 os resultado obtidos são mais lineares, sem oscilações muito bruscas, tendo seu pico em dezembro com quase quatrocentos e oitenta mil reais em vendas. Já em 2019 o cenário foi um pouco diferente, houve uma certa instabilidade no período entre Maio e Setembro, com dois picos que apresentaram valores próximos a quatrocentos e cinquenta e cinco mil reais e um vale entre esses picos com quase a metade deste valor. **Vale ressantar que em ambas pode ser uma tendencia de crescimento.**

### Insights sobre os clientes:

Resolvi criar classes de idade para ajudar a identificar quais foram os clientes que mais compraram. 
As classes foram distribuídas da seguinte forma:

- A: 21 à 33 anos
- B: 34 à 46 anos
- C: 47 à 59 anos
- D: 60 à 71 anos

Ao analisar a distribuição de clientes, é possível identicar alguns pontos interessantes:
- A maioria dos clientes são homens, com uma distribuição que fica em torno de 87% de clientes homens e  os outros 13% são mulheres.
- Sobre a faixa etária dos clientes, é evidente que a classe que mais compra é a B, ou seja, clientes com idade entre 34 à 46 anos, e representa quase 45% de todas as vendas.

Tanto o [Dashboard](https://github.com/MateusSampaio1/Analise_vendas_lojas/blob/main/Dash_Vendas.pbix), quanto a [planilha de Excel](https://github.com/MateusSampaio1/Analise_vendas_lojas/blob/main/Base%20de%20Dados%20.xlsx) podem ser encontrados na documentação do projeto.
