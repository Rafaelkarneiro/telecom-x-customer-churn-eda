# 📊 Análise de Evasão de Clientes (Churn)
## 📌 Sobre o Projeto

Este projeto tem como objetivo analisar o problema de evasão de clientes (Churn) em uma empresa de serviços por assinatura.

A análise busca identificar padrões e fatores que influenciam o cancelamento de clientes, utilizando técnicas de:

- Limpeza e tratamento de dados

- Análise exploratória de dados (EDA)

- Visualização gráfica

- Geração de insights estratégicos

O resultado final é um relatório estruturado com conclusões e recomendações para redução da taxa de churn.

## 🎯 Objetivo

Identificar:

- Perfil dos clientes que cancelam o serviço

- Variáveis mais associadas ao churn

- Padrões comportamentais e contratuais

- Possíveis estratégias para retenção

## 🗂 Estrutura do Projeto

```text
📁 telecom-x-customer-churn-eda/
├── 📁 notebooks/
│   └── 📓 churn_analysis.ipynb # Notebook com análise completa e relatório final
├── 📄 README.md # Documentação do projeto
└── 📄 requirements.txt
```

## 🛠 Tecnologias Utilizadas

- Python 3.14

- Pandas

- Matplotlib

- Jupyter Notebook

## ⚙️ Instalação e Execução

Siga os passos abaixo para executar o projeto localmente.

---

### 1️⃣ Clone o repositório

```bash
git clone https://github.com/Rafaelkarneiro/telecom-x-customer-churn-eda.git
cd telecom-x-customer-churn-eda
```
### 2️⃣ Crie um ambiente virtual (recomendado)

Crie um ambiente isolado para evitar conflitos de dependências:

```bash
python -m venv venv
```
Ative o ambiente:

```bash
venv\Scripts\activate
```

### 3️⃣ Instale as dependências

```bash
pip install -r requirements.txt
```

### 4️⃣ Execute o Jupyter Notebook

Abra o arquivo:

📁 notebooks/churn_analysis.ipynb

Execute as células na ordem apresentada para reproduzir a análise completa.

### 📥 Fonte dos Dados

O dataset é carregado diretamente via URL dentro do notebook, não sendo necessário download manual.

## 🧹 Etapas da Análise

1. Importação dos dados

2. Limpeza e tratamento

3. Análise exploratória (EDA)

4. Visualização de padrões

5. Geração de insights

6. Recomendações estratégicas

## 📊 Principais Insights Encontrados

- Clientes com contrato mensal apresentam maior taxa de churn

- A evasão ocorre principalmente nos primeiros meses

- Clientes com mensalidade mais alta tendem a cancelar mais

- Método de pagamento influencia a probabilidade de churn

## 🚀 Possíveis Melhorias Futuras

- Implementação de modelo preditivo (Machine Learning)

- Criação de dashboard interativo (Power BI ou Streamlit)

- Deploy do modelo em API

- Testes A/B para estratégias de retenção

## ⚠️ Possíveis Problemas

- Valores ausentes no dataset original

- Colunas categóricas exigem transformação

- Conversão de tipos numéricos pode gerar erros se não tratada corretamente

## 👨‍💻 Autor

Rafael Campanin Carneiro