# Datathon

Este projeto foi desenvolvido para o Datathon by Globo.com, FIAP pós Tech. O objetivo é desenvolver um modelo de sistema de recomendação personalizada para cada usuário com base nos dados de notícias do G1, predizendo qual será a próxima notícia que ele vai ler. 
O Modelo deve considerar o cold-start e o conceito de recência.

#### 🚀 Visão Geral 

Este projeto consiste em uma aplicação que processa dados de usuários e gera recomendações baseadas em seu comportamento. A aplicação é composta por uma API desenvolvida em Python utilizando FastAPI, além de notebooks Jupyter para análise de dados e geração de insights.

# Análise de Dados e Geração de Insights

Este notebook Jupyter (`notebook.ipynb`) contém a análise de dados e a geração de insights para o Datathon.

## Visão Geral

O notebook realiza a análise exploratória dos dados de usuários, identifica padrões de comportamento e gera recomendações personalizadas. Utilizando bibliotecas como Pandas, NumPy, Matplotlib e Scikit-learn.

## Estrutura do Notebook

1. **Importação de Bibliotecas**: Importa todas as bibliotecas necessárias para a análise.
2. **Carregamento dos Dados**: Carrega os dados de entrada a partir de arquivos CSV.
3. **Análise Exploratória de Dados (EDA)**: Realiza a análise exploratória dos dados para entender melhor as características e padrões.
4. **Pré-processamento dos Dados**: Limpa e transforma os dados para prepará-los para a modelagem.
5. **Modelagem**: Aplica algoritmos de machine learning para gerar recomendações.
6. **Avaliação do Modelo**: Avalia a performance dos modelos utilizando métricas apropriadas.
7. **Geração de Insights**: Gera insights a partir dos resultados obtidos.


 #### 📋 Dependências 

As dependências do projeto estão listadas no arquivo [api/requirements.txt](api/requirements.txt). Para instalar as dependências, execute:

````sh
pip install -r api/requirements.txt
````

## Recursos
* API: A API foi desenvolvida utilizando FastAPI e está localizada na pasta api/app.
  * Roteadores:
    * health_check.py: Verificação de saúde da API.
    * recommendation.py: Geração de recomendações.
    * root.py: Rota raiz da API.
  * Modelos Pydantic: Definições de modelos de dados utilizando Pydantic, localizados em models.py.



### Requisições
Verificação de Saúde
``
GET /health
``

Geração de Recomendações
``
POST /recommendation
``

### Parâmetros:

**userId:** ID do usuário para o qual as recomendações serão geradas.

### Resumo
Este projeto foi desenvolvido para o Datathon, com o objetivo de analisar dados de usuários e gerar recomendações personalizadas. A aplicação utiliza FastAPI para a criação da API e Jupyter Notebook para a análise de dados. As dependências necessárias estão listadas no arquivo requirements.txt e podem ser instaladas utilizando pip.


#### ✒️ Autores

Isabelli Andrade de Souza - https://github.com/Isabellitankian
Lucas Souza Andrade dos Santos - https://github.com/LSouzaAndrade
Michel de Lima Maia - https://github.com/Michel-Maia
Valquiria Rodrigues de Oliveira Pires - https://github.com/KyraPires


