# Utilização de Técnicas de Machine Learning para Classificação de Clientes de Instituições Financeiras Quanto a Aprovação de Empréstimos

Este repositório contém o código e a documentação para o projeto de classificação de clientes de instituições financeiras quanto à aprovação de empréstimos utilizando técnicas de aprendizado supervisionado. O objetivo principal do projeto é desenvolver um modelo preciso e eficiente para classificar clientes, reduzindo os riscos de inadimplência e otimizando o processo de concessão de crédito.

## Descrição do Projeto

O projeto utiliza dados da competição "Nubank's Credit Risk Analysis Competition" de 2017, promovida pelo Nubank. A escolha desses dados proporciona uma base sólida e realista, alinhada com os padrões de excelência estabelecidos pela empresa.

## Metodologia

### Aquisição de Dados

Os dados foram adquiridos da competição "Nubank's Credit Risk Analysis Competition" de 2017. O conjunto de dados é constituído por 43 atributos, incluindo atributos categóricos e numéricos, alguns dos quais foram anonimizados para proteger a privacidade dos indivíduos.

### Análise Exploratória e Tratamento de Dados

O processo de análise exploratória de dados (EDA) ajudou na identificação de padrões, teste de hipóteses e formulação de conclusões. O tratamento de valores nulos e inconsistentes, a remoção de atributos irrelevantes e a imputação de valores ausentes contribuíram para a qualidade dos dados utilizados no modelo.

### Seleção de Características e Balanceamento de Dados

Foram utilizadas técnicas como o coeficiente de Pearson para selecionar características relevantes e diferentes métodos de balanceamento de dados, como RandomOverSampler, SMOTE e RandomUnderSampler, para lidar com o desbalanceamento das classes.

### Codificação de Atributos Categóricos e Padronização de Dados

Para a codificação dos atributos categóricos, foram utilizadas técnicas como LabelEncoder e OneHotEncoder. A padronização dos dados numéricos foi realizada utilizando MinMaxScaler, StandardScaler, RobustScaler e Normalizer.

### Tuning de Hiperparâmetros

A otimização dos hiperparâmetros foi realizada através da validação cruzada, ajustando o modelo para obter os melhores resultados possíveis no conjunto de teste.

## Resultados e Discussão

Os resultados obtidos demonstram que, apesar do desbalanceamento das classes, o modelo foi capaz de alcançar uma AUC de 0,74 e um recall razoável, indicando sua capacidade de identificar clientes inadimplentes com uma precisão aceitável. Esses resultados corroboram a hipótese investigada de que modelos de machine learning têm potencial para serem eficazes na análise de risco de crédito.

Esses resultados sustentam a hipótese de que a aplicação de técnicas de aprendizado supervisionado pode melhorar significativamente a precisão e a eficiência na classificação de clientes para aprovação de empréstimos. A utilização dessas técnicas mostrou-se eficaz na redução dos riscos de inadimplência e na otimização do processo de concessão de crédito.

Em conclusão, as decisões de projeto foram fundamentais para o sucesso do modelo, fornecendo uma estrutura sólida e utilizando dados de alta qualidade. O diagnóstico para a avaliação da hipótese investigada indica que os modelos de machine learning são promissores na análise de risco de crédito, embora haja espaço para melhorias futuras.
