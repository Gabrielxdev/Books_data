# 📚 Análise de Dados de Livros — Projeto em Python

Este projeto utiliza um conjunto de dados extraído do Kaggle, que fornece informações abrangentes sobre livros, como **ano de publicação**, **autores**, **idioma**, **gênero**, **avaliações dos leitores**, **preço**, **vendas** e outros atributos relevantes. O objetivo é explorar e visualizar os dados, buscando padrões e insights úteis sobre o mercado editorial.

---

## 🗂️ Sobre o Dataset

O conjunto de dados contém várias colunas-chave que descrevem diferentes aspectos dos livros:

- **Ano de Publicação**: Ano em que cada livro foi publicado. Essencial para analisar a distribuição temporal das publicações.
- **Nome do Livro**: Título único de cada obra.
- **Autor**: Nome(s) do(s) autor(es), permitindo analisar a influência de autores nas vendas e avaliações.
- **language_code**: Código de idioma do livro (ex: `en`, `pt`, `es`), útil para comparações por idioma.
- **Author_Rating**: Classificação do autor com base em seu histórico e reputação entre os leitores (ex: *Novice*, *Intermediate*, *Famous*, *Excellent*).
- **Book_average_rating**: Avaliação média recebida por cada livro.
- **Book_ratings_count**: Número total de avaliações feitas por leitores. Indica o grau de engajamento.
- **Gênero**: Categoria literária do livro (ex: romance, ficção científica, biografia).
- **Preço de venda**: Valor pelo qual o livro foi vendido ao consumidor.
- **Vendas brutas**: Receita total gerada pelas vendas dos livros.
- **Receita da editora**: Receita obtida diretamente pela editora.
- **Classificação de vendas**: Ranking numérico baseado no desempenho de vendas do livro.
- **Unidades vendidas**: Número de cópias vendidas por livro. É uma métrica direta de sucesso comercial.

---

## 🎯 Objetivos do Projeto

- Explorar o dataset com Python (Pandas, Seaborn, Matplotlib).
- Realizar análises estatísticas sobre autores, avaliações e desempenho de vendas.
- Visualizar correlações entre variáveis como preço, unidades vendidas e avaliações.
- Identificar padrões por gênero, idioma e período de publicação.
- Obter insights sobre os fatores que impulsionam o sucesso de um livro.

---

## 🛠️ Tecnologias Utilizadas

- Python 3
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Exemplos de Análises

- Boxplots por tipo de autor
- Gráficos de dispersão entre avaliação média e número de avaliações
- Agrupamentos por gênero e idioma
- Correlação entre preço, receita e unidades vendidas
