# Cenários

## Histórico de versões
| Data       | Versão | Descrição            | Autor | Revisor   |
| ---------- | ------ | -------------------- | -------------- | ----------- |
| 04.03.2022 | 0.1  | Primeira versão do documento incompleta | Matheus Sousa | Amanda Nobre |
| 04.03.2022 | 1.0  | Adição de cenários | Matheus Sousa | Amanda Nobre |
| 06.03.2022 | 1.1  | Ajustes menores | Matheus Sousa | Amanda Nobre |
| 06.03.2022 | 1.2  | Correções após revisão | Matheus Sousa | Amanda Nobre |

## Introdução

A técnica consiste na apresentação dos requisitos levantados em diferentes contextos e situações, apresentando as pessoas inseridas no contexto e as interações deles com o sistema.

## Metodologia

Para realização dos cenários utilizaremos esse template de tabela:

|Numero Cenário|Nome do cenário|
|---|---|
|**Versão**|1.0|
|**Autor**| Autor do cenário|
|**Metas**|Objetivo do ceário|
|**Contexto**|**Local:**<br>><br> **Pré-Condição:**<br>><br> **Pós-Condição:**<br>> |
|**Atores**|Atores Envolvidos|
|**Recursos**|Recursos Envolvidos|
|**Restrições**| Descrição das restrições|
|**Exceções**| Descrição|
|**Episódios**|Detalhes do evento|

## Participantes

- Matheus Sousa

## Cenários

#### C1 - O usuário deve ser capaz de reproduzir e pausar episódios de podcasts

|||
|---|---|
|**Versão**|1.0|
|**Autor**| Matheus Sousa |
|**Metas**| Pausar ou reproduzir um podcast em específico |
|**Contexto**|**Local:**<br>>Página de reprodução de mídia do AntennaPod<br> **Pré-Condição:**<br>>Escolher algum podcast em específico<br> **Pós-Condição:**<br>>Podcast pausado ou reproduzindo após interação do usuário |
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo|
|**Restrições**| Saber o nome de algum podcast, conseguir pesquisar e seleciona-lo|
|**Exceções**| Sem conexão, aplicativo travar, não encontrar qualquer podcast|
|**Episódios**|Usuário selecionar um podcast, usuário apertar o botão "pause"|


#### C2 - O usuário deve ser capaz de assinar um podcast

|||
|---|---|
|**Versão**|1.0|
|**Autor**| Matheus Sousa |
|**Metas**| Conseguir se inscrever em um podcast para receber novidades em primeira mão |
|**Contexto**|**Local:**<br>>"página" do podcast<br> **Pré-Condição:**<br>>podcast não assinado<br> **Pós-Condição:**<br>> receber novidades sobre o podcast |
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo|
|**Restrições**| Escolher um podcast|
|**Exceções**| Sem conexão, aplicativo travar, não encontrar o podcast, podcast já assinado|
|**Episódios**|Usuário escolhe um podcast, usuário assina o podcast|

#### C3 - O usuário deve ser capaz de, ao reproduzir, avançar um ep e voltar um ep

|||
|---|---|
|**Versão**|1.0|
|**Autor**| Matheus Sousa |
|**Metas**| Conseguir avançar ou voltar episódios em um mesmo podcast |
|**Contexto**|**Local:**<br>>Tela de execução do episódio<br> **Pré-Condição:**<br>>Episódio em execução<br> **Pós-Condição:**<br>>Tocando episódio seguinte ou anterior |
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo|
|**Restrições**| Episódio do podcast tocando |
|**Exceções**| Sem conexão, aplicativo dando crash|
|**Episódios**|Usuário começa a ouvir um episódio, usuário decide passar para o próximo ou voltar um episódio, usuário toma a ação|

#### C4 - O usuário deve conseguir ouvir um episódio sem precisar se inscrever em seu podcast

|||
|---|---|
|**Versão**|1.0|
|**Autor**| Matheus Sousa |
|**Metas**| Conseguir consumir conteúdo sem estar inscrito |
|**Contexto**|**Local:**<br>>Lista de conteúdo de um podcast<br> **Pré-Condição:**<br>>Não estar inscrito no podcast<br> **Pós-Condição:**<br>>Usuário consumindo o conteúdo sem estar inscrito |
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo|
|**Restrições**| Não estar inscrito no podcast|
|**Exceções**| Sem conexão, aplicativo dando crash|
|**Episódios**|Usuário seleciona um podcast, usuário seleciona um episódio|

#### C6 - O usuário deve conseguir baixar um podcast sem precisar se inscrever no mesmo

|||
|---|---|
|**Versão**|1.0|
|**Autor**| Matheus Sousa |
|**Metas**| Baixar conteúdo sem estar inscrito |
|**Contexto**|**Local:**<br>>Página de um podcast<br> **Pré-Condição:**<br>>Podcast não está baixado<br> **Pós-Condição:**<br>>Conteúdo baixado pelo usuário |
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo, memória|
|**Restrições**| Não estar inscrito|
|**Exceções**| Sem conexão, aplicativo dando crash|
|**Episódios**|Usuário seleciona um podcast, usuário baixa o episódio|

#### C7 - O usuário deve conseguir visualizar suas assinaturas

|||
|---|---|
|**Versão**|1.0|
|**Autor**| Matheus Sousa |
|**Metas**| Ter acesso aos podcasts assinados |
|**Contexto**|**Local:**<br>>interface de podcasts assinados<br> **Pré-Condição:**<br>>ter assinaturas<br> **Pós-Condição:**<br>>assinaturas visiveis na tela |
|**Atores**|Atores Envolvidos|
|**Atores**|Usuário|
|**Recursos**|aplicativo|
|**Restrições**| Ter assinaturas|
|**Exceções**| Aplicativo dando crash, usuário não assinou podcasts|
|**Episódios**| usuário abre a barra do menu, usuário seleciona a opção de visualizar as assinaturas|

#### C8 - O usuário deve conseguir visualizar seus downloads

|||
|---|---|
|**Versão**|1.0|
|**Autor**| Matheus Sousa |
|**Metas**| Visualizar o conteúdo baixado no aplicativo |
|**Contexto**|**Local:**<br>>Aba de downloads<br> **Pré-Condição:**<br>>Ao menos um episódio baixado<br> **Pós-Condição:**<br>>Aba de episódios aberta |
|**Atores**|Usuário|
|**Recursos**|Aplicativo|
|**Restrições**| Ter episódios baixados|
|**Exceções**| Aplicativo dando crash, usuário não baixou nenhum episódio|
|**Episódios**|Usuário abre a barra do menu, usuário seleciona a opção de visualizar os downloads|

#### C9 - O usuário deve conseguir fazer downloads dos episódios que deseja

|||
|---|---|
|**Versão**|1.0|
|**Autor**| Matheus Sousa |
|**Metas**| Baixar conteúdo no aplicativo |
|**Contexto**|**Local:**<br>>Lista de episódios de um podcast<br> **Pré-Condição:**<br>>Episódio baixado não está disponível<br> **Pós-Condição:**<br>>Episódio baixado |
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo|
|**Restrições**| Episódio não está baixado|
|**Exceções**| Aplicativo dando crash, internet cai|
|**Episódios**|Usuário seleciona o podcast, usuário seleciona a opção de download|

#### C10 - O usuário deve conseguir visualizar os episódios dos podcasts

|||
|---|---|
|**Versão**|1.0|
|**Autor**| Matheus Sousa |
|**Metas**| Conseguir visualizar o conteúdo de cada podcast específico |
|**Contexto**|**Local:**<br>>Lista de episódios de um podcast<br> **Pré-Condição:**<br>>Saber o podcast que deseja visualizar<br> **Pós-Condição:**<br>>O usuário terá conhecimento dos episódios de um podcast específico |
|**Atores**|Usuário|
|**Recursos**|Internet, aplicativo|
|**Restrições**| -|
|**Exceções**| Aplicativo dando crash, internet cai|
|**Episódios**|Usuário seleciona o podcast, usuário vê os episódios dele|

## Referências

2019.2  - Audible. Disponível em <https://requisitos-de-software.github.io/2019.2-Audible/cenarios/>.
