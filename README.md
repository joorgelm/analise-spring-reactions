
<!-- SOBRE O PROJETO -->
<b><p align="center">Compreendendo Reactions: Explorando Características de Uso e Perfis de Usuários em Comunidades Open Source </p></b>

### Tecnologias utilizadas

* Python 3.11
* JuPyter Notebook
* Pandas
* Plotly
* PyPi

<!-- INICIANDO PROJETO -->
## Iniciando o projeto

### Pré-requisitos

Para subir o projeto em um sistema operacional unix
é necessário:

* Python 3.11
* JuPyter Notebook
* PyPi

### Inicialização

* Abra o notebook `spring-final.ipynb` no Jupyter Notebook
* Faça a instalação das dependências
```
pip3 install pandas
pip3 install seaborn
pip3 install plotly==5.22.0
pip3 install pyarrow
```

* Faça a execução das células do notebook

## Dataset
O dataset utilizado no projeto é composto por arquivos .csv

Exemplo de código para leitura de um arquivo csv:

```python
import pandas as pd
df = pd.read_csv('arquivo.csv')
```

No diretório `csv_backup` estão os arquivos csv utilizados no projeto.

## Localização dos usuários

Para a localização dos usuários, foi utilizado o projeto location-resolver, disponível em: https://github.com/ledes-facom/location-resolver
