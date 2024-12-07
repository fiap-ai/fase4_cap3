# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# Classificação de Grãos de Trigo usando Machine Learning

## Nome do grupo

## 👨‍🎓 Integrantes: 
- <a href="https://www.linkedin.com/in/gabemule/">Gabriel Mule Monteiro</a>

## 👩‍🏫 Professores:
### Tutor(a) 
- <a href="https://www.linkedin.com/company/inova-fusca">Lucas Gomes Moreira</a>


## 📜 Descrição

Este projeto tem como objetivo desenvolver um modelo de aprendizado de máquina para classificar variedades de grãos de trigo com base em suas características físicas. Utilizamos o conjunto de dados "Seeds Dataset" do UCI Machine Learning Repository, que contém medições de 210 amostras de grãos de trigo pertencentes a três variedades diferentes: Kama, Rosa e Canadian.

O projeto segue a metodologia CRISP-DM e inclui as seguintes etapas:
1. Análise exploratória de dados (EDA) com visualizações
2. Pré-processamento de dados, incluindo normalização
3. Implementação e comparação de diferentes algoritmos de classificação (KNN, SVM, Random Forest, Naive Bayes, Logistic Regression)
4. Otimização de modelos usando GridSearch
5. Interpretação dos resultados e extração de insights

O objetivo final é automatizar o processo de classificação de grãos de trigo, aumentando a eficiência e precisão em comparação com a classificação manual realizada por especialistas em cooperativas agrícolas de pequeno porte.


## 📁 Estrutura de pastas

Dentre os arquivos e pastas presentes na raiz do projeto, definem-se:

- <b>assets</b>: contém arquivos relacionados a elementos não-estruturados deste repositório, como imagens.

- <b>classificacao_graos_completo.ipynb</b>: notebook Jupyter contendo todo o código e análises do projeto.

- <b>seeds_dataset.txt</b>: arquivo de dados contendo o conjunto de dados "Seeds Dataset" utilizado no projeto.

- <b>requirements.txt</b>: arquivo que lista todas as dependências do projeto.

- <b>README.md</b>: arquivo que serve como guia e explicação geral sobre o projeto (o mesmo que você está lendo agora).

## 🔧 Como executar o código

Para executar o código deste projeto, siga os passos abaixo:

1. Clone este repositório
2. Crie um ambiente virtual: `python -m venv venv`
3. Ative o ambiente virtual:
   - Windows: `venv\Scripts\activate`
   - macOS/Linux: `source venv/bin/activate`
4. Instale as dependências: `pip install -r requirements.txt`
5. Abra o notebook `classificacao_graos_completo.ipynb` em um ambiente Jupyter
6. Execute as células sequencialmente para reproduzir a análise e os resultados

Certifique-se de ter o Python 3.8 ou superior instalado em sua máquina.


## 🗃 Histórico de lançamentos

* 0.1.0 - 25/05/2023
    * Implementação inicial do projeto
    * Análise exploratória de dados
    * Implementação e comparação de modelos de classificação
    * Otimização de modelos
    * Interpretação de resultados e conclusões

## 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/agodoi/template">MODELO GIT FIAP</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a> está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>
