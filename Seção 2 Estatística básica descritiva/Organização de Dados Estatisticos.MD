# 📊 Organização de Dados Estatísticos

---

## 📌 Organizando Dados Discretos

É muito comum organizarmos uma grande quantidade de dados na forma de uma **tabela de frequência**.

> 🧠 **Por quê?**  
> Porque esse tipo de tabela nos permite visualizar melhor a distribuição dos dados e facilita o cálculo de medidas como média, mediana, desvio padrão, entre outras.

---

### 🧮 Exemplo prático:

Suponha a seguinte amostra com **30 dados**:

1, 1, 2, 2, 2, 3, 3, 4, 4, 4,
5, 5, 5, 6, 6, 6, 6, 7, 7, 7,
7, 7, 8, 8, 8, 9, 9, 9, 9, 9


Podemos organizar esses dados em uma **tabela de frequências**:

| Valor (Xi) | Frequência (Fi) |
|------------|-----------------|
| 1          | 2               |
| 2          | 3               |
| 3          | 2               |
| 4          | 3               |
| 5          | 3               |
| 6          | 4               |
| 7          | 5               |
| 8          | 3               |
| 9          | 5               |
| **Total**  | **30**          |

> ✳️ **Nota:**  
> - `Xi`: Cada valor distinto da variável.  
> - `Fi`: Frequência com que o valor aparece na amostra.

📊 Um **gráfico de barras** pode ser usado para visualizar melhor essa distribuição!

---

## 📊 Tabela de Frequência com Intervalo de Classe

> 🔍 Usada para dados **contínuos** ou quando temos uma **amostra grande**, facilitando a organização e a interpretação.

---

### 🧮 Exemplo prático:

Um proprietário de supermercado deseja analisar a quantidade de clientes entre **10h e 12h** ao longo de **30 dias**. Eis os dados coletados:

30, 37, 18, 15, 48, 23, 28, 24, 23, 19,
16, 35, 24, 18, 24, 44, 33, 54, 31, 39,
41, 38, 24, 32, 15, 16, 13, 11, 46, 40


Organizando os dados com **intervalos de classe de amplitude 10**:

| Nº de Clientes | Contagem | Frequência |
|----------------|----------|------------|
| 10 a 19        | 9        | ▓▓▓▓▓▓▓▓▓   |
| 20 a 29        | 7        | ▓▓▓▓▓▓▓     |
| 30 a 39        | 8        | ▓▓▓▓▓▓▓▓    |
| 40 a 49        | 5        | ▓▓▓▓▓       |
| 50 a 59        | 1        | ▓           |
| **Total**      | **30**   |            |

📊 Também é possível construir um **histograma** ou um gráfico de barras para melhor visualização.

---

## 🌿 Diagrama de Caule e Folha (Stem-and-Leaf)

> 📌 Ideal para **conjuntos de dados pequenos**, pois permite **visualizar os valores individuais** e suas frequências ao mesmo tempo.

- Mostra cada valor da amostra.
- Útil para comparações visuais.
- **Desvantagem:** trabalhoso para conjuntos grandes.

---

### 🧮 Exemplo prático:

Suponha os seguintes dados:

1, 1, 2, 2, 3, 4, 4, 4, 4, 5, 8,
10, 10, 10, 11, 11, 13, 17, 18,
25, 25, 27, 27, 28, 28, 29, 29,
30, 31, 31, 31, 32, 32, 32, 34, 35,
40, 44, 48, 49, 52, 56, 57, 57, 58, 63, 66


#### 🌱 Caule e Folha:

| Caule | Folha             |
|-------|-------------------|
| 0     | 1, 1, 2, 2, 3, 4, 4, 4, 4, 5, 8 |
| 1     | 0, 0, 0, 1, 1, 3, 7, 8         |
| 2     | 5, 5, 7, 7, 8, 8, 9, 9         |
| 3     | 0, 1, 1, 1, 2, 2, 2, 4, 5      |
| 4     | 0, 4, 8, 9                     |
| 5     | 2, 6, 7, 7, 8                  |
| 6     | 3, 6                           |

> 🧾 **Legenda:**  
> `6 | 3` significa **63**

---

## ✅ Considerações Finais

- Tabelas e diagramas são ferramentas fundamentais para **organizar dados brutos**.
- A forma como os dados são apresentados impacta diretamente a **análise estatística**.
- Sempre **escolha a técnica mais apropriada** para o tipo e o volume dos seus dados.

> 📌 **Dica:** Use ferramentas como **Excel**, **Python (pandas, matplotlib)** ou **R** para automatizar a construção de tabelas e gráficos.
