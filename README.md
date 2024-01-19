# Webscrapping Premier League (Python)

Este repositório contém o arquivo em Jupyter Notebook de funções em Python que fazem o webscrapping e limpeza de estatísticas dos jogos da Premier League. Em síntese, elas executam uma _request_ para a API que disponibiliza os dados para o próprio site da liga, executa a limpeza de metadados da partida e das estatísticas de cada time. Ao final do temos um _loop_ que corre por uma lista de partidas (ver mais informações logo abaixo) e vai executando a coleta. Os dados são armazenados num objeto tipo DataFrame e podem ser facilmente exportados para um CSV usando a biblioteca pandas.

## Bibliotecas utilizadas

É possível rodar todo o script dentro do [Google Colab](https://g.co/kgs/XtyCBbi) sem a necessidade de instalar bibliotecas a parte. Mas caso seja necessário rodar em outro ambiente, precisamos apenas instalar o pandas. O as soliticações são feitas através do módulo _requests_ e a conversão das respostas é feito usando o módulo _json_, ambos nativos do Python. Para instalar o pandas, execute o código abaixo.

```{python}
pip install pandas
```

## Entendendo o site da Premier League

## Funções de coleta
Foram criadas quatro funções:
* `request_match_pl` faz a requisição à API;
* `clean_match_info` e `clean_match_stats` limpam, respectivamente, os dados da partida e as estatísticas de cada time;
* `scrape_match` executa tudo simultamente e cria o objeto DataFrame final.

### Requisição

```{python}
pip install pandas
```

### Limpeza da response

```{python}
pip install pandas
```

### União dos dados

```{python}
pip install pandas
```

## _Loop_ da coleta para várias partidas

## Exportando o CSV e o nome das estatísticas

## Contato

GitHub: [Jonas Arjona]()
Linkedin: [Jonas Arjona]()
