
# 📊 Análise Exploratória de Filmes da Netflix dos Anos 1990

Este projeto faz parte de uma atividade prática do [DataCamp](https://www.datacamp.com/), onde o objetivo é aplicar técnicas de análise exploratória de dados usando Python para explorar filmes da década de 1990 na plataforma Netflix.

---

## 🎯 Objetivos do Projeto

1. **Descobrir qual foi a duração de filme mais comum nos anos 1990.**
2. **Contar quantos filmes de ação curtos (menos de 90 minutos) foram lançados nessa década.**
3. **Visualizar os dados com gráficos para enriquecer a análise.**

---

## 🧰 Ferramentas Utilizadas

- **Linguagem:** Python  
- **Bibliotecas:** `pandas`, `matplotlib`, `seaborn`  
- **Ambiente:** Google Colab

---

## 📁 Dataset

- **Arquivo:** `netflix_data.csv`
- **Descrição:** Conjunto de dados com informações sobre filmes e séries da Netflix, incluindo:
  - `title`: título
  - `type`: tipo (filme ou série)
  - `genre`: gênero
  - `release_year`: ano de lançamento
  - `duration`: duração (ex: "90 min")
  - e outras colunas como elenco, país, diretor, etc.

---

## 📌 Resultados

### 🕒 Duração Mais Frequente nos Anos 1990

Foi calculada a **moda** das durações dos filmes da década de 90.  
Um gráfico de histograma foi gerado para visualizar a distribuição.

> 🎬 **Duração mais frequente:** `XX` minutos

### 🔫 Filmes Curtos de Ação

Considerando filmes com menos de 90 minutos como "curtos", foi feita uma contagem dos filmes de ação curtos entre 1990 e 1999.

> 📽️ **Quantidade de filmes de ação curtos nos anos 90:** `YY`

---

## 📊 Visualizações

- **Histograma** com a distribuição de duração dos filmes.
- **Gráfico de pizza** com a proporção de filmes de ação curtos vs. não curtos.

---

## 🚀 Como Executar

1. Faça o upload do arquivo `netflix_data.csv` no seu ambiente.
2. Execute o notebook `netflix_analysis.ipynb` no Google Colab.
3. Veja os resultados no console e nos gráficos.

---

## 📌 Observação

Este projeto foi feito com fins educacionais para praticar análise de dados e visualização com Python.
