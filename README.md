# Projeto de Exemplo ETL

Este é um projeto de exemplo que demonstra a extração, transformação e carregamento (ETL) de dados utilizando Python, pandas e SQLite.

## Dados

Os dados utilizados no projeto são fictícios e representam vendas de produtos em duas filiais diferentes.

### Filial 1

Os dados da filial 1 estão contidos no arquivo CSV `vendas_filial1.csv` e foram transformados de acordo com as operações definidas no código. Abaixo estão os dados transformados da filial 1:

| ID do Produto | Nome do Produto                | Quantidade Vendida | Preço Unitário | Valor Total |
|---------------|--------------------------------|--------------------|----------------|-------------|
| 101           | Laptop Dell XPS 13             | 20                 | 1500.0         | 30000.0     |
| 102           | Smartphone Samsung Galaxy S20   | 30                 | 1000.0         | 30000.0     |
| 103           | Monitor LG UltraWide 34"       | 15                 | 600.0          | 9000.0      |
| 104           | Teclado Mecânico Corsair K95 RGB | 25               | 200.0          | 5000.0      |
| 105           | Mouse Logitech MX Master 3      | 10                 | 80.0           | 800.0       |

### Filial 2

Os dados da filial 2 estão contidos no arquivo Excel `vendas_filial2.xlsx` e foram transformados de acordo com as operações definidas no código. Abaixo estão os dados transformados da filial 2:

| ID do Produto | Nome do Produto                     | Quantidade Vendida | Preço Unitário | Valor Total |
|---------------|-------------------------------------|--------------------|----------------|-------------|
| 201           | Impressora HP LaserJet Pro          | 12                 | 250.0          | 3000.0      |
| 202           | SSD Samsung 1TB                     | 18                 | 180.0          | 3240.0      |
| 203           | Tablet Apple iPad Pro                | 8                  | 900.0          | 7200.0      |
| 204           | Smartwatch Samsung Galaxy Watch 4    | 14                 | 300.0          | 4200.0      |
| 205           | Headset HyperX Cloud II              | 20                 | 120.0          | 2400.0      |

### Resultados

Os dados transformados foram carregados em um banco de dados SQLite `dados_transformados.db` e podem ser acessados utilizando consultas SQL. A seguir estão os primeiros registros das tabelas transformadas no banco de dados:

#### Tabela 'vendas_filial1_transformadas'

| ID do Produto | Nome do Produto                | Quantidade Vendida | Preço Unitário | Valor Total |
|---------------|--------------------------------|--------------------|----------------|-------------|
| 101           | Laptop Dell XPS 13             | 20                 | 1500.0         | 30000.0     |
| 102           | Smartphone Samsung Galaxy S20   | 30                 | 1000.0         | 30000.0     |
| 103           | Monitor LG UltraWide 34"       | 15                 | 600.0          | 9000.0      |
| 104           | Teclado Mecânico Corsair K95 RGB | 25               | 200.0          | 5000.0      |
| 105           | Mouse Logitech MX Master 3      | 10                 | 80.0           | 800.0       |

#### Tabela 'vendas_filial2_transformadas'

| ID do Produto | Nome do Produto                     | Quantidade Vendida | Preço Unitário | Valor Total |
|---------------|-------------------------------------|--------------------|----------------|-------------|
| 201           | Impressora HP LaserJet Pro          | 12                 | 250.0          | 3000.0      |
| 202           | SSD Samsung 1TB                     | 18                 | 180.0          | 3240.0      |
| 203           | Tablet Apple iPad Pro                | 8                  | 900.0          | 7200.0      |
| 204           | Smartwatch Samsung Galaxy Watch 4    | 14                 | 300.0          | 4200.0      |
| 205           | Headset HyperX Cloud II              | 20                 | 120.0          | 2400.0      |

Para mais detalhes sobre o código e a execução do projeto, consulte os arquivos Python fornecidos no repositório.

Link do Colab: https://colab.research.google.com/drive/1fIaimbuEhvwAei_LE7bgQVMQufridgn5?usp=sharing
