# Introdução à Engenharia de Dados

## Quais são os principais fundamentos da engenharia de dados?

A engenharia de dados é uma disciplina fundamental no campo da ciência de dados e análise de dados. Ela se concentra na coleta, transformação e disponibilização de dados para uso em análises, modelos de aprendizado de máquina ou visualizações. Aqui estão os principais fundamentos da engenharia de dados:

### 1. Arquitetura de dados

- Pipeline de Dados: Configuração de fluxos automatizados para extrair, transformar e carregar dados (ETL ou ELT).
- Armazenamento: Escolha de soluções de armazenamento adequadas, como banco de dados relacional, data lakes ou data warehouses.
- Modelagem de Dados: Projetar esquemas lógicos e físicos para representar os dados de forma eficiente.

### 2. Processamento de dados

- ETL/ELT:
    - ETL (Extract, Transform, Load): Os dados são extraídos, transformados e carregados em um data warehouse os sistema final.
    - ELT (Extract, Load, Transform): Dados são carregados no sistema bruto
 
- Batch Processing: Processamento de grandes volumes de dados em intervalos regulares.
- Stream Processing: Processamente de dados em tempo real, como com Kafka, Flink ou Spark

### 3. Integração e Ingestão de Dados

- Conectores e APIs: Integração com diversas fontes de dados, como banco de dados relacionais, APIs REST e arquivos.
- Ferramentas de Ingestão: Uso de ferramentas como Apache Kafka, Apache Nifi, AWS Glue, Google Dataglow.
- Contorole de Dados Não Estruturados: Habilidade para lidar com dados como JSON, XML, Logs ou multímidia.

### 4. Qualidade e Governança de Dados

- Qualidade de Dados:
  - Validação e limpeza dos dados.
  - Detecção e correção de duplicatas e inconsistências.
- Governança de Dados:
   - Metadados e catalogação.
   - Detecção e correção de duplicatas e inconsistências.
- Privacidade e Segurança:
  - Conformidade com leis como LGPD ou GDPR.
  - Criptografia e controle de acessos.

 ### 5. Escabilidade e Performance

 - Soluções Escaláveis:
   - Ferramentas como Apache Spark ou Hadoop para processar grandes volumes de dados.
    
 - Performance:
   -  Indexação e particionamento em bancos de dados.
   -  Uso de caches, como Redis ou Memcached.

### 6. Data Warehousing e Data Lakes

- Data Warehouse: Armazena dados estruturados otimizados para consultas e relatórios (e.g., Snowflake, Redshift, BigQuery).
- Data Lake: Repositório de dados não estruturados ou semi-estruturados (e.g., S3, Azure Data Lake).

### 7. Ferramentas e Linguagens

- Linguagens de Programação:
  -  SQL: Fundamento para manipulação de dados em bancos relacionais.
  -  Python/Scala: Para scripts, automação e frameworks como PySpark

- Ferramentas:
  - Orquestração: Apache Airflow, Luigi.
  - Bancos de Dados: PostgreSQL, MySQL, MongoDB, Cassandra.
  - Processamento: Apache Spark, Databricks, Flink.

###  8. Monitoramento e Observabilidade

- Logs e Alertas: Configuração de logs e notificações para falhas nos pipelines.
- Dashboards: Monitorar a performance do sistema usando ferramentas como Grafana ou Kibana.

### 9. Cloud Computing

- Serviços Gerenciados:
  - AWS (S3, Redshift, Glue), Google Cloud (BigQuery, Dataflow), Azure (Data Factory, Synapse Analytics).
 
- Orquestração e Automação: Infraestrutura como código (Terraform, CloudFormation)

### 10. Soft Skills

- Comunicação: Traduzir requisitos de negócios em soluções técnicas.
- Resolução de Problemas: Diagnosticar e resolver gargalos em pipelines de dados.
- Trabalho em Equipe: Colaboração com cientistas de dados, analistas e outros engenheiros.

Se você esta começando, aprender os conceitos de ETL, modelagem de dados, SQL, e ferramentas como Apache Airflow e Spark são bons pontos 

## Como surgiu a engenharia de dados e os principais pontos chaves na evolução da área?

A engenharia de dados surgiu com a necessidade de gerenciar e processar grandes volumes de dados, algo que começou a se intensificar com a popularização da internet e o aumento das capacidades computacionais. O campo tem suas raízes nas áreas de computação, banco de dados e análise de dados, e sua evolução acompanha o crescimento do volume de dados e da complexidade das soluções necessárias para lidar com eles.

Aqui está um resumo da evolução da engenharia de dados, com ênfase nos principais marcos e pontos-chave ao longo do tempo:

### 1. Era dos Bancos de Dados Relacionais (1980-1990)

- Contexto: À medida que as empresas começaram a acumular grandes volumes de dados transacionais, surgiu a necessidade de uma abordagem mais focada em análise. Isso resultou na popularização dos Data Warehouses e das tecnologias OLAP (Online Analytical Processing).
- Foco: Armazenamento de dados históricos em formatos otimizados para consultas e análises rápidas (e.g., cubos OLAP).
- Ferramentas: Empresas começaram a adotar soluções como Teradata, IBM DB2, e Microsoft SQL Server para armazenar grandes volumes de dados.

### 2. Data Warehousing e OLAP (1990-2000)

- Contexto: À medida que as empresas começaram a acumular grandes volumes de dados transacionais, surgiu a necessidade de uma abordagem mais focada em análise. Isso resultou na popularização dos Data Warehouses e das tecnologias OLAP (Online Analytical Processing).
- Foco: Armazenamento de dados históricos em formatos otimizados para consultas e análises rápidas (e.g., cubos OLAP).
- Ferramentas: Empresas começaram a adotar soluções como Teradata, IBM DB2, e Microsoft SQL Server para armazenar grandes volumes de dados.

### 3. Big Data (2000-2010)

- Contexto: No início dos anos 2000, com o aumento exponencial da quantidade de dados gerados por usuários e dispositivos (como logs de servidores, redes sociais, sensores, etc.), os bancos de dados tradicionais começaram a ser limitados.

- Foco: Surgiu o conceito de Big Data, que envolvia a coleta e processamento de grandes volumes de dados, frequentemente não estruturados, em tempo real. Tecnologias como Hadoop e
MapReduce foram desenvolvidas para lidar com essas demandas.

- Ferramentas:
   - Apache Hadoop (e seu ecossistema, como Hive, HBase, Pig) tornou-se um marco para processamento em larga escala.
   - NoSQL databases como Cassandra, MongoDB e Couchbase começaram a surgir para lidar com dados não estruturados.

### 4. Cloud Computing e Data Lakes (2010-2020)

- Contexto: O advento da computação em nuvem transformou a forma como as empresas lidavam com dados. Plataformas como AWS, Google Cloud e Azure começaram a oferecer soluções escaláveis e econômicas para armazenar e processar dados.
- Foco: Surge o conceito de Data Lake, onde os dados são armazenados em formatos brutos e podem ser processados de acordo com a necessidade. Isso representa uma mudança em relação ao modelo tradicional de Data Warehouse, que exigia dados estruturados e formatados.
- Ferramentas:
  - Amazon S3, Google Cloud Storage e Azure Blob Storage se tornaram os principais destinos de armazenamento para dados não estruturados.
  - Apache Spark surgiu como a solução de processamento de dados em larga escala, especialmente para processamento em memória.

### 5. Orquestração e Automação de Pipelines (2015-presente)

- Contexto:  À medida que as empresas passaram a usar mais tecnologias e fontes de dados, surgiu a necessidade de orquestrar e automatizar os fluxos de dados (pipelines) para integrar diferentes fontes e preparar dados para análise.
- Foco: Criar pipelines de dados que permitem que os dados sejam extraídos de fontes diversas, transformados e carregados de maneira automatizada, escalável e eficiente. O objetivo é ter dados sempre disponíveis e atualizados para análise em tempo real ou em batch.
- Ferramentas:
  - Apache Airflow e Luigi ganharam popularidade como ferramentas de orquestração de pipelines.
  - AWS Glue, Google Cloud Dataflow e Azure Data Factory são soluções gerenciadas para orquestrar dados em ambientes de nuvem.
  - Apache Kafka se tornou uma solução essencial para streaming de dados em tempo real.

### 6. Integração de IA e Machine Learning (2018-presente)

- Contexto: Com o avanço da inteligência artificial e aprendizado de máquina, a engenharia de dados passou a se integrar com essas tecnologias para fornecer dados limpos, bem estruturados e prontos para análise preditiva.
- Foco: Engenharia de dados agora também inclui a criação de pipelines de dados que alimentam modelos de machine learning, além de garantir que dados sejam acessíveis e de alta qualidade para análise preditiva.
- Ferramentas:
  - MLflow, Kubeflow e TensorFlow passaram a ser utilizados para integrar pipelines de dados com modelos de machine learning.
  - A integração com ferramentas de análise em tempo real também ficou mais forte, com tecnologias como Apache Flink e Apache Kafka Streams.
 
## Principais Pontos-Chave na Evolução da Engenharia de Dados

- Primeira Era (1980-1990): Foco em bancos de dados relacionais e SQL para armazenamento estruturado.
- Segunda Era (1990-2000): Adoção de Data Warehouses e OLAP para análise de grandes volumes de dados transacionais.
- Big Data (2000-2010): A revolução do Big Data com ferramentas como Hadoop para dados em larga escala e não estruturados.
- Data Lakes e Cloud (2010-2020): Mudança para Data Lakes na nuvem, armazenamento de dados brutos e escalabilidade.
- Orquestração de Pipelines (2015-presente): Desenvolvimento de pipelines de dados automatizados e escaláveis com ferramentas como Airflow.
- Integração com IA e ML (2018-presente): Engenharia de dados se integra com machine learning para entregar dados prontos para modelos preditivos.

A evolução da engenharia de dados reflete a crescente complexidade e volume de dados gerados e a demanda por soluções mais escaláveis, rápidas e integradas para permitir análises precisas e em tempo real. A área continua a se expandir com o uso de inteligência artificial e automação, que tornam os dados não apenas mais acessíveis, mas tambem mais uteis para decisões estratégicas e preditivas.

