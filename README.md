# Previsão de Score de Crédito com Inteligência Artificial

Este projeto foi desenvolvido durante a Jornada Python da Hashtag Treinamentos. O objetivo é criar um modelo de Machine Learning capaz de analisar dados de clientes bancários e prever seu score de crédito entre: **Bom, OK ou Ruim**.

## Tecnologias Utilizadas
- **Python**: Linguagem principal.
- [cite_start]**Pandas**: Para manipulação e tratamento da base de dados.
- [cite_start]**Scikit-Learn**: Para a criação e treinamento dos modelos de IA.
  - [cite_start]Modelos utilizados: `RandomForestClassifier` (Árvore de Decisão) e `KNeighborsClassifier` (KNN).

## O Projeto
[cite_start]O case consiste em um banco com uma base de 100.000 clientes. Para que o modelo de IA pudesse aprender, foram realizadas as seguintes etapas:

1. [cite_start]**Tratamento de Dados**: Conversão de colunas de texto (como profissão e mix de crédito) em números utilizando o `LabelEncoder`.
2. [cite_start]**Divisão de Dados**: Separação da base em dados de treino e dados de teste.
3. [cite_start]**Treinamento de Modelos**: Aplicação dos algoritmos RandomForest e KNN para encontrar o de maior precisão[cite: 2].
4. [cite_start]**Previsão**: Utilização do melhor modelo para prever o score de novos clientes em uma base distinta.

## Resultados
[cite_start]O modelo escolhido foi o que apresentou a menor taxa de erro nos testes, permitindo ao banco automatizar a análise de crédito com segurança[cite: 2].
