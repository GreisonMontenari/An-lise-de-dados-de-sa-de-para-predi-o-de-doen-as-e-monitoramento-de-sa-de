# Análise de Dados de Saúde para Predição de Doenças e Monitoramento de Saúde

An-lise-de-dados-de-sa-de-para-predi-o-de-doen-as-e-monitoramento-de-sa-de/
│
├── data/                     # Pasta para armazenar dados brutos e pré-processados
│   ├── raw_data/             # Dados brutos
│   └── processed_data/       # Dados já processados
│
├── notebooks/                # Notebooks Jupyter para análise exploratória e modelagem
│   ├── exploratory_analysis.ipynb  # Análise exploratória dos dados
│   ├── model_training.ipynb  # Treinamento do modelo de predição
│
├── scripts/                  # Scripts Python para processar e treinar modelos
│   ├── data_preprocessing.py  # Pré-processamento de dados
│   ├── model_training.py     # Treinamento de modelos
│
├── reports/                  # Relatórios gerados a partir da análise
│   └── final_report.pdf      # Relatório final com insights e resultados
│
├── README.md                 # Documentação do projeto
├── requirements.txt          # Dependências do projeto
└── LICENSE                   # Arquivo de licença (MIT)


# Análise de Dados de Saúde Mental: Predição de Doenças e Monitoramento de Saúde

## Dados

O projeto utiliza um conjunto de dados sobre saúde mental, especificamente sobre distúrbios de ansiedade e depressão. O arquivo CSV está localizado na pasta `data/` e contém informações relacionadas a surtos de ansiedade e depressão no Brasil.

O arquivo CSV contém as seguintes colunas:
- **Data**: Data do registro dos casos
- **Numero_Afastados**: Número de pessoas afastadas por questões de saúde mental
- **Causa**: Causa do afastamento (ansiedade, depressão, etc.)
- **Idade**: Idade média das pessoas afastadas
- **Sexo**: Sexo das pessoas afastadas
- **Localidade**: Localidade dos afastamentos (por estado ou cidade)

O arquivo CSV pode ser encontrado [aqui](data/arquivo.csv).


## Estrutura do Repositório

- **data/**: Contém os dados brutos e pré-processados.
- **notebooks/**: Notebooks Jupyter para análise exploratória, modelagem e testes.
- **scripts/**: Scripts Python para pré-processamento de dados e treinamento de modelos.
- **reports/**: Relatórios gerados a partir da análise dos dados.

## Como Usar

### 1. Instalação das dependências
Este projeto depende das seguintes bibliotecas:
- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib
## Como Contribuir
1. Faça um fork do repositório.
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`).
3. Faça commit das suas alterações (`git commit -m 'Adicionando nova feature'`).
4. Envie para o repositório remoto (`git push origin feature/nova-feature`).
5. Abra um Pull Request.

## Licença
Este projeto é licenciado sob a MIT License - veja o arquivo LICENSE para mais detalhes.
```text
MIT License

Copyright (c) 2025 GreisonMontenari

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS
IN THE SOFTWARE.
