# Projeto de Machine Learning no Azure

Este projeto tem como objetivo criar uma automação prática de Machine Learning usando as capacidades da plataforma Azure, configurando pontos de extremidade e criando um modelo preditivo.

## Sumário
- [1. Configuração da Conta no Azure](#1-configuração-da-conta-no-azure)
- [2. Criação do Ambiente de Trabalho no Azure Machine Learning](#2-criação-do-ambiente-de-trabalho-no-azure-machine-learning)
- [3. Desenvolvimento do Modelo Preditivo](#3-desenvolvimento-do-modelo-preditivo)
- [4. Configuração dos Pontos de Extremidade](#4-configuração-dos-pontos-de-extremidade)
- [5. Conclusão](#5-conclusão)

### 1. Configuração da Conta no Azure
- Criar uma conta no [Microsoft Azure](https://azure.microsoft.com/).
- Ativar o Azure Machine Learning Studio.
- Configurar permissões e cotas para o uso dos recursos de Machine Learning.

### 2. Criação do Ambiente de Trabalho no Azure Machine Learning
- Configurar uma nova instância de computação para treinar o modelo.
- Criar um novo Workspace e configurar os recursos necessários.

### 3. Desenvolvimento do Modelo Preditivo
- Carregar o conjunto de dados e realizar a preparação dos dados.
- Escolher um algoritmo de aprendizado de máquina adequado.
- Treinar o modelo no Azure Machine Learning Studio.
- Avaliar a performance do modelo usando métricas apropriadas (ex.: precisão, recall).

### 4. Configuração dos Pontos de Extremidade
- Configurar pontos de extremidade para disponibilizar o modelo via API.
- Salvar o arquivo de configuração JSON dos pontos de extremidade (detalhes no arquivo `endpoint_config.json`).

### 5. Conclusão
Este projeto oferece uma introdução prática à implementação de aprendizado de máquina na nuvem com o Azure. O uso dos pontos de extremidade permite acessar o modelo para previsões em tempo real e integrações com outras aplicações.

## Arquivos no Repositório
- `README.md`: Este arquivo com o passo a passo do desenvolvimento do projeto.
- `endpoint_config.json`: Arquivo com as configurações dos pontos de extremidade para acessar o modelo.
