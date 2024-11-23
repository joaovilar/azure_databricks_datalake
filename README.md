# Conexão do Databricks com Azure Data Lake Storage Gen2 e leitura da camada raw (dados brutos)


Este repositório demonstra como configurar e realizar a conexão entre o Azure Databricks e o Azure Data Lake Storage Gen2, além de demonstrar como realizar a leitura de arquivos armazenados na camada raw (dados brutos).

1. Configuração passo a passo para autenticação no Azure Data Lake usando OAuth 2.0.
2. Criação de um ponto de montagem no Databricks para acessar dados armazenados no Data Lake.
3. leitura de arquivos no formato CSV diretamente da camada raw.
4. Aplicação do Spark para carregar os dados em dataframes

   **Estrutura do Repositório**

    **csv/**: Contém arquivos CSV utilizados para simular dados de entrada da camada raw, incluindo tabelas como brands, orders, products, entre outras.<br>
    **azure data lake connect - raw.ipynb**: Um notebook detalhado que apresenta o código necessário para configurar a conexão e processar os arquivos.

![image](https://github.com/user-attachments/assets/5b9629c1-b886-4daa-8228-06b0a659cc34)

