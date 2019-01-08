### Exploração de dados e Classificação de Músicas do Spotify

## Dataset
O conjunto de dados utilizado nesse projeto foi retirado do artigo do site Minerando Dados:
http://minerandodados.com.br/index.php/2018/04/04/spotify-svm-python/

Link para os dados:
https://github.com/minerandodados/mdrepo/blob/master/data.csv

## Sobre o projeto

Esse projeto consiste da exploração por meio de gráficos e visualizações do conjunto de dados de características de músicas do Spotify

Além disso, utilizando a biblioteca Scikit-Learn da linguagem Python, foram criados modelos de previsão. O alvo (label) é se o usuário gostou da música ou não baseada nos diversos atributos (features) como energa da música, tom da música, acústica, duração, etc...

Os modelos utilizados foram Support Vector Machine (Máquina de Vetor de Suporte) para classificação e Random Forest (Floresta Aleatória).

As avaliações dos modelos ficaram entre 70% e 80%.
