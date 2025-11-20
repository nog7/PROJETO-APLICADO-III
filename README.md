# Sistema de Recomendação Orientado a Qualidade no E-commerce

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Spark](https://img.shields.io/badge/Apache%20Spark-PySpark-orange)
![Status](https://img.shields.io/badge/Status-Concluído-green)

Este repositório contém o código-fonte, documentação e análises desenvolvidas para o **Projeto Aplicado III** do curso de Tecnologia em Ciências de Dados da **Universidade Presbiteriana Mackenzie**.

## 🎯 Objetivo

O objetivo principal deste projeto é desenvolver um sistema de recomendação escalável (Big Data) capaz de sugerir produtos alimentícios relevantes aos usuários da Amazon. O sistema utiliza uma abordagem híbrida e colaborativa, visando reduzir a sobrecarga cognitiva do consumidor ("Paradoxo da Escolha") e promover produtos de qualidade baseados em avaliações históricas.

As principais metas incluem:
*   Processamento de grandes volumes de dados (Dataset Amazon Fine Food Reviews).
*   Implementação do algoritmo **ALS (Alternating Least Squares)** via PySpark.
*   Validação matemática do modelo comparado a baselines aleatórios.

**Orientadora:** Profª. Carolina Toledo Ferraz

## 📂 Estrutura do Repositório

O projeto está organizado da seguinte forma para facilitar a navegação e reprodução:

```text
/
├── Data/                   # Contém o dataset (link no txt devido ao tamanho)
│   └── base.txt
├── docs/                   # Documentação
│   └── Relatorio_Projeto_Aplicado_III.pdf
├── images/                 # Imagens e gráficos gerados
│   ├── cauda_longa.png
│   └── comparativo_rmse_mae.png
├── notebooks/              # Códigos fontes executáveis (Jupyter/Colab)
│   └── Sistema_Recomendacao_Ecommerce.ipynb
├── README.md               # Este arquivo
