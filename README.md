# 🛒 TechStore (`loja_tech`) — Consultas SQL, Stored Procedures e Views

![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen)
![MySQL](https://img.shields.io/badge/MySQL-8.0%2B-blue?logo=mysql&logoColor=white)
![Atividade](https://img.shields.io/badge/Atividade-Individual-orange)

Repositório desenvolvido para a disciplina de **Banco de Dados**, contendo a resolução prática das **10 consultas SQL**, **5 Stored Procedures** aplicadas ao banco relacional `loja_tech` (contexto e-commerce TechStore) e **5 exemplos práticos de Views**.

---

## 📋 Sumário

- [Sobre o Projeto](#-sobre-o-projeto)
- [Estrutura do Repositório](#-estrutura-do-repositório)
- [Consultas SQL (Parte 1)](#-consultas-sql-parte-1)
- [Stored Procedures Implementadas (Parte 2)](#-stored-procedures-implementadas-parte-2)
- [Views vs. Stored Procedures: 5 Casos de Uso](#-views-vs-stored-procedures-5-casos-de-uso)
- [Como Executar no MySQL Workbench](#-como-executar-no-mysql-workbench)
- [Referências Bibliográficas](#-referências-bibliográficas)

---

## 🎯 Sobre o Projeto

O objetivo desta atividade é praticar a manipulação de dados em SQL (filtros, ordenação, funções de agregação e `INNER JOIN`) e aplicar a programação no lado do servidor (*Server-Side*) por meio de **Stored Procedures** no MySQL, seguindo boas práticas (`DROP PROCEDURE IF EXISTS`, controle de `DELIMITER` e prefixo `p_` nos parâmetros).

---

## 📂 Estrutura do Repositório

```text
├── 01_schema_loja_tech.sql      # Criação do banco, tabelas e carga inicial de dados
├── 02_consultas.sql             # Resolução dos 10 desafios de consultas SQL
├── 03_stored_procedures.sql     # Criação e testes das 5 Stored Procedures
├── 04_exemplos_views.sql        # 5 exemplos práticos de Views no contexto loja_tech
└── README.md                    # Documentação completa do projeto
