# 🛒 Análise de Lucratividade no Varejo (E-commerce)

**Contexto do Projeto:** Este projeto analisa uma base de dados de transações de uma rede de varejo para identificar os gargalos de lucro. O objetivo principal foi compreender a razão pela qual o aumento do volume de vendas não se estava a refletir proporcionalmente no caixa da empresa, utilizando técnicas de Análise Exploratória de Dados (EDA).

---

## 🛠️ Ferramentas Utilizadas
* **Linguagem:** Python
* **Bibliotecas:** Pandas (Limpeza e Manipulação), Matplotlib e Seaborn (Visualização de Dados)
* **Ambiente:** Google Colab

---

## 🧹 Processo de Limpeza e Preparação de Dados (Data Cleaning)
A base de dados original (`Superstore Dataset`) continha inconsistências que foram tratadas antes da análise:
1. **Remoção de Linhas Nulas:** Eliminação de 806 linhas vazias ("fantasmas") resultantes de erros de exportação do sistema.
2. **Tratamento de Dados Faltantes:** Preenchimento de valores nulos na coluna de Códigos Postais (CEP).
3. **Conversão de Tipos:** Transformação das colunas de texto relativas a datas (`Order Date` e `Ship Date`) para o formato `datetime`, permitindo análises temporais.

---

## 💡 Principais Insights e Descobertas

* 🚨 **O Grande Gargalo Financeiro:** Ao analisar o lucro por sub-categoria, descobriu-se que o departamento de **Mesas (Tables)** é o maior ralo financeiro da empresa, gerando um prejuízo acumulado de mais de **US$ 17.700**.
* 🔍 **A Causa Raiz:** O cruzamento de dados provou que o prejuízo não se deve ao produto em si, mas sim à **política de descontos**. Enquanto a loja aplica uma média de 15,6% de desconto nos produtos em geral, a categoria de mesas sofre descontos agressivos que chegam a **26,1%**, corroendo completamente a margem de lucro.

---

## 📈 Recomendação de Negócios
Sugere-se à equipa de gestão uma **revisão imediata na política de precificação e descontos** do setor de mobiliário. Limitar promoções agressivas na categoria de Mesas estancará a perda de capital, permitindo que a receita gerada por essas vendas se converta em lucro real para a empresa.
