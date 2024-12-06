
[Documentação em Português](#quantum-guard-streamlit--português)
[Documentation in English](#quantum-guard-streamlit--english)

# Quantum Guard Streamlit (Português)

# Guia para Rodar o Projeto Quantum Guard Localmente

Este guia fornece as instruções para configurar e executar o projeto **Quantum Guard**, uma aplicação baseada em Machine Learning Clássico e Quântico para classificação de transações financeiras.

---

## 1. **Pré-requisitos**

Certifique-se de ter o seguinte instalado:

- **Python 3.10**
- **Pipenv** (gerenciador de ambientes)
  - Instale o Pipenv, se ainda não tiver:
    ```bash
    pip install pipenv
    ```
---

## 2. **Clonar o Repositório** (Opcional)

Se o projeto estiver em um repositório Git, você pode cloná-lo usando:

git clone https://github.com/Weslley-Prado/quantum-guard-streamlit.git
cd quantum-guard-streamlit

## 3. **Criar e Ativar o Ambiente Virtual com Pipenv**
Dentro do diretório do projeto, inicialize o ambiente virtual e instale as dependências:


    pipenv install
    
Se houver um arquivo `Pipfile` previamente configurado, ele será usado automaticamente. Caso contrário, instale as bibliotecas manualmente:

    pipenv shell

## 4. **Estrutura de Diretórios Esperada**
Certifique-se de que os modelos `.pkl` estejam nos seguintes caminhos:

<PROJETO_BASE>/
├── infra/
│   ├── model_of_classical_machine_learning/
│   │   └── modelo_anti_fraude.pkl
│   └── model_of_quantum_machine_learning/
│       └── modelo_anti_fraude_quantum.pkl
└── app.py  # Nome do arquivo principal do projeto

## 5. **## **Executar a Aplicação**

Com o ambiente virtual ativado, inicie o aplicativo Streamlit:

    streamlit run app.py

Abra o navegador e acesse o endereço fornecido (geralmente, `http://localhost:8501`).

## 7. **Desenvolvedores**
  

 - **Autor:** Weslley Rosa Prado   
 -  **Orientador:** Prof. Dr. José Alexandre Nogueira    
 - **Instituição:** Universidade Federal do   Espírito Santo (UFES)

# Quantum Guard Streamlit (English)

# Guide to Running the Quantum Guard Project Locally

This guide provides instructions for setting up and running the Quantum Guard project, an application based on Classical and Quantum Machine Learning for classifying financial transactions.

---

## 1. **Prerequisites

Make sure you have the following installed:

- **Python 3.10**
- **Pipenv** (environment manager)
  - Install Pipenv if you don't already have it:
    ```bash
    pip install pipenv
    ```
---

## 2. **Clone the Repository** (Optional)

If the project is in a Git repository, you can clone it using:

git clone https://github.com/Weslley-Prado/quantum-guard-streamlit.git
cd quantum-guard-streamlit

## 3. **Create and Activate the Virtual Environment with Pipenv**
Inside the project directory, initialize the virtual environment and install the dependencies:


    pipenv install
    
If there is a previously configured `Pipfile`, it will be used automatically. Otherwise, install the libraries manually:

    pipenv shell

## 4. **Expected Directory Structure**
Make sure that the `.pkl` templates are in the following paths:

<BASE_PROJECT>/
├── infra/
│ ├── model_of_classical_machine_learning/
│ │ └── model_anti_fraud.pkl
│ └── model_of_quantum_machine_learning/
│ └── model_anti_fraud_quantum.pkl
└── app.py # Name of the main project file

## 5. Running the application

With the virtual environment activated, start the Streamlit application:

    streamlit run app

Translated with DeepL.com (free version)