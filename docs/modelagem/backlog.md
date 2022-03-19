# Backlog

## Histórico de versões
| Data       | Versão | Descrição                                   | Autor                                         | Revisor                                        |
| ---------- | ------ | ------------------------------------------- | --------------------------------------------- | ---------------------------------------------- |
| 04.02.2022 | 1.0    | Criação do documento e adição da introdução | [Thaís Rebouças](https://github.com/Thais-ra) | [Yudi Yamane](https://github.com/yudi-azvd)    |
| 05.02.2022 | 1.1    | Adição das histórias de usuário             | [Thaís Rebouças](https://github.com/Thais-ra) | [Yudi Yamane](https://github.com/yudi-azvd)    |
| 08.02.2022 | 1.2    | Criação das features e épicos               | [Thaís Rebouças](https://github.com/Thais-ra) | [Yudi Yamane](https://github.com/yudi-azvd)    |
| 19.03.2022 | 1.3    | Adição do id de cada requisito              | [Thaís Rebouças](https://github.com/Thais-ra) | [Matheus Sousa](https://github.com/gatotabaco) |


## Introdução
### Backlog

Backlog é uma lista com itens descrevendo as necessidades do usuário que o produto busca suprir. Existem várias maneiras de organizar o Backlog, um modelo estrutural muito utilizado é o conjunto de Epic, Feature and Story – Épico, Funcionalidade e História.

### Histórias de usuários
Histórias de usuários (User Story) são descrições curtas, informais e em linguagem simples do que um usuário pode fazer no contexto do produto de software para obter algo de valor. Dessa forma os usuários se tornam o centro da conversa quando se trata de adicionar ou alterar em um produto de software. Ela é a menor unidade de trabalho com base na necessidade do cliente final que vai utilizar e/ou interagir com o Produto.

Normalmente as histórias de usuários seguem o padrão de papel-função-benefício:

Eu, como _[tipo de usuario]_, desejo _[uma ação]_ para _[um benefício/valor]_.

### Funcionalidade

A Funcionalidade (Feature) é responsável por agrupar um conjunto de histórias de usuário. A Funcionalidade expressa uma função do Produto, da qual contém diversos requisitos funcionais com suas regras e exceções. Ela está relacionada a uma Funcionalidade em médio ou alto nível dentro do Produto e por isso precisa de requisitos funcionais e não funcionais expressos por Histórias de usuários. Quando todas as histórias da Funcionalidade estiverem prontas, considera-se a Feature concluída.

### Épico

O Épico (Epic) é uma grande parte do trabalho a ser realizado no Produto. É também conhecido como uma Grande História de Usuário, da qual expressa de forma macro a necessidade global. Todos os épicos devem representar a entrega integral do Produto. Eles são formados por Funcionalidades, ou seja, após a entrega de todas elas, considera-se que o Épico esteja finalizado


## Metodologia

Para a confecção do backlog utilizamos o método de instrospecção, análise do aplicativo e revisão
dos requisitosfuncionais e não funcionais. A partir disto geramos os temas e épicos, as histórias
de usuário, e então definimos o backlog do produto.

## Participantes

- [Thaís Rebouças](https://github.com/Thais-ra)

## Resultados

EP é para Épico e FT é para Feature.

### EP01: Reprodução de episódios 
### FT01: Modo de reprodução
| USID | Histórias de Usuário                                                                                                                  | ID Requisitos |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| US05 | Eu, como usuário, desejo ouvir um episódio sem precisar me inscrever no podcast para saber se o conteúdo me agrada antes de assiná-lo | RF01          |
| US03 | Eu, como usuário, desejo avançar e voltar um episódio para controlar a reprodução do que estou assistindo                             | RF61          |
| US01 | Eu, como usuário, desejo reproduzir e pausar episódios de podcast para controlar a reprodução do que estou assistindo                 | RF37          |
| US02 | Eu, como usuário, desejo avançar 10s e/ou voltar 10s em um episódio para controlar a reprodução do que estou assistindo               | RF62          |
| US04 | Eu, como usuário, desejo mudar velocidade de reprodução de um episódio para acompanhar o meu ritmo                                    | RF47          |

### FT02: Lista de reprodução
| USID | Histórias de Usuário                                                                                                             | ID Requisitos |
| ---- | -------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| US08 | Eu, como usuário, desejo adicionar um episódio a fila de reprodução para ordenar o conteúdo que vou assistir                     | RF38          |
| US09 | Eu, como usuário, desejo alterar a ordem da fila de reprodução para dar a prioridade que quero aos conteúdos que quero consumir  | RF21          |
| US07 | Eu, como usuário, desejo retirar a flag de "novo" de um episódio para sinalizar que aquele episódio não é mais novo para mim     | RF34          |
| US10 | Eu, como usuário, desejo remover um episódio da fila de reprodução para dar espaço para outros episódio que tenho mais interesse | RF39          |
| US11 | Eu, como usuário, desejo criar playlist de episódios para agrupar episódios de forma que faz sentido para mim                    | RF51          |

### FT03: Histórico de reprodução

| USID | Histórias de Usuário                                                                                 | ID Requisitos |
| ---- | ---------------------------------------------------------------------------------------------------- | ------------- |
| US06 | Eu, como usuário, desejo visualizar o histórico de reprodução para lembrar dos episódios que já ouvi | RF22          |


### EP02: Acesso offline
### FT04: Downloads
| USID  | Histórias de Usuário                                                                                                                                       | ID Requisitos |
| ----- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| US015 | Eu, como usuário, desejo baixar um episódio sem precisar assinar o podcast para ter acesso offline àquele episódio mesmo que o podcast não me agrade tanto | RF02          |
| US012 | Eu, como usuário, desejo baixar episódios para ter acesso aos mesmos de modo offline                                                                       | RF12          |
| US013 | Eu, como usuário, desejo remover um episódio de podcast dos baixados para organizar os conteúdos que quero ter offline                                     | RF43          |
| US014 | Eu, como usuário, desejo visualizar logs dos downloads para saber se tudo ocorreu como o esperado                                                          | RF45          |

### FT05: Visualização de downloads
| USID  | Histórias de Usuário                                                                | ID Requisitos |
| ----- | ----------------------------------------------------------------------------------- | ------------- |
| US016 | Eu, como usuário, desejo visualizar meus downloads para encontrá-los com facilidade | RF11          |


### EP03: Assinaturas
### FT06: Gerenciamento de assinaturas
| USID | Histórias de Usuário                                                                                                | ID Requisitos |
| ---- | ------------------------------------------------------------------------------------------------------------------- | ------------- |
| US17 | Eu, como usuário, desejo assinar um podcast para ter acesso a ele de forma fácil                                    | RF26          |
| US18 | Eu, como usuário, desejo desassinar um podcast para conseguir manter minha lista de assinaturas sempre ao meu gosto | RF27          |

### FT07: Visualização de assinaturas
| USID | Histórias de Usuário                                                                                                           | ID Requisitos |
| ---- | ------------------------------------------------------------------------------------------------------------------------------ | ------------- |
| US19 | Eu, como usuário, desejo visualizar minhas assinaturas para encontrar todos os podcasts que gosto em um lugar só               | RF10          |
| US21 | Eu, como usuário, desejo visualizar todos os episódios dos podcasts assinados para ter acesso fácil aos conteúdos que gosto    | RF29          |
| US22 | Eu, como usuário, desejo visualizar todos os novos episódios dos podcasts assinados para encontrar as novidades em um só lugar | RF33          |

### FT08: Ordenação
| USID | Histórias de Usuário                                                                                                                                       | ID Requisitos |
| ---- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| US23 | Eu, como usuário, desejo ordenar episódios de podcasts assinados por titulo para encontrar os episódios mais facilmente                                    | RF30          |
| US24 | Eu, como usuário, desejo ordenar episódios de podcasts assinados por duração para escolher qual episódio assistir baseado no tempo que eu tenho disponível | RF31          |
| US25 | Eu, como usuário, desejo ordenar episódios de podcasts assinados por data para escolher os episódios mais ou menos atuais                                  | RF32          |


### EP04: Pesquisas
### FT09: Por podcasts
| USID | Histórias de Usuário                                                                                                            | ID Requisitos |
| ---- | ------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| US26 | Eu, como usuário, desejo pesquisar um podcast pelo título para encontrar um podcast facilmente em uma lista com muitos podcasts | RF24          |
| US27 | Eu, como usuário, desejo pesquisar um podcast por categoria para encontrar podcasts por área de interesse                       | RF25          |
| US28 | Eu, como usuário, desejo pesquisar podcasts disponíveis no iTunes para ter acesso aos podcasts do iTunes também                 | RF07          |
| US29 | Eu, como usuário, desejo visualizar podcasts por país para visualizar podcasts de países que me interessam                      | RF54          |

### FT10: Por episódios
| USID | Histórias de Usuário                                                                                                               | ID Requisitos |
| ---- | ---------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| US30 | Eu, como usuário, desejo pesquisar um episódio pelo criador do podcast para encontrar um episódio que eu não saiba o nome          | RF23          |
| US31 | Eu, como usuário, desejo pesquisar um episódio pelo título para encontrar um episódio facilmente em uma lista com muitos episódios | RF06          |

### FT11: Informações
| USID | Histórias de Usuário                                                                                               | ID Requisitos |
| ---- | ------------------------------------------------------------------------------------------------------------------ | ------------- |
| US20 | Eu, como usuário, desejo visualizar os episódios de cada podcasts para decidir se vou assinar                      | RF13          |
| US32 | Eu, como usuário, desejo visualizar informações sobre o podcast para conhecer melhor o conteúdo antes de assiná-lo | RF16          |


### EP05: Navegação personalizada
### FT12: Aparencia
| USID | Histórias de Usuário                                                                          | ID Requisitos |
| ---- | --------------------------------------------------------------------------------------------- | ------------- |
| US36 | Eu, como usuário, desejo alterar o tema (visual) do aplicativo para personalizar o aplicativo | RF57          |

### FT13: Recomendação
| USID | Histórias de Usuário                                                                                                                                       | ID Requisitos |
| ---- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| US34 | Eu, como usuário, desejo visualizar podcasts recomendados de acordo com o meu gosto para encontrar facilmente podcasts diferentes que atenda ao meu perfil | RF52          |
| US33 | Eu, como usuário, desejo visualizar sugestões dos podcasts mais escutados para explorar novos assuntos                                                     | RF53          |

### FT14: Dados estatisticos
| USID | Histórias de Usuário                                                                                                                                         | ID Requisitos |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------- |
| US40 | Eu, como usuário, desejo visualizar estatísticas de horas de reprodução para ter mais controle do meu tempo no aplicativo                                    | RF58          |
| US41 | Eu, como usuário, desejo visualizar estatísticas do tamanho dos downloads para saber quanto da minha memória está sendo ocupada pelos episódios que eu baixo | RF59          |

### FT15: Favoritos
| USID | Histórias de Usuário                                                                            | ID Requisitos |
| ---- | ----------------------------------------------------------------------------------------------- | ------------- |
| US38 | Eu, como usuário, desejo favoritar episódios para ouvir de novo em algum momento                | RF48          |
| US37 | Eu, como usuário, desejo visualizar episodios favoritados para visualizar os melhores episódios | RF50          |
| US39 | Eu, como usuário, desejo desfavoritar episódios para dar espaço a outros episódios melhores     | RF49          |

### FT16: Renomear
| USID | Histórias de Usuário                                                                              | ID Requisitos |
| ---- | ------------------------------------------------------------------------------------------------- | ------------- |
| US35 | Eu, como usuário, desejo renomear o podcast assinado para personalizar como eu quero cada podcast | RF18          |


### EP06: Usabilidade
### FT17: Compartilhar
| USID | Histórias de Usuário                                                                                                              | ID Requisitos |
| ---- | --------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| US42 | Eu, como usuário, desejo compartilhar um episodio (Whatsapp, Facebook, Instagram, etc) para divulgar um conteúdo do meu interesse | RF20          |

### FT18: Navegação
| USID | Histórias de Usuário                                                                                                                                          | ID Requisitos |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| US43 | Eu, como usuário, desejo navegar no app através da barra lateral para encontrar oque quero com mais facilidade                                                | RF60          |
| US44 | Eu, como usuário, desejo acessar de forma direta e fácil a página principal para encontrar as principais funcionalidades mais facilmente                      | RF03          |
| US46 | Eu, como usuário, desejo ser redirecionado para o website do podcast assinado por um link para acessar facilmente o website do podcast que estou visualizando | RF36          |
| US45 | Eu, como aplicativo, desejo ser intuitivo para os usuários conseguirem navegar facilmente                                                                     | RNF02         |

### FT19: Notificação
| USID | Histórias de Usuário                                                                                     | ID Requisitos |
| ---- | -------------------------------------------------------------------------------------------------------- | ------------- |
| US47 | Eu, como aplicação, desejo notificar novos episódios dos podcasts para o usuário estar sempre atualizado | RF28          |

### FT20: Backup e Sincronização
| USID | Histórias de Usuário                                                                                                            | ID Requisitos |
| ---- | ------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| US52 | Eu, como usuário, desejo importar uma lista de podcast para recuperar meus dados                                                | RF14          |
| US50 | Eu, como usuário, desejo realizar um backup de dados para ter acesso a minha conta em um celular diferente, ou após formata-lo  | RF63          |
| US51 | Eu, como usuário, desejo sincronizar o aplicativo com a conta do gpodder.net para salvar as atividades realizadas no aplicativo | RF56          |
| US49 | Eu, como aplicativo, desejo não requerer cadastro para o usuário acessar a plataforma                                           | RNF01         |

### FT21: Plataforma
| USID | Histórias de Usuário                                                                          | ID Requisitos |
| ---- | --------------------------------------------------------------------------------------------- | ------------- |
| US48 | Eu, como aplicativo, desejo rodar em qualquer plataforma mobile para ser acessível para todos | RNF03         |

## Referências

- Artefato: Backlog do Produto. TRT9. Disponível em: https://www.trt9.jus.br/pds/Scrum/workproducts/product_backlog_68345C16.html. Acesso em: 04 de Março de 2022.

- Histórias de usuários: o que são, por que e como usá-los. Digite. Disponível em: https://www.digite.com/pt-br/agile/historias-de-usuarios. Acesso em: 04 de Março de 2022.

- Epic, Feature and Story – Épico, Funcionalidade e História. O dono do produto. Disponível em: https://odonodoproduto.com/epic-feature-and-story-epico-funcionalidade-e-historia. Acesso em: 04 de Março de 2022.



