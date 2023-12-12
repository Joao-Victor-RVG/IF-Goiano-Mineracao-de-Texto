# INSTITUTO FEDERAL GOIANO - BACHARELADO EM CIENCIAS DA COMPUTAÇÃO
<figure>

  <img src="logo IF-Goiano.png" alt="IF-Goiano logo">

---

<br>
  
Olá, seja bem-vindo ao meu repositório da disciplina de Metodos Computacionais Avançados em Mineração de Texto do curso de Bacharelado em Ciência da Computação no Instituto Federal Goiano. Abaixo, você verá tudo o que foi feito e estudado neste curso.
  

<br>

Hello, welcome to my repository of the discipline of Advanced Computational Methods in Text Mining of the Bachelor's Degree in Computer Science at Instituto Federal Goiano. Below, you will see everything that was done and studied in this course.


<br>

# :rocket: Sobre / About

O objetivo principal destas aulas é estudar técnicas de  Mineração de Texto.  Nesta disciplina vamos estudar conceitos sobre mineração de texto, processamento de linguagem natural, linguagem R, pré-processamento de texto, tokenização, análise de frequência, análise de sentimento, classificação de texto, agrupamentos, sumarização.

<br>

The main objective of these classes is to study Text Mining techniques. In this course we will study concepts about text mining, natural language processing, R language, text pre-processing, tokenization, frequency analysis, sentiment analysis, text classification, grouping, summarization.

<br>



# Colaboradores / Collaborators

  * [Aluno / Student (João Victor Rocha Vilela Godoi)](https://github.com/Joao-Victor-RVG)
  * [Aluno / Student (Pedro Paulo Soares Rabelo)](https://github.com/SwloBr)


<br>


## 🏫 Escola / School 

[IF-Goiano Website](https://ifgoiano.edu.br/home/index.php)
[YouTube Channel](https://www.youtube.com/user/ifgoiano)


## Documentação / Documentation

<br>

# Documentação do Projeto: Regulamentação dos Cassinos no Brasil

## Introdução

O projeto "Regulamentação dos Cassinos no Brasil" tem como objetivo analisar a opinião pública e dos parlamentares sobre a regulamentação dos cassinos no país. O histórico do tema remonta ao Decreto-Lei nº 9.215 de 30 de abril de 1946, que proibiu os jogos de azar no Brasil. Essa proibição teve impactos significativos na economia, mas ao longo dos anos, diferentes projetos de lei foram apresentados para discutir a regulamentação.

O foco deste projeto é o **Projeto de Lei nº 442/1991**, que aborda a regulamentação dos cassinos, bingos, jogos do bicho e jogos online. O processo legislativo desse projeto teve diferentes momentos ao longo dos anos, e o objetivo é entender a opinião popular sobre o tema.

## Técnicas Utilizadas

### 1. Extração de Dados

Os dados foram extraídos de uma enquete relacionada ao PL 442/1991 da Câmara dos Deputados. O arquivo CSV contendo os comentários foi processado para remover irregularidades e criar um conjunto de dados adequado para análise.

### 2. Pré-processamento de Texto

O pré-processamento dos textos foi realizado para limpar e estruturar os dados. Isso incluiu a tokenização, remoção de pontuações, números e stop words em língua portuguesa. O corpus resultante foi usado para análises posteriores.

### 3. Análise de Sentimento em Português

Foi realizada uma análise de sentimento utilizando o LexiconPT, um dicionário em português com polaridade de palavras. Além disso, um dicionário personalizado foi incorporado. As polaridades foram agregadas para avaliar o sentimento geral dos comentários em relação à regulamentação dos cassinos.

### 4. Modelagem de Tópicos (LDA)

A modelagem de tópicos foi aplicada usando o algoritmo Latent Dirichlet Allocation (LDA) para identificar tópicos presentes nos comentários. Isso ajudou a entender os temas predominantes nas opiniões sobre a regulamentação.

### 5. Tradução para Inglês

Para ampliar a compreensão global, os comentários foram traduzidos para o inglês usando a API de tradução. Isso permitiu uma visão mais ampla das opiniões, possibilitando uma análise comparativa entre as línguas.

### 6. Análise de Sentimento em Inglês

Assim como na análise em português, uma análise de sentimento foi realizada nos comentários traduzidos para o inglês, permitindo uma compreensão mais abrangente das opiniões.

### 7. Categorização e Visualização

Os resultados foram categorizados e visualizados por meio de gráficos de tópicos e termos mais frequentes, proporcionando insights visuais sobre os principais pontos discutidos nos comentários.

## Conclusão

Este projeto oferece uma visão abrangente da opinião pública sobre a regulamentação dos cassinos no Brasil. As técnicas de mineração de texto utilizadas forneceram insights valiosos sobre os sentimentos e tópicos predominantes nos comentários. Essas informações podem ser úteis para compreender as perspectivas da sociedade em relação ao tema e contribuir para futuras discussões legislativas.

