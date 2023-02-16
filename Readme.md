# ADA - Exploratory Data Analysis
![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)

- Instituição: Let's Code
- Curso: Data4All
- Disciplina: Técnicas de Programação I
- Professores: Bruno Issamo & Gabriel Novais
- Alunos: Amanda Borges Matos Santana Magalhaes, Cauli Vilela Ferreira, Gabriel Soares Moreira, João Victor Carvalho, Matheus Miranda Brandão, Vinicius Rocha Pinheiro.

Este projeto é uma exploração do [dataset](https://www.kaggle.com/datasets/georgescutelnicu/top-100-popular-movies-from-2003-to-2022-imdb) fornecido pelo Kaggle. O foco é explorar os dados e descobrir quaisquer insights interessantes ou padrões que possam estar presentes.

A especificação completa do projeto pode ser encontrada em: [Projeto Final](https://github.com/MatBrands/ADA-Exploratory_Data_Analysis/blob/master/utils/Projeto%20Final.md).

## Conteúdo

- Descrição dos Dados
- Objetivos
- Ferramentas Usadas
- Integrantes
- Recomendações
- Instalação
- Organização do projeto
- Contribuições

## Descrição dos Dados
O conjunto de dados consiste em uma variedade de recursos, como título, nota do imdb, ano e mês de lançamento, classificação indicativa, duração, atores, diretores, genêros, países de locação e país de origem. Também inclui informações sobre o orçamento e retorno financeiro de cada filme no conjunto de dados.

## Objetivos
 Os objetivos deste projeto são: 

- Demonstrar as habilidades obtidas em aula;
- Entender melhor os dados disponíveis;
- Descobrir padrões e relações entre as variáveis;
- Ajudar na tomada de decisão baseada em dados.

## Ferramentas Usadas 
Este projeto foi concluído usando Python e suas bibliotecas associadas, como NumPy, Pandas, Matplotlib, Seaborn.

## Integrantes
Projeto desenvolvido pelos Devs:

- [Amanda Borges Matos Santana Magalhaes](https://github.com/magalhaesaamanda)
- [Cauli Vilela Ferreira](https://github.com/coquizin)
- [Gabriel Soares Moreira](https://github.com/moreiragabrielsoares)
- [João Victor Carvalho](https://github.com/jvDATA)
- [Matheus Miranda Brandão](https://github.com/MatBrands/)
- [Vinicius Rocha Pinheiro](https://github.com/vini-pinheiro)

## Recomendações
- Cada desenvolvedor possuirá um notebook destinado à sua própria análise exploratória.
- Ao desenvolver uma nova funcionalidade o dev deverá informar de maneira breve e sucinta sobre o que foi feito.
- Em relação aos commits será utilizado um padrão:
    - Commits de novas features. Ex: git commit -m "New: Readme"
    - Commits de updates. Ex: git commit -m "Updated: Readme"
    - Commits de remoção. Ex: git commit -m "Removed: Readme"

## Instalação
Foi utilizado o [Python](https://www.python.org/) v3.10.9.

### Conda
No desenvolvimento foi utilizado o gerenciador de pacotes e ambientes [Conda](https://conda.io/). Portanto para prosseguir necessita-se de sua [instalação](https://conda.io/projects/conda/en/latest/user-guide/install/index.html).

- Navegar até a pasta de destino
```sh
cd utils
```

- Instalar dependências
```sh
conda env create -f environment.yml
```

- Ativar
```sh
conda activate ada_eda_venv
```

- Desativar
```sh
conda deactivate
```

### Requirements
Pode-se utilizar o arquivo requirements.txt para criar o ambiente virtual.

- Criar ambiente virtual
```sh
python -m venv ada_eda_venv
```

- Ativar
```sh
source ./ada_eda_venv/bin/activate
```

- Navegar até a pasta de destino
```sh
cd utils
```

- Instalar dependências
```sh
pip install -r requirements.txt
```

- Desativar
```sh
deactivate
```

## Organização do projeto
```sh
ADA-Exploratory_Data_Analysis
├── License
├── Readme.md
├── datasets
│   ├── processed
│   │   └── movies.pkl
│   └── raw
│       └── movies.csv
├── notebooks
│   ├── edas
│   │   ├── amanda.ipynb
│   │   ├── cauli.ipynb
│   │   ├── gabriel.ipynb
│   │   ├── joao_victor.ipynb
│   │   ├── matheus.ipynb
│   │   └── vinicius.ipynb
│   ├── main.ipynb
│   └── tratative.ipynb
└── utils
    ├── environment.yml
    ├── Projeto Final.md
    └── requirements.txt
```

## Contribuições