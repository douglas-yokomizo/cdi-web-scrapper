# Taxa CDI Scraper e Visualizador

Este é um script Python que captura a taxa CDI do site da B3, salva os dados em um arquivo CSV e, em seguida, gera um gráfico dos dados em png.

## Como usar

1. Execute o script Python. Ele irá capturar a taxa CDI do site da B3 a cada poucos segundos por um total de 10 vezes. Os dados capturados (data, hora e taxa CDI) serão salvos em um arquivo chamado `taxa-cdi.csv`.

```bash
python analise.py
```

2. O script então lê o arquivo `taxa-cdi.csv`, extrai as colunas 'hora' e 'taxa' e plota um gráfico de linha dos dados. O gráfico é salvo como uma imagem PNG.

## Dependências

Este script depende das seguintes bibliotecas Python:

- os
- time
- json
- random
- datetime
- csv
- sys
- pandas
- seaborn
- requests

Certifique-se de ter todas essas bibliotecas instaladas antes de executar o script.

## Notas

Este script foi criado para fins de aprendizado e não deve ser usado para captura de dados em grande escala sem permissão. Além disso, a taxa CDI é ligeiramente randomizada para fins de demonstração.
