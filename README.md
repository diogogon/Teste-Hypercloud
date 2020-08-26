<h1 align="center"> Teste Hypercloud </h1>
<p align="center"> Teste técnico de Business Intelligence da Hypercloud para avaliar a aptdão ao cargo de Assistente de BI (Home Office) </p>

## Teste teórico:
#### 1. Para você, o que significa Business Inteligence?
<p align="justify"> É um processo que apoia a tomada de decisão. Ele transforma dados brutos e entrega conhecimento ao tomador de decisão que usará sua inteligência para resolver problemas. </p>

#### 2. Cite duas ferramentas de ETL.
Pentaho Data Integration (PDI) e Talend Data Integration.

#### 3. Cite três ferramentas de apresentação de Dados.
Power BI, Qlik Sense e Tableau.

#### 4. O que é uma Tabela Fato e o que é uma tabela Dimensão?
<p align="justify"> As tabelas dimensões possuem os dados descritivos que são utilizadas como filtros. Quando se unem em torno de uma métrica podemos criar uma linha da tabela fato. Então, a tabela fato é formada por um conjunto de métricas que permitem analisar o desempenho do negócio – a tabela central do negócio. </p>

#### 5. Quais tipos de modelagens são as mais utilizadas em um projeto de BI?
As mais utilizadas são os esquemas floco de neve e estrela.

#### 6. O que significa Surrogate Key?
<p align="justify"> É a chave artificial utilizada para conectar as tabelas dimensões na tabela fato. Chaves principais (naturais – id de produto, siglas UF’s...) também podem fazer isso, mas seu diferencial é guardar o histórico, por isso ela é auto incremental. Na tabela fato ela se torna uma chave estrangeira. </p>

#### 7. Explique a diferença entre relacionamento 1 para 1 e 1 para N.
<p align="justify"> São as relações, que se dão pelas chaves, entre as colunas das tabelas. O tipo 1:1 significa que para cada 1 ocorrência em uma tabela está associada a 1 ocorrência em outra tabela. E vice-versa. Ex: Cliente <-> CPF. Já o tipo 1:N ocorre quando 1 ocorrência em uma tabela está associada a N ocorrências de outra tabela. Ex: o id de Produtos de uma tabela dimensão está para N (muitos) id de Produtos na tabela fato baseada nas vendas. </p>

#### 8. O que significa Drill Down / Drill Up?
<p align="justify"> Essas operações estão ligadas ao nível de detalhamento. Um Drill Down aumenta o nível de detalhes da informação, a destrinchando em partições relacionadas ao todo. Ex: (1) País-Estado-Município-Bairro. Um Drill Up faz o inverso, pega a menor granularidade (mais detalhado) e sobe na hierarquia. </p>

## Teste técnico:
#### 1. Faça um Desenho da modelagem deste Data Warehouse relacionando as tabelas.
O desenho do modelo foi feito no MySQL Workbench em diagramas:

<p align="center"> <img src="https://github.com/diogogon/Teste-Hypercloud/blob/master/Modelagem_Snowflake.png"> </p>

#### 1.1. Qual a modelagem projetada?
Esquema floco de neve (SnowFlake), pois nesse caso há ramificações nas dimensões, isto é, ligação entre elas.

## Visuais
#### Arquivo PBIX
[Teste_PowerBI_HyperCloud](https://github.com/diogogon/Teste-Hypercloud/blob/master/Teste_Hypercloud.pbix)

## Autor
*Diogo Gonçalves*
> E-mail: dio.goncalves90@gmail.com

> Github: https://github.com/diogogon

> Linkedin: www.linkedin.com/in/diogogon
