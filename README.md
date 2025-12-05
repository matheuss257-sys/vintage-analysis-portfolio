# Projeto: Análise de Vintage e Inadimplência de Crédito

Este projeto consiste em uma automação desenvolvida em **Python** para processar dados de duplicatas, calcular a Matriz de Safra (Vintage Analysis) e gerar indicadores de inadimplência.

# Objetivo
O script lê uma base de dados bruta, realiza o tratamento e limpeza (ETL), aplica regras de negócio para classificar atrasos (buckets de 30, 60, 90 e 180 dias) e exporta um relatório executivo em Excel.

# Tecnologias
* **Python 3**
* **Pandas & NumPy** (Manipulação de dados e cálculos vetoriais)
* **OpenPyXL** (Exportação para Excel)

## Estrutura dos Arquivos
* `MatrizAdimplencia.ipynb`: O código fonte (Jupyter Notebook) com toda a lógica documentada.
* `dados.xlsx`: Base de dados fictícia utilizada para demonstração.
* `Relatorio_Analise_Carteira_Final.xlsx`: Exemplo do output gerado pelo script.

## Como Executar
Você pode visualizar o projeto diretamente aqui no GitHub. Caso queira rodar o código:

1.  Baixe o arquivo `MatrizAdimplencia.ipynb` e `dados.xlsx`.
2.  Abra o arquivo `.ipynb` no Google Colab ou Jupyter Notebook.
3.  Faça o upload do arquivo `dados.xlsx` para o ambiente.
4.  Execute todas as células.
