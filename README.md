# Análise de Sentimentos em Reviews de Filmes

Este repositório contém a implementação do projeto de Análise de Sentimentos desenvolvido no âmbito da disciplina de Text Mining para Ciência de Dados, no ISCTE — Instituto Universitário de Lisboa.

O projeto aborda a tarefa de classificação de sentimentos em textos, aplicando diversas metodologias, desde abordagens baseadas em ferramentas prontas e léxicos até técnicas avançadas baseadas em aprendizagem automática e modelos de transformers.

## Estrutura dos Ficheiros

| Ficheiro        | Descrição |
|-----------------|-----------|
| `2.2.ipynb`      | Avaliação de ferramentas existentes de análise de sentimentos (`TextBlob` e `VADER`) sobre o dataset IMDB Reviews. Definição de uma baseline inicial. |
| `2.3.ipynb`      | Implementação de um classificador baseado no léxico `NRC EmoLex`, incluindo pré-processamento e tratamento de negação. |
| `2.4.ipynb`      | Treino de modelos de aprendizagem automática supervisionada (`Logistic Regression` + TF-IDF) com diferentes níveis de pré-processamento. |
| `2.5.ipynb`      | Aplicação de modelos baseados em transformers (`DistilBERT`): utilização de pipelines pré-treinados e realização de fine-tuning manual em PyTorch. |
| `2.6.ipynb`      | Utilização de modelos generativos para análise de sentimentos em português, incluindo avaliação de modelos multilingues e de zero-shot learning. |
| `clean_NCR.py`   | Script de limpeza do léxico `NRC EmoLex`, extraindo apenas as colunas necessárias (`word`, `positive`, `negative`) para utilização posterior no pipeline. |