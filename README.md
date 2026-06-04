# 📊 Análise de Eficiência Multicanal: TV & Digital

## 📌 Sobre o Projeto
Este repositório contém uma pipeline completa de extração, tratamento e análise de dados voltada para **Marketing de Performance**. 

O objetivo central do projeto é cruzar bases de investimentos em mídia offline (TV Aberta) e campanhas digitais para apurar métricas reais de performance, identificar oportunidades de otimização de conversão (CRO) e mitigar desperdícios de orçamento publicitário. 

Como o meu foco atua na interseção entre **Dados e Design (UI/UX)**, toda a modelagem foi construída com foco em governança: garantir que a base de dados final seja limpa, íntegra e estruturalmente pronta para alimentar dashboards executivos sem quebrar a interface.

---

## 🛠️ Tecnologias e Arquitetura
* **Ingestão e Limpeza (ETL):** Python & Pandas.
* **Motor Relacional:** Banco de dados SQLite em memória para alta performance.
* **Regras de Negócio e Exploração:** SQL Avançado.
  * Uso de *CTEs (Common Table Expressions)* para consolidação prévia.
  * *Window Functions* e agregações para análise comportamental.
  * Condicionais lógicas (`CASE WHEN`) e `COALESCE` para tratamento de nulos e falhas de tracking.

---

## 🎯 Principais KPIs Analisados
A modelagem foi desenhada para responder às dores reais de negócio:
1. **Custo de Aquisição de Clientes (CAC):** Unificação dos investimentos de TV e Digital divididos pelas conversões reais, revelando o custo verdadeiro por usuário.
2. **Taxa de Conversão (CRO):** Mapeamento do funil de cliques para conversão, isolando erros de divisão por zero na base.
3. **Governança e Qualidade de Dados:** Identificação de campanhas sem correspondência multicanal e tratamento de *missing values* gerados pelas plataformas de mídia.

---

## 📂 Estrutura do Repositório
* `analise_campanhas.ipynb`: Notebook principal contendo o script em Python, as consultas estruturadas em SQL e o racional de Data Storytelling.
* `resultado_campanhas.csv`: Base final consolidada, limpa e cruzada, pronta para consumo em ferramentas de Business Intelligence (Power BI / Tableau).

---

## 🚀 Como Executar
O código foi documentado de forma interativa no Google Colab/Jupyter Notebook. 
Para visualizar a análise e os outputs gerados, basta abrir o arquivo `.ipynb` diretamente aqui no GitHub ou importá-lo para o seu ambiente de desenvolvimento.

---
✉️ **Contato:** dircesilva.2002@outlook.com | [LinkedIn](https://www.linkedin.com/in/dirce-maria-silva/)
