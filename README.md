# Analisando o gitHubArchive

Utilizando a base de dados do https://www.githubarchive.org/ realizei diversas análises com a 
finalidade de responder algumas perguntas sobre a utilização do github. 

Com a ferramente bigquery.cloud.google.com realizei consultas e extrair diversos csv que você pode encontrar no [linked](https://drive.google.com/file/d/0BwqKhM_BnSmgd0pyd2hjaVBDWDg/view?usp=sharing)

A análise foi feita em 4 diferentes ferramentas. 

* Análise dos tipos de ações ao longo do dia 1/1/2015 (Spark/Hadoop)
* Análise dos user mais ativos entre 2011~2014 (R)
* Análise das palavras utilizadas nos commits e nas descrições dos projetos mais ativos de 2014 (R)
* Análise da evolução do commits do projeto do Eclipse mês a mês no ano de 2014(R)
* Análise do projeto mais ativo de 2014 mês a mês (d3)
* Análise dos tipo de repositórios (públicos e privados) ao longo dos anos (Pandas/Python)

As análises em R você pode encontrar no meu rpub. [Aqui](http://rpubs.com/Rodolfo_Viana/185649) o código pode ser encontrado na pasta R
O mesmo para a análise em Pandas/Python. 

Já a análise em D3 você pode encontrar nesse [link](http://rodolfoviana.github.io/gitHubArchive/) o código pode ser encontrado na branch gh-pages do projeto. 
O código e análise em Spark/Hadoop podem ser encontrados no documento "Código em Spark"

Todas as consultas realizadas no bigquery podem ser encontradas no documento "Consultas"

Dúvidas e sugestões são sempre bem vindas. 
