# Projeto de Data Warehouse - Análise de Crimes em Chicago

## Descrição

Este projeto foi desenvolvido como trabalho final da disciplina DCC147 - Data Warehouse, ministrada pelo Prof. Victor Ströele. O objetivo é analisar os dados de crimes cometidos na cidade de Chicago, produzindo soluções (relatórios, indicadores, dashboards) que auxiliem os gestores a compreender as ocorrências dos crimes na cidade.

## Estrutura do Projeto

O projeto segue a arquitetura Kimball e está estruturado nas seguintes etapas:

1. Carga dos dados do Sistema
2. Criação e Carga do Modelo Dimensional
3. Criação do CUBO
4. Criação de Relatórios com o Pentaho
    - Relatórios Estáticos
    - Relatórios Dinâmicos
5. Criação de dashboards

## Tecnologias Utilizadas

- Pentaho Data Integration (PDI) para ETL
- Schema Workbench para criação de cubos OLAP
- Pentaho BI Server para hospedagem e acesso aos dados
- Pentaho Report Designer para relatórios estáticos
- Saiku Analytics para relatórios dinâmicos
- Pentaho Dashboard Designer para criação de dashboards


## Como Executar

1. Clone este repositório
2. Siga as instruções em cada diretório para configurar e executar cada etapa do projeto
3. Certifique-se de ter todas as ferramentas Pentaho instaladas e configuradas corretamente

## Estrutura de Diretórios

- `/dados`: Contém os dados brutos e processados
- `/etl`: Scripts e transformações de ETL
- `/modelos`: Modelos dimensionais e cubos OLAP
- `/relatorios`: Relatórios estáticos e dinâmicos
- `/dashboards`: Arquivos de configuração dos dashboards
- `/docs`: Documentação adicional do projeto


## Autores

- Ádrian Pereira Machado
- Arthur Lima da Costa

## Data de Entrega

17/03/2025

## Link para download da base
https://catalog.data.gov/dataset/crimes-2001-to-present
