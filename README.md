# dw_dbt

Criando um DW, com informacoes extraidas de uma lib chamada yfinance e realizando as transformacoes no DBT + visualizacao no Streamlit.

Este projeto tem como objetivo criar um Data Warehouse (DW) para armazenar e analisar dados de commodities, utilizando uma arquitetura moderna de ETL (Extract, Transform, Load). 


![image](https://github.com/lucasfazzib/dw_dbt/assets/9930662/a346c668-fb36-4358-9067-c47ed989dff8)

## Estrutura do Projeto

### 1. Extract_Load

A parte de `extract_load` é responsável por extrair dados de uma API e carregar diretamente no banco de dados PostgreSQL. O script `extract_load.py` realiza essa operação.



