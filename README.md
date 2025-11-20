# Sistema de Recomendação Orientado a Qualidade no E-commerce

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Spark](https://img.shields.io/badge/Apache%20Spark-PySpark-orange)
![Status](https://img.shields.io/badge/Status-Concluído-green)

Este repositório contém o código-fonte, documentação e análises desenvolvidas para o **Projeto Aplicado III** do curso de Tecnologia em Ciências de Dados da **Universidade Presbiteriana Mackenzie**.

## 🎯 Objetivo

O objetivo principal deste projeto é desenvolver um sistema de recomendação capaz de sugerir produtos relevantes aos usuários com base em avaliações de outros consumidores. O sistema utiliza uma abordagem **híbrida**, combinando técnicas de **Filtragem Colaborativa** e **Filtragem Baseada em Conteúdo**, para proporcionar recomendações mais precisas, diversificadas e personalizadas.

As metas específicas do projeto incluem:
*   **Analisar dados:** Identificar padrões e informações relevantes nas avaliações de produtos para a recomendação.
*   **Avaliar estratégias:** Testar diferentes abordagens que considerem tanto as notas (ratings) quanto as características textuais dos produtos.
*   **Testar precisão:** Verificar a capacidade do sistema em fornecer sugestões úteis para diferentes perfis de usuários.
*   **Melhorar a experiência:** Propor melhorias na experiência de compra com base nas recomendações geradas.

**Orientadora:** Profª. Carolina Toledo Ferraz

## 📂 Estrutura do Repositório 

O projeto está organizado da seguinte forma para facilitar a navegação e reprodução:

```text
/
├── Data/                   # Contém o dataset (link no txt devido ao tamanho)
│   └── base.txt
├── notebooks/              # Códigos fontes executáveis (Jupyter/Colab)
│   └── Sistema_Recomendacao_Ecommerce.ipynb
├── docs/                   # Documentação
│   └── PROJETO APLICADO III.pdf
├── images/                 # Imagens e gráficos gerados
│   ├── cauda_longa.png
│   └── comparativo_rmse_mae.png
├── README.md 
