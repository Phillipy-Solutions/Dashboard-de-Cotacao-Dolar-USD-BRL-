# 📊 Dashboard de Cotação do Dólar (USD/BRL)

Este projeto tem como objetivo analisar e monitorar a **cotação do dólar (USD/BRL)** nos últimos 30 dias, utilizando um fluxo completo de dados que simula um cenário real de **Business Intelligence e Analytics**.

O dashboard foi desenvolvido em **Power BI**, com dados coletados automaticamente via **API pública**, tratados com **Python** e transformados no **Power Query**, resultando em uma visualização clara, objetiva e orientada a indicadores.

---

## 🧠 Objetivo do Projeto

Transformar dados financeiros brutos em **informações visuais e acionáveis**, aplicando boas práticas de:

* Coleta de dados
* Tratamento e padronização
* Modelagem
* Criação de métricas
* Storytelling com dados

O projeto foi desenvolvido com foco em **portfólio**, aprendizado prático e simulação de um ambiente real de BI.

---

## 🔄 Fluxo da Solução

```
API → Python → CSV → Power BI → Power Query → Modelagem → DAX → Dashboard
```

### Descrição do fluxo:

1. **API pública (AwesomeAPI)** fornece os dados de cotação do dólar
2. **Python** realiza o consumo da API e estrutura os dados
3. Os dados tratados são salvos em um **arquivo CSV**
4. O **Power BI** consome o CSV
5. O **Power Query** realiza limpeza, padronização e ajustes de tipos
6. A **modelagem de dados** organiza os campos para análise
7. **Medidas DAX** são criadas para cálculo dos indicadores
8. O **dashboard** apresenta os insights de forma visual

---

## 📈 Indicadores do Dashboard

O dashboard apresenta os seguintes KPIs:

* **Cotação atual do dólar**
* **Maior valor no período (30 dias)**
* **Menor valor no período (30 dias)**
* **Evolução diária da cotação USD/BRL**

Além disso, há um texto analítico que contextualiza o comportamento da moeda no período analisado.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

* **Python**

  * Consumo de API
  * Tratamento e estruturação de dados
  * Geração de arquivo CSV

* **Power BI Desktop**

  * Conexão com dados
  * Modelagem
  * Criação de visualizações

* **Power Query (ETL)**

  * Limpeza de dados
  * Padronização de tipos
  * Ajustes de formato numérico

* **DAX**

  * Medida de cotação atual
  * Medida de valor máximo
  * Medida de valor mínimo

---

## 📊 Visualizações Utilizadas

* Cartões (KPIs)
* Gráfico de linha/área para evolução temporal
* Texto analítico para suporte à narrativa

O layout foi pensado para garantir:

* Clareza visual
* Leitura rápida
* Foco nos principais indicadores

---

## 🔁 Atualização dos Dados

O projeto está preparado para **atualização automática** quando publicado no **Power BI Service**, utilizando:

* Fonte de dados baseada em API pública
* Agendamento de atualização no serviço do Power BI

Não é necessário o uso de gateway, pois os dados são obtidos diretamente da internet.

---

## 📌 Considerações Finais

Este projeto demonstra a integração entre **Python e Power BI**, reforçando conceitos fundamentais de **Analytics Engineer**, **BI Developer** e **Analista de Dados**.

Feedbacks e sugestões são muito bem-vindos!

---

## 👤 Autor

**Matheus Phillipy**
Projeto desenvolvido para fins de estudo e portfólio em Análise de Dados e Business Intelligence.

---

## 🔖 Tags

`Power BI` `Python` `Data Analytics` `Business Intelligence` `DAX` `Power Query` `Data Visualization` `Portfolio`
