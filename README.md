# Data-Sciences
aula 1

mport pandas as pd

uri = 'https://raw.githubusercontent.com/alura-cursos/introducao-a-data-science/master/aula4.1/movies.csv'
filmes = pd.read_csv(uri)
filmes.head()
# filmes.size

*******************


import pandas as pd

uri = 'https://raw.githubusercontent.com/alura-cursos/introducao-a-data-science/master/aula1.2/ratings.csv'
notas = pd.read_csv(uri)
print (notas.head(6), notas.tail(6))
# filmes.size


*******************

import pandas as pd

uri = 'https://raw.githubusercontent.com/alura-cursos/introducao-a-data-science/master/aula1.2/ratings.csv'
notas = pd.read_csv(uri)
print (notas.head(6), notas.tail(6))
print (notas.size)


*******************
https://github.com/alura-cursos/introducao-a-data-science/blob/master/aula4.1/introdu%C3%A7%C3%A3o_a_data_science.py
