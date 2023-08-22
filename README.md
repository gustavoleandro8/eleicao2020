# Estudo de Caso: Análise das Eleições de 2020 no estado de São paulo utilizando Python, SQL e Power BI
Neste repositório, compartilho os detalhes do meu estudo de caso que abordou a análise das eleições de 2020. O objetivo principal foi explorar e compreender os dados eleitorais por meio de uma combinação eficaz de ferramentas, incluindo Python, SQL (SQLite) e Power BI.

## Contexto do Estudo
O estudo de caso concentrou-se no Perfil do eleitor e os resultados das eleições realizadas em 2020 focado no estado de São paulo. O objetivo era extrair insights significativos dos dados brutos das eleições e apresentá-los de maneira clara e acessível por meio de visualizações dinâmicas e consultas eficiêntes.

## Ferramentas Utilizadas
Durante o desenvolvimento deste estudo de caso, utilizei as seguintes ferramentas:

1. **Python**:A linguagem de programação Python foi empregada para a limpeza, manipulação e preparação dos dados brutos das eleições. A biblioteca Pandas desempenharam um papel essencial na análise exploratória e no processamento dos dados.

2. **SQL (SQLite)**:Criei um banco de dados SQLite para armazenar os dados eleitorais de forma estruturada. Utilizei consultas SQL para extrair informações específicas , facilitando a análise dos dados em diferentes perspectivas.

3. **Power BI**: Para criar visualizações interativas e informativas dos insights extraídos dos dados, o Power BI foi a ferramenta escolhida. Elaborei um dashboard dinâmico que permite a exploração profunda dos resultados eleitorais em diferentes níveis de detalhes.

## Conteúdo do Notebook
O notebook intitulado "notebook_eleicao2020.ipynb" contém os seguintes tópicos:

**Importação de Bibliotecas**: Importação das bibliotecas necessárias, como pandas, sqlite3 e csv, para manipulação e análise de dados.

**Leitura e Limpeza de Dados**: Leitura dos arquivos CSV contendo os dados eleitorais de 2020. Em seguida, são mantidas apenas as colunas relevantes para a análise.

**Preparação dos Dados**: Realização do tratamento dos dados, incluindo a substituição de valores vazios por NaN e a remoção de registros nulos dos DataFrames.

**Criação do Banco de Dados**: Criação de um banco de dados SQLite chamado "eleicoes.db". Tabelas são criadas para armazenar os dados de perfil eleitoral e resultados.

**Importação de Dados no Banco de Dados**: Os DataFrames processados são importados para as tabelas do banco de dados SQLite.

**Consulta ao Banco de Dados**: Consultas SQL são executadas para responder a perguntas específicas, como os candidatos mais votados em um município e características mais frequentes do eleitorado.

## Arquivo .pbix
O arquivo "eleicao.pbix" contém o dashboard desenvolvido no Power BI. Ele foi criado para permitir a exploração interativa dos resultados eleitorais e das informações do perfil do eleitor. O dashboard inclui visualizações gráficas, tabelas dinâmicas e filtros interativos de acordo com o município que facilitam a compreensão e a obtenção de insights sobre os dados eleitorais.

![Dashboard_eleicao2020](https://github.com/gustavoleandro8/eleicao2020/assets/138906268/806cb0d3-9e99-4a2a-b1ad-d53f14859cf3)
