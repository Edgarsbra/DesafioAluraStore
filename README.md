# DesafioAluraStore
# 🛍️ Alura Store Brasil — Análise de Faturamento das Lojas

## 📘 Descrição
Este notebook foi desenvolvido no **Google Colab** como parte de um estudo de **análise de dados em Python**, com foco na comparação de **faturamento entre quatro lojas virtuais da Alura Store Brasil**.  
O objetivo é identificar qual loja apresenta melhor desempenho financeiro e entender a distribuição de faturamento por categoria de produtos.

---

## 🧠 Objetivos do Projeto
- Importar e integrar os dados de quatro lojas diferentes.  
- Calcular o **faturamento total** e **médio por categoria**.  
- Visualizar os resultados com **gráficos comparativos**.  
- Criar funções que automatizem a análise de novas bases.

---

## 🧩 Estrutura do Notebook
O notebook contém 23 células, sendo 16 de código e 7 de explicação (Markdown), organizadas nas seguintes etapas:

### 1️⃣ Importação das Bibliotecas
Essas bibliotecas são:
**pandas**: manipulação e análise de dados tabulares.
**matplotlib** e **seaborn**: criação de gráficos e visualizações estatísticas.


### 2️⃣ Importação dos Dados
Os dados das quatro lojas são importados diretamente do GitHub, usando o pandas.read_csv() para carregar os arquivos .csv.
As linhas com valores nulos são removidas.
### 3️⃣ Visualização Inicial
Exibe as primeiras linhas do DataFrame para inspecionar a estrutura das colunas e garantir que a leitura foi correta.

### 4️⃣ Cálculo do Faturamento Total por Loja
Cria-se um dicionário com os nomes das lojas e o faturamento total (soma dos preços) de cada uma.
Em seguida, o dicionário é convertido em um DataFrame pandas (dfanalise) para facilitar a visualização e a plotagem.

### 5️⃣ Visualização Gráfica do Faturamento
sse trecho cria um gráfico de barras comparando o faturamento das quatro lojas.
Cada loja é representada por uma cor diferente, permitindo uma análise visual rápida do desempenho.

### 6️⃣ Criação de Funções para Análise por Categoria
### 7️⃣ Aplicação das Funções às Quatro Lojas
### 8️⃣ Visualizações Complementares
Outras células usam seaborn e matplotlib para comparar graficamente:
Faturamento total por categoria;
Faturamento médio;
Distribuição de preços.
Essas análises permitem observar tendências e identificar quais categorias têm maior impacto no faturamento geral.

### 💡 Conclusões
É possível comparar facilmente o desempenho financeiro de todas as lojas.
As funções criadas facilitam a expansão do projeto para novas filiais ou períodos de tempo.
A análise gráfica ajuda a compreender padrões de consumo e categorias mais lucrativas.



