# 📊 Análise de Desempenho - Challenge Alura Store

## 📌 Sobre o Projeto
Este projeto consiste em uma análise exploratória de dados para avaliar o desempenho quatro filiais da empresa fictícia "Alura Store Brasil".

O **objetivo principal** dessa análise foi fornecer dados quantitativos para embasar a decisão estratégica de descontinuar uma das lojas da rede, identificando qual unidade possui o menor diferencial competitivo.

## 🗂️ Dados Analisados
O projeto processa dados de vendas de quatro arquivos CSV distintos (`loja_1`, `loja_2`, `loja_3`, `loja_4`). As principais métricas analisadas incluem:

* **Financeiro**: Faturamento total e preço dos produtos.
* **Logística**: Valor do frete e localização (latitude/longitude).
* **Comercial**: Volume de vendas por categoria (Móveis, Eletrônicos, Brinquedos, etc.).
* **Satisfação**: Avaliação média dos clientes.

## 🛠️ Tecnologias Utilizadas
O projeto foi desenvolvido em **Python** utilizando as seguintes bibliotecas:
* **Pandas**: Leitura, limpeza e manipulação dos DataFrames.
* **Matplotlib**: Criação de gráficos de barras e pizza para visualização de faturamento e mix de produtos.
* **Folium**: (Importado no código) Para visualização geoespacial das vendas.

## 🔎 Principais análises

### 1. Faturamento Total
* **Loja 1:** Líder em receita (aprox. R$ 1.53M),apesar de custos de frete mais altos.
* **Loja 2:** Segundo maior faturamento.
* **Loja 4:** Menor faturamento total, porém com alta eficiência operacional (menor frete).

### 2. Desempenho por Categoria
A análise detalhada do mix de produtos revelou que a **Loja 2** apresenta o menor volume de vendas nas categorias mais importantes para o negócio:
* **Móveis:** Vendeu apenas 442 unidades (vs. 499 da Loja 3).
* **Eletrônicos:** Pior desempenho da rede (422 unidades).
* **Brinquedos:** Pior desempenho da rede (313 unidades).

## 🎯 Conclusão e Recomendação
Com base nos dados processados, a recomendação final é **descontinuar a Loja 2**.

**Justificativa:**
A Loja 2 encontra-se em uma posição de "mediocridade". Diferente das outras unidades, ela não lidera em nenhum parâmetro fundamental:
* Não possui o maior faturamento (pertence à Loja 1).
* Não possui a melhor logística/frete (pertence à Loja 4).
* Não possui o maior volume de vendas ou satisfação (pertence à Loja 3).

Fechar a Loja 2 permite realocar recursos para fortalecer a eficiência da Loja 4 e a liderança das Lojas 1 e 3.

Desenvolvido como parte de uma análise estratégica de dados no Challenge Alura Store do Projeto Alura One.

## 🚀 Como Executar
Execute o notebook `AluraStoreBrasil.ipynb` em um ambiente Jupyter Notebook, VS Code ou Google Colab.
