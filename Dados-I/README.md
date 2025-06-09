# Trilha de Carreira em Dados: De Analista a Cientista

Bem-vindo à trilha de estudos para se desenvolver na área de dados, começando como Analista de Dados e avançando para Cientista de Dados! Este roadmap foi criado para orientar seus estudos e o desenvolvimento de habilidades essenciais.

---

## Habilidades Essenciais

### 1. Ferramentas de Produtividade e Visualização Inicial

#### Excel / Google Sheets
- Principais funções: `PROCV`, `SE`, `CONT.SE`, `SOMASE`, `CONCAT`, `SE`
- Criação e trabalho com tabelas dinâmicas (agrupamentos e filtros), incluindo contagem distinta
- Cálculo de medidas de resumo (média, mediana, quartis, mínimo, máximo) utilizando funções integradas
- Criação básica de gráficos (Gráficos de Barras e Linhas são muito comuns)

### 2. Banco de Dados e SQL

- Entendimento de Banco de Dados Relacionais
- Tipos de dados comuns: `INT`, `VARCHAR`, `DATE`, `FLOAT`, `BOOLEAN`

#### SQL Básico
- Comandos de consulta essenciais: `SELECT`, `FROM`, `WHERE`, `GROUP BY`, `ORDER BY`, `JOIN`
- Cláusulas `WHERE` e `HAVING`
- Cláusulas de condição: `AND`, `OR`, `NOT`
- Filtros avançados: `BETWEEN`, `IN`, `LIKE`
- Funções de condição: `CASE`, `IF`
- Funções de string: `CONCAT`, `SUBSTRING`, `TRIM`, `REPLACE`
- Funções de agregação: `COUNT`, `SUM`, `AVG`, `MIN`, `MAX` (frequentemente usadas com `GROUP BY`)
- Tipos de `JOIN`: `INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`, `FULL OUTER JOIN`

#### SQL Avançado
- Funções de janela: `ROW_NUMBER`, `RANK`, `DENSE_RANK`
- Criação de `views` e `stored procedures`
- Criação de `CTEs` (Common Table Expressions)
- Conceitos de Álgebra Relacional: `join`, `group by`, `order by` e outros
- Chaves primárias, secundárias e estrangeiras
- Cálculo de estatísticas descritivas (como mediana e quartis) utilizando SQL, mesmo em engines que não possuem funções diretas para isso. Ferramentas como Spark SQL possuem funções específicas para mediana e percentis.

Para SQL uma forte recomendação é a seguinte trilha:
- [Desafio SQL leetcode](https://leetcode.com/studyplan/top-sql-50/): Ótimo para praticar e ver exemplos reais
- [Curso SQL 6 horas - Udemy](https://www.udemy.com/course/sql-para-analise-de-dados/): Recomendo irem entrando de tempos em tempos e pegarem quando ficar 24 reais rs

### 3. Estatística e Probabilidade

- Estatística Básica: Fundamento crucial para a área de dados
  - Entender População e Amostra (amostragem aleatória, separação de bases para treino e teste em Machine Learning)
  - Estatística como forma de sumarizar e resumir características de um conjunto de dados
  - Tipos de Variáveis: Qualitativas (Nominal, Ordinal) e Quantitativas (Discreta, Contínua)
  - Tabelas de Frequência: Frequência Absoluta, Relativa, Acumulada e Relativa Acumulada (pode ser calculada em Excel/Sheets, Python/Pandas ou SQL)
  - Medidas de Posição (Estatísticas Descritivas):
    - Somatório (Sigma Σ)
    - Média
    - Mediana
    - Quartis (Q1, Q3) e Intervalo Interquartílico
    - Mínimo e Máximo
    - Moda
  - Medidas de Dispersão: Variância, Desvio Padrão
  - Distribuições de Probabilidade: Normal, Bernoulli, Binomial, Uniforme, Poisson, Geométrica
  - Probabilidade: cálculo experimental, teórico ou Bayesiano
  - Intervalo de Confiança
  - Testes de Hipóteses

### 4. Programação para Análise de Dados

- Python (preferencialmente) ou R
  - Fluência na sintaxe básica
  - Métodos e pacotes para leitura e escrita de dados (uso de Pandas em Python)
  - Cálculo de estatísticas (frequência, medidas de posição, etc.) com Pandas, SciPy, Statsmodels
  - Visualização de dados usando bibliotecas de gráficos em Python

- [Desafio Pandas Leetcode](https://leetcode.com/studyplan/30-days-of-pandas/): Ótimo para praticar e ver exemplos reais

---

## Habilidades para Cientista de Dados (Avançando na Trilha)

### Estatística e Probabilidade Avançada
- Função densidade de probabilidade e distribuição acumulada
- Testes de hipóteses avançados (para variância, ANOVA)
- Erros do Tipo I e Tipo II
- Inferência Bayesiana

### Álgebra Linear
- Matrizes e vetores
- Álgebra matricial
- Distâncias e produto interno (essenciais para algoritmos de Machine Learning)

### Data Preparation (Preparação de Dados)
- Tratamento de valores ausentes (missings)
- Tratamento de outliers
- Categorização de variáveis contínuas e discretas
- Análise de Componentes Principais (PCA)
- Análise de correlação/associação entre diferentes tipos de dados
- Seleção de variáveis

### Machine Learning
- Modelos de Classificação: Árvore de classificação, Random Forest, Boosting (Gradient, ADA), Regressão logística, KNN, Naive Bayes, Redes neurais, SVM
- Modelos de Regressão: Regressão linear, Regularização (L1, L2), Árvore de regressão, Análise de resíduos, GLM
- Modelos de Agrupamento (Clusterização): K-means, K-medoids, DBSCAN, Algoritmos hierárquicos, Gaussian Mixture Models (GMM)
- Estratégias para definição do número de clusters: elbow, silhueta, distância intra-cluster, etc.
- Principais pacotes: Scikit-learn (Python), caret, mlr (R), TensorFlow, Keras, PyTorch

### Avaliação de Modelos
- Métricas: KS, Gini, AUC, RMSE, MAE, F1, Recall, Precision, R2
- Validações cruzadas e temporais: holdout, leave one out, k-fold, out of sample, out of time

### Visualização de Dados Avançada
- Propósito e aplicação de diferentes tipos de gráficos (Barras, Linha, Histograma, Box Plot)
- Identificação de outliers (Box Plot)
- Foco em visualizações que agreguem valor e facilitem a tomada de decisão

### Processamento de Linguagem Natural (NLP)
- Representação de Texto: Bag of Words, TF-IDF
- Modelagem de Texto: Modelagem de Tópicos, Análise de Sentimentos, Classificação de Texto
- Ferramentas: NLTK, Gensim

### Sistemas Distribuídos e Big Data
- Processamento em tempo real (Logs, Sensores, Redes Sociais)
- Componentes do Spark: Spark SQL, Spark Streaming, MLlib, GraphX, Spark Core
- Outras ferramentas: Hadoop, Hive, Databricks

### Pesquisa Operacional e Modelagem
- Ferramentas para otimização: PuLP, scipy.optimize, Excel Solver, Gurobi, CPLEX
- Integração com Machine Learning para decisões automatizadas

### Metodologia de Projetos de Dados
- Metodologia CRISP-DM: Entendimento do Negócio, Entendimento dos Dados, Preparação dos Dados, Modelagem, Avaliação, Implantação

---

## 5. Deploy de Modelos

- **Conceitos de Deploy:** O que é deploy de modelos? Diferença entre prototipagem e produção.
- **Serialização de Modelos:** Como salvar e carregar modelos treinados (pickle, joblib, ONNX).
- **APIs para Modelos:** 
  - Criação de APIs com Flask, FastAPI ou Django para servir modelos.
  - Testes de endpoints.
- **Containers:** 
  - Docker para empacotar aplicações de Machine Learning.
  - Noções de Dockerfile e docker-compose.
- **Orquestração e Escalabilidade:** 
  - Introdução ao Kubernetes.
  - Serviços gerenciados (AWS SageMaker, Google AI Platform, Azure ML).
- **Monitoramento de Modelos:** 
  - Monitoramento de performance e dados em produção.
  - Ferramentas como MLflow, Prometheus, Grafana.
- **Versionamento de Modelos:** 
  - DVC, MLflow, Git para versionamento de código e modelos.
- **Documentação e Boas Práticas:** 
  - Swagger/OpenAPI para documentação de APIs.
  - Logs, testes automatizados e CI/CD para modelos.

---

## Recursos Sugeridos

### Plataformas de Aprendizado e Prática
- [Kaggle](https://www.kaggle.com/): Ótimo para praticar e ver exemplos reais
- Comunidade online: Participar de comunidades para tirar dúvidas e trocar ideias

### Cursos e Documentação
- Curso Básico de Estatística: Focado nos conceitos fundamentais e aplicação prática em Sheets, Python e SQL
- [Curso de SQL - W3Schools](https://www.w3schools.com/sql/): Para aprender e praticar SQL
- Documentação oficial de bibliotecas e frameworks: Scikit-learn, TensorFlow, Keras, PyTorch, NLTK, Gensim, Apache Spark, Apache Hadoop, Apache Hive
- [Documentação Flask](https://flask.palletsprojects.com/)
- [Documentação FastAPI](https://fastapi.tiangolo.com/)
- [Documentação Docker](https://docs.docker.com/)
- [MLflow](https://mlflow.org/)

### Livros
- [Mãos à Obra: Aprendizado de Máquina com Scikit-Learn & TensorFlow](https://www.amazon.com.br/M%C3%A3os-Obra-Aprendizado-Scikit-Learn-TensorFlow/dp/8550803812): Tem os principais fundamentos de aprendizado de máquina
- [Python para Análise de Dados - Wes McKinney](https://wesmckinney.com/book/): Essencial para aprender a manipular dados com Python/Pandas
- Introduction to Operations Research - Frederick S. Hillier e Gerald J. Lieberman
- [Estatística Básica](https://www.amazon.com.br/Estatistica-Basica-10%C2%AA-edi%C3%A7%C3%A3o-2024-ebook/dp/B0CW1LHHD3): Fundamentos de estatística
- [Noções de Probabilidade](https://www.ime.usp.br/~noproest/doku.php?id=principal): Fundamentos de Probabilidade
- Livros sobre Machine Learning (ex: Machine Learning: Guia de Referência Rápida - Matt Harrison, Mãos à Obra: Aprendizado de Máquina com Scikit-Learn, Keras e TensorFlow - Aurélien Géron)

---

Siga essa trilha de forma iterativa, pratique bastante em diferentes tecnologias (Excel, SQL, Python), e compartilhe seus projetos! Não desista se algo parecer complexo inicialmente; o aprendizado é progressivo.