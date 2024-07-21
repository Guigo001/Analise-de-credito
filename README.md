# Análise de Crédito de uma Instituição Financeira

## Descrição

Este projeto tem como objetivo analisar e tratar dados de clientes de uma instituição financeira para extrair insights úteis. Os dados estão em formato CSV e contêm informações sobre os clientes. O foco principal é entender os fatores que levam um cliente a ser inadimplente (default = 1) ou adimplente (default = 0). A análise busca explicar o comportamento de inadimplência com base em outros atributos, como salário, escolaridade e movimentação financeira.

## Estrutura do Projeto

- `data/`: Contém os arquivos de dados CSV.
- `notebooks/`: Notebooks Jupyter usados para análise e modelagem.
- `src/`: Scripts e módulos Python.
- `reports/`: Relatórios gerados a partir da análise.

## Instalação

### Pré-requisitos

- Python 3.7 ou superior
- pip (Python package installer)

### Passos para Instalação

1. Clone o repositório para sua máquina local:
    
    ```bash
    bashCopiar código
    git clone https://github.com/Guigo001/Projetos.git
    
    ```
    
2. Crie um ambiente virtual:
    
    ```bash
    bashCopiar código
    python -m venv venv
    source venv/bin/activate  # No Windows, use `venv\Scripts\activate`
    
    ```
    
3. Instale as dependências:
    
    ```bash
    bashCopiar código
    pip install -r requirements.txt
    
    ```
    

## Uso

### Executando a Análise

1. Certifique-se de que o ambiente virtual está ativado:
    
    ```bash
    bashCopiar código
    source venv/bin/activate  # No Windows, use `venv\Scripts\activate`
    
    ```
    
2. Execute os notebooks Jupyter na pasta `notebooks/` para realizar a análise:
    
    ```bash
    bashCopiar código
    jupyter notebook
    
    ```
    
3. Navegue até o notebook desejado e execute as células.

### Estrutura dos Dados

Os dados estão no formato CSV e possuem as seguintes colunas principais:

- `default`: Indica se um cliente é adimplente (0) ou inadimplente (1).
- `salario`: Salário do cliente.
- `escolaridade`: Nível de escolaridade do cliente.
- `movimentacao_financeira`: Dados sobre a movimentação financeira do cliente.

## Contribuição

Sinta-se à vontade para contribuir com o projeto. Para isso, siga os passos abaixo:

1. Faça um fork do repositório.
2. Crie uma nova branch com a sua feature ou correção de bug:
    
    ```bash
    bashCopiar código
    git checkout -b minha-feature
    
    ```
    
3. Faça commit das suas alterações:
    
    ```bash
    bashCopiar código
    git commit -m 'Minha nova feature'
    
    ```
    
4. Envie para o branch original:
    
    ```bash
    bashCopiar código
    git push origin minha-feature
    
    ```
