# 🛒 Análise Exploratória de Vendas - E-commerce (Olist)

Este projeto realiza uma análise de dados ponta a ponta (end-to-end) utilizando dados reais do e-commerce brasileiro (Olist). O objetivo é extrair, limpar e transformar os dados para gerar insights de negócio acionáveis utilizando Python e visualização de dados.

## 🎯 O Problema de Negócio
O projeto foi estruturado para responder a quatro perguntas fundamentais para a estratégia da empresa:
1. Qual é a evolução do faturamento mensal (Sazonalidade)?
2. Quais produtos sustentam a receita da empresa (Curva ABC / Regra de Pareto)?
3. Qual é o Ticket Médio por região geográfica?
4. Qual é a taxa de retenção dos clientes (Cohort Analysis)?

## 🛠️ Ferramentas e Tecnologias Utilizadas
* **Linguagem:** Python (Jupyter Notebook)
* **Manipulação e Limpeza de Dados:** Pandas, NumPy
* **Visualização de Dados:** Matplotlib, Seaborn, Tableau (para Dashboard Interativo)
* **Versionamento:** Git e GitHub

## 💡 Principais Insights Acionáveis

* **Sazonalidade Forte:** Identificamos um pico extremo de faturamento em Novembro de 2017, impulsionado pela Black Friday. **Recomendação:** Reforçar a logística e o abastecimento de estoque nos meses de Q4 para evitar ruptura.
* **Princípio de Pareto (Curva ABC):** Cerca de 18% do portfólio de produtos (Classe A) é responsável por gerar 80% de todo o faturamento da empresa. **Recomendação:** Focar o orçamento de marketing e garantir estoque ininterrupto para esses produtos *Top-Tier*.
* **Ticket Médio Geográfico:** Surpreendentemente, estados do Norte/Nordeste (ex: PB, AC, RO) possuem os maiores tickets médios. Isso ocorre possivelmente devido à compensação do alto custo de frete com compras de maior valor agregado.
* **Retenção (Cohort):** A taxa de recompra é historicamente baixa (~3%), comportamento típico de um marketplace de bens duráveis (compras pontuais). **Recomendação:** Mudar o foco de campanhas de retenção de longo prazo para estratégias de *Cross-sell* (venda cruzada) no exato momento da primeira compra.

## 🚀 Como executar o projeto localmente

1. Clone este repositório em sua máquina:
   ```bash
   git clone [https://github.com/vlbarbosa/analise-ecommerce-ads.git](https://github.com/vlbarbosa/analise-ecommerce-ads.git)
