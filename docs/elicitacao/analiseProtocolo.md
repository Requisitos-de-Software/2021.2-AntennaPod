# Análise de Protocolo

## Histórico de Versão

| Data       | Versão | Descrição                                                     | Autor                         | Revisor |
| ---------- | ------ | ------------------------------------------------------------- | ----------------------------- | ------- |
| 11.02.2022 | 1.0    | Criação do documento                                          | [Matheus Sousa](https://github.com/gatotabaco) e [Thais Rebouças](https://github.com/Thais-ra) |    --    |
| 17.02.2022 | 1.1    | Adição da transcrição da entrevista e resultado da elicitação | [Thais Rebouças](https://github.com/Thais-ra)                |   [Abraão Alves](https://github.com/Abraao1231)       |

## Introdução

A análise de protocolo é uma técnica de elicitação de requisitos que consiste em documentar pensamentos e ações de uma pessoa enquanto ela executa determinada tarefa.
Existem dois tipos de análise de protocolo: no protocolo concorrente o usuário verbaliza pensamentos e ações enquanto executa a tarefa e no protocolo retrospectivo um vídeo é gravado enquanto o usuário executa a tarefa, depois ele explica o que estava pensando e fazendo ao executá-la. Quando aplicados juntos, uma maior quantidade de detalhes pode ser obtida. Essa técnica depende da habilidade do usuário em descrever porque está tomando determinada decisão.

## Metodologia

Optamos por aplicar ambos os tipos de análise de protocolo, o concorrente e o retrospectivo, visando obter melhores resultados.
Para realizar a análise o usuário Gabriel, que nunca teve contato com o aplicativo anteriormente, foi convidado para navegar pela aplicação. Foram documentadas as ações e verbalizações do mesmo.

| Entrevistador | Usuário |
| ------------- | ------- |
| [Matheus Sousa](https://github.com/gatotabaco) | Gabriel |

## Participantes
- [Matheus Sousa](https://github.com/gatotabaco)
- [Thais Rebouças](https://github.com/Thais-ra)

## Verbalização do Gabriel

### Tela de Adicionar Podcast
Aqui eu vou procurar um podcast na caixa de pesquisa, no caso o "flow podcast", ele deu várias opções além do que eu queria. Cliquei no podcast e apareceu a opção de assinar, além dos últimos episódios. Cliquei na opção de assinar e fechei. Continuei procurando mais podcasts, eu queria encontrar algum podcast por tema, como "jogadores de futebol". Pesquisei isso na aba mas não retornou nada. "Importar lista de podcast", aqui eu acredito que conseguiria importar um podcast meu pra lá. Esse "pesquisar no iTunes" é pesquisar os podcasts que só tem no iTunes?
Agora vou clicar nesse podcast que aparece aqui, esse "PrimoCast", ai eu assino, cliquei na lateral direita, no ícone de baixar e já está fazendo o download, agora ele já ta no menu lateral e clicando em "downloads" consigo encontrar esse episódio aqui.
Se eu quero procurar "primo rico" será que aparece todos os episódios que ele participou? Só aparece o podcast dele, mas não todas as entrevistas que ele já fez.

### Tela de Assinaturas
Aqui ficam os podcasts que já assinei, vou clicar na lupa para encontrar um episódio específico, no caso "o futuro do flow". Aqui.

### Tela dos podcasts
Aqui tem uma lupa para pesquisar algum episódio, tem como mudar a ordenação, filtrar, atualizar, e tem três pontinhos com mais opções. "visitar website", "compartilhar", "renomear podcast" e "remover podcast". Também tem mais informações sobre o podcast e as configurações dele.

### Menu lateral
Nas opções laterais tem "fila", "episódios", "assinatura", "downloads", "histórico de reprodução", "adicionar podcast" e o podcast que acabei de assinar. Além das configurações logo abaixo.
Quando eu clico no podcast que eu assinei, ele vai parar em uma tela com as informações do podcast.

#### Adicionar PodCast
É por aqui que volta para a tela inicial.

#### Downloads
Aqui ficariam os episódios que eu baixei. Mas como não baixei nenhum por enquanto, tá vazia.

#### Histórico de reprodução
Aqui imagino que ficariam os episódios que eu assisti. Mas tá vazio.

## Resultados

### Requisitos funcionais

| ID    | Descrição                                                                                    |
| ----- | -------------------------------------------------------------------------------------------- |
| APF01 | O usuário deve conseguir se inscrever no podcast que ele deseja                              |
| APF02 | O usuário deve conseguir pesquisar pelos podcasts disponíveis                                |
| APF03 | O usuário deve conseguir pesquisar podcasts disponíveis no iTunes                            |
| APF04 | O usuário deve conseguir pesquisar pelos episódios de cada podcast                           |
| APF05 | O usuário deve conseguir filtrar os episódios de podcast                                     |
| APF06 | O usuário deve conseguir ordenar os episódios de podcast                                     |
| APF07 | O usuário deve conseguir visualizar suas assinaturas                                         |
| APF08 | O usuário deve conseguir visualizar os episódios dos podcasts                                |
| APF09 | O usuário deve conseguir fazer downloads dos episódios que deseja                            |
| APF10 | O usuário deve conseguir visualizar seus downloads                                           |
| APF11 | O usuário deve conseguir importar uma lista de podcast                                       |
| APF12 | O usuário deve ser capaz de navegar no app através de uma barra lateral                      |
| APF13 | O usuário deve conseguir atualizar de lista de episódios                                     |
| APF14 | O usuário deve ser capaz de ser redirecionado para o website do podcast assinado por um link |
| APF15 | O usuário deve conseguir compartilhar o podcast                                              |
| APF16 | O usuário deve ser capaz de compartilhar um episodio (Whatsapp, Facebook, Instagram, etc)    |
| APF17 | O usuário deve conseguir renomear o podcast assinado                                         |
| APF18 | O usuário deve conseguir remover o podcast das suas assinaturas                              |
| APF19 | O usuário deve conseguir visualizar informações sobre o podcast                              |
| APF20 | O usuário deve conseguir alterar a ordem da fila de reprodução                               |
| APF21 | O usuário deve conseguir visualizar o histórico de reprodução                                |

## Referências

https://www.agtic.ufpr.br/pds-ufpr/ProcessoDemoisellePlugin/guidances/guidelines/orientacoesElicitacaoRequisitos_3AF37DEB.html
