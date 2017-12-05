
# Python para Jornalistas - Journalism Course#

## Exercício da semana 3 ##

**Objetivo:**
Usar python para identificar o sexo de uma pessoa através de um nome.

**Método Escolhido:**
Procura de nome digitado em grande base de dados, utilizei uma base de dados pública ('http://www01.seade.gov.br/download/arquivos/OpenData/Eleicoes/Eleicoes.zip') com nomes de candidatos à cargos políticos que concorreram nas eleições de 1998 a 2016.


**Ferramentas Utilizadas**
* Python 3.6.2 - Linguagem alvo de estudo.
* Open Refine 2.8 - (http://openrefine.org/index.html) para eliminar registros nomes repetidos, provavelmente candidatos de mais de uma eleição, primeiramente uni as colunas 'nomecand' e 'data_nasc' e então removi os registros repetidos (observei que ainda restaram alguns registros duplicados onde havia acentuação da Língua Portuguesa. ex: Joao Xxxxx 01/01/1970 - João Xxxxx 01/01/1970, mas para a fim de exercício não refinei)
* Jupyter 5.2.1 - Editar e executar os comandos python e escrever esse Readme.md.
