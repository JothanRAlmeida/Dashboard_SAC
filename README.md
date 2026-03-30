## Dashboard de Atendimento – Power BI

Este projeto foi desenvolvido como parte de um treinamento do canal Hashtag Treinamentos, com o objetivo de praticar todo o fluxo de análise de dados, desde o tratamento até a visualização final em um dashboard interativo no Power BI.

### Fonte de Dados

A base de dados foi inicialmente analisada no Excel antes da importação para o Power BI, garantindo melhor entendimento da estrutura e dos dados disponíveis.

### Tratamento de Dados (Power Query)

Durante a etapa de transformação, foram realizadas as seguintes ações:

Remoção de linhas em branco
Definição da primeira linha como cabeçalho
Correção dos tipos de dados
Padronização de nomes utilizando Coluna de Exemplo
Tratamento geral dos dados:
Inclusão de colunas como:
Tempo de atendimento
Tempo de resposta
Idade
Substituição de valores inconsistentes
Exclusão de dados desnecessários

### Modelagem de Dados

Foi realizada a criação de um modelo relacional, conectando:

Tabela Fato (atendimentos)
Tabelas Dimensão (ex: atendentes, problemas, datas, etc.)

Essa modelagem permite análises mais eficientes e escaláveis.

### Indicadores e Métricas

O dashboard foi construído com foco nas principais necessidades do negócio:

- Total de atendimentos
- Tempo médio de resposta (em dias)
- Tempo médio de atendimento (em minutos)
- Média diária de chamados
- % de chamados cancelados
- Visualizações

O dashboard inclui análises visuais como:

- Evolução do total de atendimentos ao longo do tempo
- Total de atendimentos por tipo de problema
- Total de atendimentos por atendente

### Objetivo

O principal objetivo deste projeto é transformar dados brutos em informações relevantes, permitindo uma visão clara da operação de atendimento e auxiliando na tomada de decisões.

### Ferramentas Utilizadas

- Power BI
- Power Query
- Excel
