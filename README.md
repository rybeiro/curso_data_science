# Data Science
Minhas anotações importantes sobre o conteúdo do curso de *Data Science*

## Importando bibliotecas
Importando o Pandas ```import pandas as pd ```

Lendo dados de arquivos CSV ```variavel = pd.read_csv('file.csv')```

## Métodos e informações
Exibindo uma determinada quantidade de linhas e por padrão as 5 primeiras ```varialvel.head()```

Verificando o formato da tabela de dados ```varialvel.shape```

Renomear as colunas da tabela de dados ```varialvel.columns = []```

Para exibir apenas um determinada coluna ```varialve['nome_coluna']``` ou ```variavel.nome_coluna```

Exibindo os valores sem repetição em determinada coluna ```variavel.nome_coluna.unique()```

Exibindo a quantidade de vezes que uma determinado valor foi selecionado ```variavel.nome_coluna.value_counts()```

Exibir a média ```variavel.nome_coluna.mean()```

*describe()*

## Bibliotecas de visualização
- Seaborn
- Plot da biblioteca Pandas

## Documentações para análise
### Pandas
- Dataframe
- Series
- Plot