# Priorização: R$ 100

## Histórico de versões
| Data       | Versão | Descrição                                                | Autor                                        | Revisor                                       |
| ---------- | ------ | -------------------------------------------------------- | -------------------------------------------- | --------------------------------------------- |
| 18.02.2022 | 1.0    | Criação do documento                                     | [Yudi Yamane](https://github.com/yudi-azvd)  | --                                            |
| 23.02.2022 | 1.1    | Renomeação do documento e esclarecimento da ténica R$100 | [Yudi Yamane](https://github.com/yudi-azvd)  | [Thais Rebouças](https://github.com/Thais-ra) |
| 14.04.2022 | 1.2    | Adição dos links para as técnicas                        | [Amanda Nobre](https://github.com/AmandaNbr) | -                                             |

## Introdução

Nem todos os requisitos devem ser imediatamente implementados. Por isso existe
um processo de priorização de requisitos, no qual são definidos aqueles que
têm mais importância no momento e, portanto, devem ser implementados primeiro.

A técnica de priorização utilizada foi a de R$ 100. Consiste em imaginar que o
orçamento do projeto é de R$ 100 para realizar todos os requisitos. Então cada 
requisito é analisado e discutido qual o seu preço, ou seja, quantos reais a equipe
está disposta a pagar para "comprá-lo" e realizá-lo. Quanto maior essa quantidade,
maior é a prioridade do requisito.

## Participantes

Os participantes para essa técnica são os integrantes da equipe do projeto:

- [Abraão Alves](https://github.com/Abraao1231) 
- [Amanda Nobre](https://github.com/AmandaNbr)
- [Thais Rebouças](https://github.com/Thais-ra)
- [Matheus Calixto](https://github.com/matheuscvp)
- [Matheus Sousa](https://github.com/gatotabaco)
- [Yudi Yamane](https://github.com/yudi-azvd)

## Metodologia
Em reunião no Discord, os requisitos levantados pelos participantes foram colocados
em uma planilha do Google Sheets, um em cada linha. Em seguida, a cada requisito 
foi atribuído uma quantia em reais. 

Para ter uma base de onde começar com essa técnica, nós dividimos o valor de R$ 
100 pela a quantidade de requisitos funcionais e não funcionais. Assim, temos uma
noção de como ficaria a precificação se o orçamento de R$ 100 fosse divido igualmente
para todos os requisitos, que resulta aproximadamente em R$ 1,60 por requisito. 
Usamos esse valor como referência para requisito com prioridade média apenas para
os primeiros requisitos analisados. Com o passar dos requisitos, a noção de valor
para prioridade média foi aumentando naturalmente.

## Resultado

### Requisitos Funcionais

O resultado da elicitação e priorização pode ser visto na tabela abaixo ordenado
em ordem descrescente pelo preço do requisito:

| ID   | Descrição                                                                                    | Técnica                                                                                                         | R$   |
| ---- | -------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- | ---- |
| RF37 | O usuário deve ser capaz de reproduzir e pausar episódios de podcasts                        | [Brainstorm](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/brainstorm/)                 | 6,00 |
| RF26 | O usuário deve ser capaz de assinar um podcast                                               | [Brainstorm](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/brainstorm/)                 | 4,00 |
| RF61 | O usuário deve ser capaz de, ao reproduzir, avançar um ep e voltar um ep                     | [Introspecção](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/introspeccao/)             | 4,00 |
| RF01 | O usuário deve conseguir ouvir um episódio sem precisar se inscrever em seu podcast          | [Observação](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/observacao/)                 | 3,00 |
| RF02 | O usuário deve conseguir baixar um podcast sem precisar se inscrever no mesmo                | [Observação](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/observacao/)                 | 3,00 |
| RF10 | O usuário deve conseguir visualizar suas assinaturas                                         | [Análise de Protocolo](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/analiseProtocolo/) | 3,00 |
| RF11 | O usuário deve conseguir visualizar seus downloads                                           | [Análise de Protocolo](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/analiseProtocolo/) | 3,00 |
| RF12 | O usuário deve conseguir fazer downloads dos episódios que deseja                            | [Análise de Protocolo](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/analiseProtocolo/) | 3,00 |
| RF13 | O usuário deve conseguir visualizar os episódios dos podcasts                                | [Análise de Protocolo](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/analiseProtocolo/) | 3,00 |
| RF23 | O usuário deve ser capaz de pesquisar um episódio pelo criador do podcast                    | [Brainstorm](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/brainstorm/)                 | 3,00 |
| RF24 | O usuário deve ser capaz de pesquisar um podcast pelo título                                 | [Brainstorm](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/brainstorm/)                 | 3,00 |
| RF29 | O usuário deve ser capaz de visualizar todos os episódios dos podcasts assinados             | [Brainstorm](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/brainstorm/)                 | 3,00 |
| RF57 | O usuário deve ser capaz de alterar o tema (visual) do aplicativo                            | [Introspecção](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/introspeccao/)             | 3,00 |
| RF60 | O usuário deve ser capaz de navegar no app através da barra lateral                          | [Introspecção](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/introspeccao/)             | 3,00 |
| RF62 | O usuário deve ser capaz de, ao reproduzir, avançar 10 s e voltar 10 s em um ep              | [Introspecção](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/introspeccao/)             | 3,00 |
| RF27 | O usuário deve ser capaz de desassinar um podcast                                            | [Brainstorm](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/brainstorm/)                 | 2,50 |
| RF03 | O usuário deve conseguir acessar de forma direta e fácil de acessar a página principal       | [Observação](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/observacao/)                 | 2,00 |
| RF16 | O usuário deve conseguir visualizar informações sobre o podcast                              | [Análise de Protocolo](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/analiseProtocolo/) | 2,00 |
| RF22 | O usuário deve conseguir visualizar o histórico de reprodução                                | [Análise de Protocolo](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/analiseProtocolo/) | 2,00 |
| RF25 | O usuário deve ser capaz de pesquisar um podcast por categoria                               | [Brainstorm](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/brainstorm/)                 | 2,00 |
| RF28 | O usuário deve ser capaz de receber notificação de novos episódios de podcasts assinados     | [Brainstorm](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/brainstorm/)                 | 2,00 |
| RF30 | O usuário deve ser capaz de ordenar episódios de podcasts assinados por titulo               | [Brainstorm](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/brainstorm/)                 | 2,00 |
| RF33 | O usuário deve ser capaz de visualizar todos os novos episódios dos podcasts assinados       | [Brainstorm](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/brainstorm/)                 | 2,00 |
| RF38 | O usuário deve ser capaz de adicionar um episódio a fila de reprodução                       | [Brainstorm](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/brainstorm/)                 | 2,00 |
| RF43 | O usuário deve ser capaz de remover um episódio de podcast dos baixados                      | [Brainstorm](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/brainstorm/)                 | 2,00 |
| RF20 | O usuário deve ser capaz de compartilhar um episodio (Whatsapp, Facebook, Instagram, etc)    | [Análise de Protocolo](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/analiseProtocolo/) | 1,50 |
| RF47 | O usuário deve ser capaz de mudar velocidade de reprodução de um episódio                    | [Brainstorm](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/brainstorm/)                 | 1,50 |
| RF52 | O usuário deve ser capaz de visualizar podcasts recomendados de acordo com o gosto           | [Brainstorm](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/brainstorm/)                 | 1,50 |
| RF53 | O usuário deve ser capaz de visualizar sugestões dos podcasts mais escutados                 | [Brainstorm](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/brainstorm/)                 | 1,50 |
| RF58 | O usuário deve ser capaz de visualizar estatísticas de horas de reprodução                   | [Introspecção](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/introspeccao/)             | 1,50 |
| RF06 | O usuário deve conseguir pesquisar pelos episódios de cada podcast                           | [Análise de Protocolo](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/analiseProtocolo/) | 1,00 |
| RF14 | O usuário deve conseguir importar uma lista de podcast                                       | [Análise de Protocolo](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/analiseProtocolo/) | 1,00 |
| RF21 | O usuário deve conseguir alterar a ordem da fila de reprodução                               | [Análise de Protocolo](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/analiseProtocolo/) | 1,00 |
| RF31 | O usuário deve ser capaz de ordenar episódios de podcasts assinados por duração              | [Brainstorm](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/brainstorm/)                 | 1,00 |
| RF32 | O usuário deve ser capaz de ordenar episódios de podcasts assinados por data                 | [Brainstorm](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/brainstorm/)                 | 1,00 |
| RF34 | O usuário deve ser capaz de retirar a flag de "novo" de um episodio                          | [Brainstorm](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/brainstorm/)                 | 1,00 |
| RF36 | O usuário deve ser capaz de ser redirecionado para o website do podcast assinado por um link | [Brainstorm](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/brainstorm/)                 | 1,00 |
| RF39 | O usuário deve ser capaz de remover um episódio da fila de reprodução                        | [Brainstorm](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/brainstorm/)                 | 1,00 |
| RF48 | O usuário deve ser capaz de favoritar episódios                                              | [Brainstorm](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/brainstorm/)                 | 1,00 |
| RF50 | O usuário deve ser capaz de visualizar episodios favoritados                                 | [Brainstorm](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/brainstorm/)                 | 1,00 |
| RF59 | O usuário deve ser capaz de visualizar estatísticas do tamanho dos downloads                 | [Introspecção](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/introspeccao/)             | 1,00 |
| RF63 | O usuário deve ser capaz de realizar um backup de dados                                      | [Introspecção](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/introspeccao/)             | 1,00 |
| RF07 | O usuário deve conseguir pesquisar podcasts disponíveis no iTunes                            | [Análise de Protocolo](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/analiseProtocolo/) | 0,50 |
| RF18 | O usuário deve conseguir renomear o podcast assinado                                         | [Análise de Protocolo](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/analiseProtocolo/) | 0,50 |
| RF45 | O usuário deve ser capaz de visualizar logs dos downloads                                    | [Brainstorm](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/brainstorm/)                 | 0,50 |
| RF49 | O usuário deve ser capaz de desfavoritar episódios                                           | [Brainstorm](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/brainstorm/)                 | 0,50 |
| RF51 | O usuário deve ser capaz de criar playlist de episódios                                      | [Brainstorm](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/brainstorm/)                 | 0,50 |
| RF54 | O usuário deve ser capaz de visualizar podcasts por país                                     | [Brainstorm](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/brainstorm/)                 | 0,50 |
| RF56 | O usuário deve ser capaz de sincronizar o aplicativo com a conta do gpodder.net              | [Introspecção](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/introspeccao/)             | 0,50 |

### Requisitos Não Funcionais

| ID    | Descrição                                               | Técnica                                                                                         | R$   |
| ----- | ------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | ---- |
| RNF01 | O aplicativo não requer cadastro                        | [Brainstorm](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/brainstorm/) | 3,00 |
| RNF02 | O aplicativo deve ser intuitivo                         | [Brainstorm](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/brainstorm/) | 2,00 |
| RNF03 | O aplicativo deverá rodar em qualquer plataforma mobile | [Brainstorm](https://requisitos-de-software.github.io/2021.2-AntennaPod/elicitacao/brainstorm/) | 1,50 |

## Referências

WIEGERS, Karl et al. First things first: Setting requirement priorities: $100. In: SOFTWARE Requirements. 3. ed. [S. l.: s. n.], 2013. cap. 16, p. 321-322.