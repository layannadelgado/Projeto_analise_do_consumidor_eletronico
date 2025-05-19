# 📊 Análise de Clientes por Segmento 
Este projeto foi desenvolvido com base no dataset:
[Ecommerce Consumer Behavior Analysis Data](https://www.kaggle.com/datasets/salahuddinahmedshuvo/ecommerce-consumer-behavior-analysis-data) disponível no Kaggle.

O objetivo é analisar o comportamento de compra dos clientes e gerar insights de vendas por **segmento**, utilizando **Python (Google Colab)** para o 
tratamento de dados e **Power BI** para criação de dashboards interativos.

## 🧾 KPIs Analisados

1.Qual o valor médio gasto por cliente em cada segmento?
2.Qual o faturamento total gerado por cada segmento de clientes?
3.Quais são as categorias de produtos mais adquiridos em cada segmento?
4.Qual o percentual de cancelamentos em cada segmento?
5.Qual o nível de satisfação dos clientes (NPS)?
6.Como cada segmento evoluiu em receita e desempenho ao longo do ano?
7.Qual o faturamento distribuído entre os diferentes gêneros dos clientes?


## 🏷️ Definição dos Segmentos
**Segmento**	   **Valor Mínimo**	  **Frequência Mínima**	   **Características**
💎 Diamante     	 R$ 450+	           8+ compras	            Clientes premium 
🥇 Ouro	           R$ 350+	           6+ compras	            Clientes frequentes 
🥈 Prata	         R$ 250+	           4+ compras	            Clientes regulares 
🥉 Bronze	         R$ 150+	           2+ compras	            Clientes iniciais/ocasionais
⚪ Sem Catategoria    -                   -                   Novos ou baixo engajamento



## ⚙️ Etapas do Projeto

### 🔍 Tratamento de Dados – Google Colab
- Limpeza e organização dos dados
- Criação da coluna Segmento com base no valor/frequência
- Visualização de outliers com boxplot
- Exportação do dataset tratado para uso no Power BI

### 📈 Análise Estatística – Power BI (DAX)
- Cálculo de métricas: média, mediana, desvio padrão
- Verificação de outliers por desvio padrão (nenhum identificado)
- Criação de medidas com DAX, incluindo:
- Receita total
- Ticket médio
- Taxa de cancelamento
- Receita por gênero

### 📊 Visualização – Power BI
Criação de dashboard interativo com:
- Gráficos de barras, pizza, linhas e cartões
- Filtros por segmento, gênero, cancelamento e período
- Destaques visuais para insights relevantes
    
## 🛠️ Ferramentas Utilizadas
- Python (Google Colab)
- Pandas, Numpy, Seaborn
- Power BI Desktop
- Linguagem DAX




