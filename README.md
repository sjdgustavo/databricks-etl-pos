# ETL com Arquitetura Medallion no Databricks

Projeto desenvolvido durante minha pós-graduação em Engenharia de Dados e IA com foco na construção de um pipeline ETL utilizando arquitetura Medallion (Bronze, Silver e Gold) no Databricks.

O pipeline realiza ingestão, tratamento e disponibilização de dados analíticos utilizando PySpark e Delta Lake, aplicando conceitos modernos de Engenharia de Dados e organização em camadas.

---

```bash
ETL_arquitetura_medalhao/
│
├── 00.config/
│   └── config.ipynb
│
├── 01.bronze/
│   ├── ipca_bronze.ipynb
│   └── boi_gordo_bronze.ipynb
│
├── 02.silver/
│   └── economia_silver.ipynb
│
├── 03.gold/
│   └── gold_insights.ipynb
│
└── README.md
