# Previsão de Score de Crédito com Inteligência Artificial

Este projeto foi desenvolvido durante a Jornada Python da Hashtag Treinamentos. O objetivo é criar um modelo de Machine Learning capaz de analisar dados de clientes bancários e prever seu score de crédito entre: **Bom, OK ou Ruim**.

## Tecnologias Utilizadas
- **Python**: Linguagem principal.
- **Pandas**: Para manipulação e tratamento da base de dados.
- **Scikit-Learn**: Para a criação e treinamento dos modelos de IA.
- [Modelos utilizados: `RandomForestClassifier` (Árvore de Decisão) e `KNeighborsClassifier` (KNN).

## O Projeto
O case consiste em um banco com uma base de 100.000 clientes. Para que o modelo de IA pudesse aprender, foram realizadas as seguintes etapas:

1. **Tratamento de Dados**: Conversão de colunas de texto (como profissão e mix de crédito) em números utilizando o `LabelEncoder`.
2. **Divisão de Dados**: Separação da base em dados de treino e dados de teste.
3. **Treinamento de Modelos**: Aplicação dos algoritmos RandomForest e KNN para encontrar o de maior precisão[cite: 2].
4. **Previsão**: Utilização do melhor modelo para prever o score de novos clientes em uma base distinta.

## Resultados
O modelo escolhido foi o que apresentou a menor taxa de erro nos testes, permitindo ao banco automatizar a análise de crédito com segurança[cite: 2].
