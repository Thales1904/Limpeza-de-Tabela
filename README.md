# Limpeza e Análise de Dados — Cafeteria

Projeto desenvolvido para realizar a **limpeza, organização e análise exploratória** de uma tabela de vendas de uma cafeteria utilizando Python.

O trabalho parte de uma base de dados com informações inconsistentes e aplica técnicas de tratamento e análise com **Pandas**, além da criação de gráficos para facilitar a visualização dos dados.

## Objetivos

* Identificar e tratar dados inconsistentes.
* Organizar e padronizar a tabela de vendas.
* Trabalhar com seleção e manipulação de dados utilizando `loc` e `iloc`.
* Realizar uma análise exploratória da base.
* Criar gráficos para visualizar informações relevantes.
* Exportar a tabela após o processo de limpeza.

## Tecnologias utilizadas

* **Python**
* **Jupyter Notebook**
* **Pandas** — manipulação e limpeza dos dados.
* **Matplotlib** — criação de gráficos.
* **Seaborn** — visualização e análise gráfica.

## Arquivos

| Arquivo                | Descrição                                                                    |
| ---------------------- | ---------------------------------------------------------------------------- |
| `dirty_cafe_sales.csv` | Tabela original, contendo dados que precisam ser tratados.                   |
| `tabela_limpa.csv`     | Tabela final após o processo de limpeza.                                     |
| `*.ipynb`              | Notebook contendo as etapas de tratamento, análise e visualização dos dados. |

## Etapas do projeto

### 1. Importação dos dados

A tabela `dirty_cafe_sales.csv` é carregada utilizando o Pandas para iniciar o processo de análise.

### 2. Exploração da base

São verificadas informações como:

* quantidade de linhas e colunas;
* tipos de dados;
* valores ausentes;
* valores inconsistentes;
* estatísticas descritivas;
* possíveis duplicidades.

### 3. Limpeza dos dados

São aplicadas técnicas de tratamento para melhorar a qualidade da base, incluindo:

* tratamento de valores ausentes;
* correção de tipos de dados;
* padronização de informações;
* identificação e tratamento de valores inconsistentes;
* remoção ou correção de registros problemáticos quando necessário.

### 4. Seleção de dados com `loc` e `iloc`

O projeto também demonstra o uso dos principais métodos de seleção do Pandas:

```python
df.loc[condicao, "coluna"]
```

e

```python
df.iloc[linhas, colunas]
```

O objetivo é demonstrar, na prática, as diferenças entre a seleção por **rótulos/condições** (`loc`) e a seleção por **posição** (`iloc`).

### 5. Visualização dos dados

Após o tratamento, são utilizados **Matplotlib** e **Seaborn** para criar gráficos e facilitar a interpretação das informações presentes na tabela.

As visualizações ajudam a observar padrões, distribuições e relações entre as variáveis da base.

### 6. Exportação da tabela limpa

Ao final do processo, os dados tratados são exportados para uma nova tabela:

```text
tabela_limpa.csv
```

Dessa forma, a base original `dirty_cafe_sales.csv` é preservada e o resultado do processo de limpeza fica disponível em um novo arquivo.

## Resultado

O projeto demonstra um fluxo básico de **limpeza e análise de dados**, desde a importação de uma base com problemas até a geração de uma versão organizada e pronta para utilização em análises posteriores.

---

**Projeto desenvolvido para fins de estudo e prática em análise e tratamento de dados com Python.**
