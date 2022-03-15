# Léxicos

## Histórico de versões
| Data       | Versão | Descrição            | Autor                                        | Revisor                                     |
| ---------- | ------ | -------------------- | -------------------------------------------- | ------------------------------------------- |
| 25.02.2022 | 1.0    | Criação do documento | [Amanda Nobre](https://github.com/AmandaNbr) | [Yudi Yamane](https://github.com/yudi-azvd) |
| 13.03.2022 | 1.1    | Dividindo por tipo e colocando em ordem alfabética | [Amanda Nobre](https://github.com/AmandaNbr) | [Yudi Yamane](https://github.com/yudi-azvd) |

## Introdução

Léxico é uma técnica de modelagem que tem como objeto principal a própria linguagem, pois busca descrever símbolos (palavras chave e frases recorrentes no desenvolvimento do projeto) para mapeá-los e entender as noções e impactos de cada símbolo levantado.

A descrição de símbolos ocorre das 3 seguintes formas:

| Tipo   | Noção                                                                    | Impacto                                                                                                      |
| ------ | ------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ |
| VERBO  | Quem realiza, quando acontece e quais os procedimentos envolvidos.       | Quais os reflexos da ação no ambiente (outras ações que devem ocorrer) e quais os novos estados decorrentes. |
| OBJETO | Definir o objeto e identificar outros objetos com os quais se relaciona. | Ações que podem ser aplicadas ao objeto.                                                                     |
| ESTADO | O que significa e quais ações levaram a esse estado.                     | Identificar outros estados e ações que podem ocorrer a partir do estado que se descreve.                     |


## Metodologia

Para definir os léxicos foi feita uma introspecção através da navegação nos artefatos e requisitos levantados e, a partir disso, os símbolos foram coletados. 
Os léxicos estão organizados por tipo, em ordem alfabética e seguindo o seguinte modelo:

| LXX       | Nome do Léxico            |
| --------- | ------------------------- |
| Tipo      | (Verbo, objeto ou estado) |
| Sinônimos | Sinônimos do léxico       |
| Noção     | Noção do léxico           |
| Impacto   | Impactos do léxico        |
| Autor     | Autor do léxico           |

## Participantes

- [Amanda Nobre](https://github.com/AmandaNbr)

## Resultados

### ESTADO

#### Léxico 01 - Duração

| L01       | Duração                                                     |
| --------- | ----------------------------------------------------------- |
| Tipo      | Estado                                                      |
| Sinônimos | Tempo                                                       |
| Noção     | Tempo de duração de um episódio                             |
| Impacto   | O usuário pode visualizar o tempo de duração de um episódio |
| Autor     | [Amanda Nobre](https://github.com/AmandaNbr)                |

#### Léxico 02 - Fila de reprodução

| L02       | Fila de reprodução                                   |
| --------- | ---------------------------------------------------- |
| Tipo      | Estado                                               |
| Sinônimos | -                                                    |
| Noção     | Fila episódios que serão reproduzidos em sequência   |
| Impacto   | O usuário pode inserir um episódio na fila           |
|           | O usuário pode retirar um episódio da fila           |
|           | O usuário pode visulizar a fila de reprodução        |
|           | O usuário pode mudar a posição dos episódios na fila |
| Autor     | [Amanda Nobre](https://github.com/AmandaNbr)         |

#### Léxico 03 - Novo

| L03       | Novo                                                          |
| --------- | ------------------------------------------------------------- |
| Tipo      | Estado                                                        |
| Sinônimos | Recente, inédito                                              |
| Noção     | Um episódio ao ser postado recebe a identificação de "novo"   |
| Impacto   | O usuário pode visualizar os novos episódios facilmente       |
|           | O usuário pode tirar a identificação de "novo" de um episódio |
| Autor     | [Amanda Nobre](https://github.com/AmandaNbr)                  |

#### Léxico 04 - Velocidade de reprodução

| L04       | Velocidade de reprodução                          |
| --------- | ------------------------------------------------- |
| Tipo      | Estado                                            |
| Sinônimos | -                                                 |
| Noção     | Velocidade de reprodução de um episódio           |
| Impacto   | O usuário pode alterar a velocidade de reprodução |
| Autor     | [Amanda Nobre](https://github.com/AmandaNbr)      |

### OBJETO

#### Léxico 05 - Canal

| L05       | Canal                                                                    |
| --------- | ------------------------------------------------------------------------ |
| Tipo      | Objeto                                                                   |
| Sinônimos | Criador de conteúdo                                                      |
| Noção     | Pessoa ou organização que posta o PodCasts                               |
| Impacto   | O AntennaPod disponibiliza os canais para serem assinados e visualizados |
| Autor     | [Amanda Nobre](https://github.com/AmandaNbr)                             |

#### Léxico 06 - Episódio

| L06       | Episódio                                                                    |
| --------- | --------------------------------------------------------------------------- |
| Tipo      | Objeto                                                                      |
| Sinônimos | Capítulo                                                                    |
| Noção     | Episódio de um PodCast de um canal e disponibilizado pelo AntennaPod        |
| Impacto   | O AntennaPod disponibiliza os episódios de PodCasts para serem reproduzidos |
| Autor     | [Amanda Nobre](https://github.com/AmandaNbr)                                |

#### Léxico 07 - Histórico

| L07       | Histórico                                                  |
| --------- | ---------------------------------------------------------- |
| Tipo      | Objeto                                                     |
| Sinônimos | -                                                          |
| Noção     | Lista de episódios reproduzidos                            |
| Impacto   | O usuário pode visulizar a lista de episódios reproduzidos |
|           | O usuário pode limpar a lista de episódios reproduzidos    |
| Autor     | [Amanda Nobre](https://github.com/AmandaNbr)               |

#### Léxico 08 - PodCast

| L08       | PodCast                                          |
| --------- | ------------------------------------------------ |
| Tipo      | Objeto                                           |
| Sinônimos | -                                                |
| Noção     | Arquivo digital de áudio                         |
| Impacto   | O usuário ouve PodCasts no aplicativo AntennaPod |
| Autor     | [Amanda Nobre](https://github.com/AmandaNbr)     |

#### Léxico 09 - Usuário

| L09       | Usuário                                      |
| --------- | -------------------------------------------- |
| Tipo      | Objeto                                       |
| Sinônimos | Utilizador, cliente                          |
| Noção     | Quem utiliza o aplicativo                    |
| Impacto   | O usuário instala o AntennaPod               |
|           | O usuário ouve PodCasts                      |
|           | O usuário se inscreve em canais              |
| Autor     | [Amanda Nobre](https://github.com/AmandaNbr) |

### VERBO

#### Léxico 10 - Assinar

| L10       | Assinar                                                                 |
| --------- | ----------------------------------------------------------------------- |
| Tipo      | Verbo                                                                   |
| Sinônimos | Inscrever-se                                                            |
| Noção     | O usuário assina um canal de PodCast                                    |
| Impacto   | O usuário, após assinar o canal, tem acesso aos episódios               |
|           | O usuário, após assinar o canal, recebe notificações de novos episódios |
| Autor     | [Amanda Nobre](https://github.com/AmandaNbr)                            |

#### Léxico 11 - Atualizar

| L11       | Atualizar                                                                           |
| --------- | ----------------------------------------------------------------------------------- |
| Tipo      | Verbo                                                                               |
| Sinônimos | Renovar                                                                             |
| Noção     | O usuário pode atualizar a página                                                   |
| Impacto   | O usuário, ao atualizar a página, verá ou não alguma mudança, como um novo episódio |
| Autor     | [Amanda Nobre](https://github.com/AmandaNbr)                                        |

#### Léxico 12 - Baixar

| L12       | Baixar                                                                                                        |
| --------- | ------------------------------------------------------------------------------------------------------------- |
| Tipo      | Verbo                                                                                                         |
| Sinônimos | Fazer download                                                                                                |
| Noção     | O usuário pode baixar um episódio                                                                             |
| Impacto   | O usuário pode fazer download do conteúdo de forma a ser possível ouvir o PodCast sem conexão com à Internet. |
| Autor     | [Amanda Nobre](https://github.com/AmandaNbr)                                                                  |

#### Léxico 13 - Descobrir

| L13       | Descobrir                                                                  |
| --------- | -------------------------------------------------------------------------- |
| Tipo      | Verbo                                                                      |
| Sinônimos | Recomendados, sugestões                                                    |
| Noção     | Títulos selecionados de acordo com os gostos do seu perfil ou mais ouvidos |
| Impacto   | O usuário poderá visualizar PodCasts recomendados                          |
|           | O usuário poderá reproduzir PodCasts recomendados                          |
| Autor     | [Amanda Nobre](https://github.com/AmandaNbr)                               |

#### Léxico 14 - Favoritar

| L14       | Favoritar                                                   |
| --------- | ----------------------------------------------------------- |
| Tipo      | Verbo                                                       |
| Sinônimos | Gostar, curtir                                              |
| Noção     | O usuário favorita um episódio que gosta                    |
| Impacto   | O usuário pode adicionar ou remover episódios dos favoritos |
|           | O usuário visualizar a lista de favoritos                   |
| Autor     | [Amanda Nobre](https://github.com/AmandaNbr)                |

#### Léxico 15 - Filtrar

| L15       | Filtrar                                                                                           |
| --------- | ------------------------------------------------------------------------------------------------- |
| Tipo      | Verbo                                                                                             |
| Sinônimos | Separar, escolher                                                                                 |
| Noção     | O usuário pode filtrar as pesquisas                                                               |
| Impacto   | O usuário pode filtrar PodCasts por país                                                          |
|           | O usuário pode filtrar episódios por reproduzidos, favoritados, pausados, está na fila e baixados |
| Autor     | [Amanda Nobre](https://github.com/AmandaNbr)                                                      |

#### Léxico 16 - Pesquisar

| L16       | Pesquisar                                                    |
| --------- | ------------------------------------------------------------ |
| Tipo      | Verbo                                                        |
| Sinônimos | Buscar, procurar                                             |
| Noção     | O usuário pode pesquisar um PodCast, um episódio ou um canal |
| Impacto   | O usuário poderá pesquisar por um título específico          |
| Autor     | [Amanda Nobre](https://github.com/AmandaNbr)                 |

#### Léxico 17 - Reproduzir

| L17       | Reproduzir                                                            |
| --------- | --------------------------------------------------------------------- |
| Tipo      | Verbo                                                                 |
| Sinônimos | Apresentar, exibir, dar play, ouvir                                   |
| Noção     | O usuário reproduz um episódio de um PodCast                          |
| Impacto   | O usuário pode pausar o episódio                                      |
|           | O usuário pode avançar 30 segundos e retornar 10 segundos no episódio |
|           | O usuário pode avançar outro episodio da fila                         |
|           | O usuário pode mudar a velocidade de reprodução                       |
| Autor     | [Amanda Nobre](https://github.com/AmandaNbr)                          |

## Referências

SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 10.

REQUISITOS DE SOFTWARE, DisneyPlus 2021.1. Léxicos. Disponível em: <https://requisitos-de-software.github.io/2021.1-DisneyPlus/modelagem/lexicos/#l04-conta>
