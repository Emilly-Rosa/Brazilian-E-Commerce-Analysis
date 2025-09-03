# 📊 Projeto de Análise de Dados – Brazilian E-Commerce (Olist)

## 📌 Objetivo

O objetivo deste projeto é explorar e analisar o **dataset público da Olist** (disponível no Kaggle) para responder a perguntas estratégicas sobre vendas, logística, clientes, pagamentos e satisfação.

As questões foram pensadas sob a perspectiva de um **stakeholder de negócios**, simulando um cenário real de análise de dados em e-commerce. Para isso, contei com o apoio do **ChatGPT (atuando como stakeholder)** na definição das perguntas, tornando o projeto mais próximo de uma experiência prática de mercado.

---

## 🔎 Perguntas de Negócio

### 📦 Vendas e Receita

1. Qual é o faturamento total da Olist no período disponível?
2. Como se distribui o ticket médio por pedido e por cliente único?
3. Quais são as categorias de produtos mais vendidas em volume e em receita?
4. O faturamento varia muito entre estados e cidades? Se sim, onde temos mais força?

### 🚚 Logística e Entregas

5. Qual é o tempo médio entre a compra e a entrega ao cliente?
6. Quantos pedidos foram entregues dentro do prazo estimado e quantos atrasaram?
7. Existe diferença significativa de prazo entre estados/regiões do Brasil?
8. Quais vendedores têm maior índice de atrasos na entrega?

### 👥 Clientes

9. Qual é a proporção de clientes recorrentes versus clientes únicos?
10. Em quais estados temos mais clientes ativos?
11. Existe algum perfil de cliente (cidade/estado) que compra em maior quantidade ou gasta mais?

### 💳 Pagamentos

12. Qual o método de pagamento mais usado (boleto, cartão, etc.)?
13. Qual é a média de parcelas escolhida pelos clientes?
14. Existe diferença no valor do pedido dependendo da forma de pagamento?

### ⭐ Satisfação do Cliente

15. Qual a média geral das notas de review?
16. Quais categorias de produto apresentam melhores e piores avaliações?
17. Existe relação entre atraso na entrega e nota do review?
18. Quais são os principais padrões nos comentários de review (positivos ou negativos)?

---

## 🗂️ Dataset

O dataset utilizado é o **Brazilian E-Commerce Public Dataset by Olist**, disponível no Kaggle.
Ele contém informações sobre:

* Pedidos, clientes e vendedores
* Localização geográfica
* Produtos e categorias
* Pagamentos e métodos de pagamento
* Entregas e prazos
* Avaliações e comentários de clientes

---

## ⚙️ Metodologia

Os seguintes passos foram realizados no **Google Colab**:

* 📥 Importação do dataset do Kaggle
* 🔍 Análise exploratória inicial (visão geral dos dados sujos e inconsistências)
* 🔗 Integração: junção das diferentes tabelas em uma única base consolidada
* 🧹 Tratamento de dados: exclusão de colunas não pertinentes, tratamento de valores nulos e conversão de colunas de datas


