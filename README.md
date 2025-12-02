|Faculdade |Curso|Disciplina |Professor|Ano|
| :- | :- | :- | :- | :- |
|Estácio de São Paulo|ADS|Tópicos de Big Data em Python|Prof. Fabio Oliveira|2025|

## 📝 Análise de Dados

Python, com suas poderosas bibliotecas e frameworks, oferece uma solução robusta para lidar com Big Data de forma eficiente. Lidar com volumes tão grandes de dados exige mais do que apenas a capacidade de armazenar e recuperar dados. São necessárias técnicas avançadas para processar, analisar e interpretar esses dados de forma significativa.

Saiba mais sobre Tópicos de Big Data em Python clicando [aqui](https://medium.com/@etimfonime/handling-big-data-with-python-ee3e15cb981e)

![chatbot](unnamed.png)

# 🎬 Projeto Extensionista: Análise de Dados de Filmes com Big Data em Python

## Resumo
- Notebook principal: app_V2.ipynb
- Base de dados: filmes.xlsx
- Imagem ilustrativa: unnamed.png

## 📚 Descrição

Este projeto tem como objetivo realizar uma análise exploratória de dados (EDA) sobre o mercado cinematográfico, utilizando Python e suas principais bibliotecas para Big Data. A partir de um dataset real de filmes, são extraídos insights estratégicos para decisões de investimento, avaliação de risco e otimização de portfólio no setor audiovisual.

## 🚩 Principais Funcionalidades

- Padronização de colunas e limpeza de colunas financeiras.
- Função explode_genres(df) para separar múltiplos gêneros por linha.
- Criação da coluna profit_margin: (gross_world_wide - budget) / gross_world_wide.
- Transformações logarítmicas em gross_* para análise de correlação.
- Remoção de outliers anuais utilizados na série temporal (anos removidos: 2006 e 2024).
- Gráficos principais: heatmap de correlação, scatter/log-regression, boxplot (Oscar), contagem de gêneros (top 10) e série temporal Orçamento vs Bilheteria (últimos 10 anos).

## 📦 Tecnologias Utilizadas

- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn
- openpyxl (leitura do Excel)
- Jupyter Notebook / JupyterLab

## 🚀 Como Começar

### Pré-requisitos

- Python 3.7 ou superior
- Jupyter Notebook
- pip (gerenciador de pacotes Python)
- Git (opcional)

### 🔧 Instalação

1. Clone o repositório:

    ```bash
    git clone https://github.com/dlepinski/Projeto-Extensionista-Big-Data.git
    cd Projeto-Extensionista-Big-Data
    ```

2. Instale o Jupyter Notebook (caso não tenha):

    ```bash
    pip install notebook
    ```
    ou, via Anaconda:
    ```bash
    conda install -c conda-forge notebook
    ```

3. Instale as dependências do projeto:

    ```bash
    pip install pandas numpy matplotlib seaborn openpyxl
    ```

## Como executar

1. Colocar filmes.xlsx na mesma pasta do notebook.
2. Abrir app_V2.ipynb no Jupyter Notebook/JupyterLab.
3. Executar as células na ordem (seções comentadas: Limpeza → Engenharia de Atributos → EDA → Visualizações).


## 🗂️ Estrutura do Projeto

```
Projeto-Extensionista-Big-Data/
│
├── app_V2.ipynb           # Notebook principal atualizado
├── filmes.xlsx            # Base de dados dos filmes (IMDb)
├── unnamed.png            # Imagem ilustrativa
├── README.md              # Este arquivo
└── ...
```

## 🤝 Como Contribuir

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/SuaFeature`)
3. Commit suas alterações (`git commit -m 'Minha contribuição'`)
4. Faça push para a branch (`git push origin feature/SuaFeature`)
5. Abra um Pull Request

## 👥 Equipe

- Daniela - Gerente de Projeto
- Sandra - Desenvolvedora 
- Gilberto - Analista de negócios
- Eloy - Analista de Requisitos

## 📞 Suporte

- [Abra uma Issue](https://github.com/dlepinski/Projeto-Extensionista-Big-Data/issues)

## 🔗 Links Úteis

- [Jupyter Notebook](https://jupyter.org/)
- [Artigo: Handling Big Data with Python](https://medium.com/@etimfonime/handling-big-data-with-python-ee3e15cb981e)

---

> Projeto desenvolvido para a disciplina de Tópicos de Big Data em Python — Estácio de São Paulo - 2025.