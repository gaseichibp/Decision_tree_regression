# Decision tree regression

# `English version`:

### Description

This project demonstrates the implementation of Decision Tree Regression to predict salaries based on position levels. The dataset contains information about various positions in a company along with their corresponding levels and salaries.

### Dataset

The dataset `Position_Salaries.csv` contains the following columns:
- Position: Job title
- Level: Position leve(1-10)
- Salary: Correponding salary in dollays

### Requirements

The porjects requires the following Python packages:
- numpy
- pandas
- matplotlib
- scikit-learn

These packages are already in the included `venv` virtual environment

### How to Run

1. Activate the virtual environment:

```bash
source venv/bin/activate #on Linux/Mac
venv\Scripts\activate #on Windows
```

2. Run the Python script:

```bash
python decision_tree_regression.py
```

### Code Explanation
The script decision_tree_regression.py performs the following steps:

 1. Imports necessary libraries (numpy, pandas, matplotlib)
 2. Loads the dataset from Position_Salaries.csv
 3. Prepares the feature matrix (X) and target vector (y)
 4. Creates and trains a Decision Tree Regressor model
 5. Makes a prediction for position level 6.5
 6. Visualizes the results with a scatter plot and regression curve

### Results 

The script outputs:
  - A prediction for level 6.5 (shown in the console)
  - A visualization comparing actual salaries (red dots) with the Decision Tree Regression model's predictions (blue line)

![Decision Tree Regression Visualization](Figure_1.png)
    
### Notes
  - The Decision Tree Regressor is initialized with random_state=0 for reproducibility
  - The visualiation uses a high-resolution grid(0.01 step) to show the step-like nature of decision tree predictions

### Git Repository Structure
```text
decision_tree_regression/
├── venv/                   # Virtual environment with dependencies
├── Position_Salaries.csv   # Dataset file
├── decision_tree_regression.py  # Main script
├── Figure_1.png            # Output visualization
└── README.md               # This file
```

# `Versão em Português (BR)`:

### Descrição

Este projeto demonstra a implementação de uma Árvore de Decisão para Regressão (Decision Tree Regression) para prever salários com base em níveis de cargo. O conjunto de dados contém informações sobre várias posições em uma empresa, juntamente com seus respectivos níveis e salários.

### Conjunto de Dados

O arquivo `Position_Salaries.csv` contém as seguintes colunas:
- Position: Cargo
- Level: Nível do cargo (1-10)
- Salary: Salário correspondente em dólares

### Requisitos

O projeto requer os seguintes pacotes Python:
- numpy
- pandas
- matplotlib
- scikit-learn

Estes pacotes já estão instalados no ambiente virtual `venv` incluído.

### Como Executar

1. Ative o ambiente virtual:

```bash
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate    # Windows
```
Execute o script Python:

```bash
python decision_tree_regression.py
``` 
## Explicação do Código
O script decision_tree_regression.py executa os seguintes passos:
 1. Importa as bibliotecas necessárias (numpy, pandas, matplotlib)
 2. Carrega o conjunto de dados de Position_Salaries.csv
 3. Prepara a matriz de características (X) e o vetor alvo (y)
 4. Cria e treina um modelo de Árvore de Decisão para Regressão
 5. Faz uma previsão para o nível de cargo 6.5
 6. Visualiza os resultados com um gráfico de dispersão e curva de regressão

## Resultados
O script gera:

- Uma previsão para o nível 6.5 (exibida no console)
- Uma visualização comparando salários reais (pontos vermelhos) com as previsões do modelo (linha azul)

![Decision Tree Regression Visualization](Figure_1.png)

## Observações
- O modelo de Árvore de Decisão é inicializado com random_state=0 para garantir reprodutibilidade
- A visualização utiliza uma grade de alta resolução (passo de 0.01) para mostrar a natureza escalonada das previsões de árvore de decisão

## Estrutura do Repositório Git
```text
decision_tree_regression/
├── venv/                   # Ambiente virtual com dependências
├── Position_Salaries.csv   # Arquivo de dados
├── decision_tree_regression.py  # Script principal
├── Figure_1.png            # Visualização dos resultados
└── README.md               # Este arquivo
``` 
