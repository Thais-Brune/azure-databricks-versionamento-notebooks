# Azure Databricks - Versionamento e Organização de Notebooks

Descrição do Projeto

Este projeto demonstra o uso do Azure Databricks para criação, organização e versionamento de notebooks em ambientes de dados na nuvem.

A solução contempla desde a criação de clusters e importação de arquivos até a integração com Azure DevOps para versionamento de código e automação de pipelines CI/CD.

Também são explorados recursos de inteligência artificial integrados ao Databricks para auxiliar na geração de código Python e Spark, facilitando a construção de notebooks interativos com análises, filtros, sumarizações e visualizações de dados.

## Objetivos do Projeto
## Objetivo Geral

Demonstrar na prática como utilizar o Azure Databricks em um ambiente moderno de engenharia de dados, aplicando boas práticas de organização, colaboração e versionamento.

## Objetivos Específicos
Criar e configurar clusters no Azure Databricks;
Importar arquivos para processamento;
Criar notebooks em Python e Spark;
Utilizar IA integrada para geração de código;
Integrar notebooks ao Azure DevOps;
Implementar versionamento de notebooks;
Automatizar processos com CI/CD;
Organizar ambientes colaborativos de dados.
Tecnologias Utilizadas
Microsoft Azure
Azure Databricks
Apache Spark
Python
Azure DevOps
Git
CI/CD
Machine Learning

## Etapas Desenvolvidas
1. Criação do Workspace no Azure Databricks

Foi criado um workspace no Azure Databricks utilizando o portal Azure.

Configurações utilizadas
Configuração	Valor
Região	Brazil South
Plano	Standard
Resource Group	RG-DIO-DATABRICKS

2. Criação do Cluster

O cluster foi configurado para execução dos notebooks Spark.

Configuração do Cluster
Configuração	Valor
Runtime	Databricks Runtime
Linguagem	Python
Tipo de Cluster	Single Node

3. Importação de Arquivos

Foram importados arquivos CSV para análise e processamento.

Exemplo de Dataset
vendas.csv
clientes.csv
produtos.csv

4. Criação de Notebooks

Os notebooks foram utilizados para:

Leitura de dados;
Tratamento de dados;
Análises exploratórias;
Criação de visualizações;
Aplicação de filtros;
Geração de sumarizações.

5. Utilização da IA Integrada

A inteligência artificial integrada ao Databricks foi utilizada para auxiliar na geração de código Python e Spark.

Exemplos gerados pela IA
Leitura de arquivo CSV
df = spark.read.csv('/FileStore/dados/vendas.csv', 
header=True, inferSchema=True)
Exibição de dados
display(df)
Agrupamento e sumarização
df.groupBy("categoria") \
.sum("valor_venda") \
.show()

6. Visualização de Dados

Foram criados gráficos e tabelas interativas dentro dos notebooks.

Recursos utilizados
Gráficos de barras;
Tabelas dinâmicas;
Dashboards interativos;
Filtros por período e categoria.

7. Integração com Azure DevOps

O projeto foi integrado ao Azure DevOps para controle de versão e colaboração.

Funcionalidades utilizadas
Repositórios Git;
Versionamento de notebooks;
Controle de alterações;
Branches;
Pull Requests.

8. Automação com CI/CD

Foi configurada uma esteira de CI/CD para automação de deploy dos notebooks.

Benefícios
Automação de processos;
Maior controle de versões;
Deploy contínuo;
Melhor colaboração entre equipes.
Boas Práticas Aplicadas
Organização de notebooks por finalidade;
Separação entre scripts e imagens;
Uso de comentários explicativos;
Versionamento com Git;
Reaproveitamento de código;
Uso de notebooks modulares;
Documentação completa do projeto.
Monitoramento e Controle

Foram utilizados recursos do Azure para monitoramento de:

Uso do cluster;
Consumo de recursos;
Execução de notebooks;
Performance dos jobs.
Aprendizados Obtidos

Durante o desenvolvimento deste projeto foi possível aprender:

Criação de ambientes no Azure Databricks;
Processamento distribuído com Spark;
Integração com Azure DevOps;
Versionamento de notebooks;
Automação CI/CD;
Uso de IA para geração de código;
Organização de ambientes colaborativos.
Capturas de Tela

## Conclusão

O projeto demonstrou como utilizar o Azure Databricks em ambientes modernos de dados, aplicando práticas importantes de organização, versionamento e automação.

Além disso, foi possível integrar notebooks ao Azure DevOps e utilizar recursos de inteligência artificial para acelerar o desenvolvimento de análises e pipelines de dados.
feat: integração com azure devops
feat: configuração do pipeline ci/cd
docs: atualização do README
