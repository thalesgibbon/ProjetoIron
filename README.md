# ProjetoUltron

Projeto Iron foi desenvolvido por volta de 2016 com objetivo de acompanhar e mensurar projetos realizados por uma empresa de consultoria no ramo de tecnologia. O escopo foi definido em entender o banco de dados do software de gestao, extrair os dados, cruzar com informacoes externas (drive e calendar), modelar e criar dashboard.

A origem dos dados foram Software de lancamento de horas, Google Planilhas e Google Calendar. Foram necessarios cerca de 360 horas para finalizar o projeto.

Alguns exemplos de metricas elaboradas: Horas realizadas, Horas previstas, Horas orcadas, etc.

Alguns exemplos de dimensoes desenvolvidas: Por colaborador, produtivas e inprodutiva, cliente, projeto, etc.

Comentario: Este foi meu primeiro projeto em que utilizei o metodo dinamico de criacao em um projeto Qlikview. Este metodo unifica todos scripts e funcoes em uma planilha(Excel) com objetivo de reduzir erros de desenvolvimento. Para contribuir com o metodo, adaptei a criacao de graficos dinamicos no arquivo de modelagem, resultando numa facil visualizacao de dimensoes e metricas dinamicas (vide 7.DataModel).
![Alt Text](https://github.com/thalesgibbon/ProjetoIron/raw/master/ProjetoIron_DinamicTable.png)

## Estrutura 

* 1.Config - Arquivos e dados default utilizados ao longo do projeto;
* 2.OtherData - Arquivos externos. Exemplo (Planilhas, Imagens, etc);
* 3.Extractor - Script Qlikview de extracao de dados;
* 4.ExtractData - Diretorio de armazenamento dos dados extraidos;
* 5.Transform - Script Qlikview de transformacao e padronizacao de dados;
* 6.TransformData - Diretorio de armazenamento dos dados transformados;
* 7.DataModel - Arquivo Qlikview de modelagem de dados;
* 8.APP - Arquivo Qlikview de visualizacao de dados;
* reload APP.bat - Arquivo bat para atualizacao dos scripts.

## Overview 

(obs: dados foram mesclados por motivos de confidencialidade)

Aba para acompanhar o saldo de horas dos colaboradores da consultoria:
![Alt Text](https://github.com/thalesgibbon/ProjetoIron/raw/master/ProjetoIron_SaldoHoras.png)

Aba para acompanhar os projetos ativos e inativos, como tambem as horas alocadas em cada tarefa:
![Alt Text](https://github.com/thalesgibbon/ProjetoIron/raw/master/ProjetoIron_Tarefas.png)

Aba para acompanhar especificamente a equipe de suporte a clientes:
![Alt Text](https://github.com/thalesgibbon/ProjetoIron/raw/master/ProjetoIron_EquipeSuporte.png)

Aba enviada semanalmente com o report de horas para cada cliente.
![Alt Text](https://github.com/thalesgibbon/ProjetoIron/raw/master/ProjetoIron_Report.png)


## Stack:

* [Excel] - Centralizar todos dados de dimensoes, metricas e fluxo de transformacao.
* [Qlikview 11] - ETL, Modelagem e Visualizacao dos dados.

## Desenvolvido por:

| Nome | GitHub 
|---|---|
| Thales Gibbon | @thalesgibbon |

## Resultado:

* Automatizacao de reports manuais
* melhor acompanhamento de projetos e saldo de horas pela consultoria
* aprendizado de metodo dinamico

