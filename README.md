# 📦 Análise de Performance Comercial e Logística com Dados Reais de E-commerce (Olist)

Este projeto analisa um conjunto de dados reais do marketplace brasileiro Olist com foco em performance de vendas, comportamento dos clientes e eficiência logística. Utilizando Python e técnicas de estatística descritiva, o objetivo é extrair **insights acionáveis** que apoiem **decisões estratégicas em marketing, vendas e operações**.

---

## 🎯 Objetivos do Projeto

- Avaliar o desempenho de vendas por produto, categoria e região
- Analisar o comportamento dos clientes e seu impacto na receita
- Medir a eficiência logística com foco em prazos de entrega
- Identificar padrões e oportunidades de otimização comercial

---

## 📊 Base de Dados

**Fonte:** [Brazilian E-Commerce Public Dataset by Olist (Kaggle)](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)  
**Período:** 2016 a 2018  
**Volume:** +100 mil pedidos

### Tabelas principais utilizadas:
- `orders` — status e datas dos pedidos
- `order_items` — produtos incluídos nos pedidos
- `products` — descrição, categoria e dimensões dos produtos
- `customers` — localização dos clientes
- `sellers` — localização dos vendedores
- `order_reviews` — avaliações dos clientes
- `order_payments` — formas e valores de pagamento

---

## 🛠️ Ferramentas e Tecnologias

- **Linguagem:** Python 3.x
- **Bibliotecas:** pandas, numpy, matplotlib, seaborn, datetime
- **Ambiente:** Jupyter Notebook
- **Versionamento:** Git e GitHub

---

## 📈 Etapas do Projeto

### 1. Importação e Exploração dos Dados
- Leitura das tabelas
- Inspeção de estrutura, tipos e valores ausentes
- Entendimento relacional entre as tabelas

### 2. Limpeza e Pré-processamento
- Conversão de colunas de data
- Criação de métricas derivadas:
  - Tempo de entrega
  - Receita por item
  - Ticket médio por pedido
- Padronização de nomes de colunas

### 3. Análise Exploratória e Visualizações
- Top categorias por volume e por receita
- Faturamento mensal (análise temporal)
- Vendas por estado (heatmap geográfico)
- Curva ABC de produtos (80/20)
- Tempo médio de entrega vs avaliação média
- Ticket médio por categoria

### 4. Insights Estratégicos
- O Sudeste representa mais de 50% das vendas
- Atrasos logísticos impactam diretamente a nota dos pedidos
- Poucas categorias concentram a maior parte do faturamento
- O valor médio por pedido varia muito entre categorias

---

## 📌 Principais Indicadores Criados

| Indicador              | Descrição                                                                 |
|------------------------|---------------------------------------------------------------------------|
| Receita Total          | Soma dos valores pagos por pedido                                         |
| Ticket Médio           | Receita Total / Número de pedidos                                         |
| Tempo Médio de Entrega | Diferença entre a data de entrega e a data de compra                     |
| Score Médio            | Média das avaliações dos clientes por categoria ou estado                |
| Distribuição Geográfica| Quantidade de pedidos por estado                                          |

---

## 🗂️ Estrutura de Pastas

olist-sales-performance/ │ ├── data/ │ └── raw/ # Dados originais (.csv) │ ├── notebooks/ │ └── 01_analise_olist.ipynb # Notebook principal │ ├── imgs/ │ └── graficos/ # Gráficos salvos para README e LinkedIn │ ├── README.md ├── requirements.txt └── .gitignore


---

## 🚀 Próximos Passos

- Implementar visualizações interativas com Streamlit
- Construir dashboard final no Power BI como extensão
- Aplicar agrupamento de clientes (clustering simples)
- Criar uma versão em inglês do projeto

---

## 💡 Diferenciais do Projeto

- Base de dados **real**, brasileira e amplamente utilizada no mercado
- Aplicação de **estatística descritiva com propósito de negócio**
- **Conexão direta com áreas-chave**: vendas, logística, marketing e CX
- Estrutura modular, limpa e com boas práticas de projeto

---

## 👩‍💻 Autora

**Mayara Nascimento**  
📧 mayaranmartins@outlook.com  
📱 (11) 98010-3000  
🔗 [LinkedIn](https://www.linkedin.com/in/mayaranmartins)  

---

## ⭐️ Como contribuir ou dar feedback

- ⭐️ Dê uma estrela neste repositório se achou útil ou inspirador
- 🔄 Compartilhe este projeto com alguém da área de dados


