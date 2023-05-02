# Case Boticário - Previsão de Vendas
## Desenvolvedora: Bruna Moura Bergmann

## Features

- Treina e salva o modelo com a base histórica de vendas
- Realiza a previsão utilizando o modelo treinado e salva no arquivo resultado.xlsx

## Pré-requisitos

- Python versão 3.9 ou superior instalado
- Módulos do Python instalados: numpy, pandas, scikit-learn, seaborn, sqlite3, openpyxl

## Utilização

1. Copiar os arquivos recebidos para um diretório (<INST_DIR>)
2. Abrir o prompt de comando e executar as seguintes instruções

```sh
cd <INST_DIR>
python caseBoticario.py
```


3. Os resultados serão gravados nos arquivos
<INST_DIR>/resultado.xlsx  : Resultado da predição
<INST_DIR>/modelo_dump.pkl  : Modelo treinado
