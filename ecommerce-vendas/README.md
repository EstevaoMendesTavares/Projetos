# 📊 Estudo de Caso: Dashboard de Vendas E-commerce

Este projeto foca na análise de vendas e comportamento do cliente para uma empresa fictícia de e-commerce, com o objetivo de identificar fatores de queda de receita e otimizar estratégias de fidelização.

---

## 🎯 Desafio de Negócios

> **Objetivo:** Estabelecer o contexto e a relevância da análise.
>
> * A empresa de e-commerce enfrentava uma **queda de vendas atípica** a partir de abril, dificultando o planejamento de estoque e campanhas de marketing.
> * O desafio era **transformar os dados brutos** de transações e clientes em métricas claras para **identificar a causa raiz** e subsidiar ações para fidelização e otimização de vendas.

---

## 🛠️ Metodologia e Pipeline de Dados

**Tecnologias Utilizadas:** Power BI, Excel/CSV, Power Query.

1.  **ETL e Transformação de Dados:**
    * A base de dados foi carregada a partir dos arquivos Excel/CSV.
    * O tratamento, limpeza e transformação de dados (ETL) foram realizados integralmente via **Power Query (M Language)** dentro do Power BI, para garantir a qualidade do modelo.
    * **🔗 [Ver Planilha de Dados de Origem (E-commerce.xlsx)]**(./E-commerce.xlsx)

2.  **Modelagem e DAX:**
    * A modelagem de dados foi organizada no **Esquema Estrela** para otimizar o desempenho e a navegabilidade do Power BI.
    * Criei medidas e colunas calculadas em **DAX** para: Taxa de Conclusão de Pedidos e Receita Acumulada.

---

## 💡 Resultados e Insights Estratégicos

O dashboard desenvolvido revelou:

* **Alto Risco:** **80% da receita total era impulsionada por apenas 15% da base de clientes.** A queda de vendas estava ligada a uma falha na retenção ou aquisição de novos clientes de alto valor.
* **Recomendação:** Priorizar programas de fidelidade e *upsell* para a base principal de clientes.

---

## 🔗 Acesso ao Projeto

* **🖼️ [Visualização do Dashboard (Template.png)]**(./Template.png)
* **💾 [Download do Arquivo PBIX (Vendas-commerce.pbix)]**(./Vendas-commerce.pbix)
* **🌐 [Ver Estudo de Caso Detalhado no Site Pessoal]** (Link para a aba 'Página do Projeto' no seu Google Site)
