# Casos de Uso

## Histórico de versões
| Data       | Versão | Descrição            | Revisores      | Autor(es)   |
| ---------- | ------ | -------------------- | -------------- | ----------- |
| 24.02.2022 | 1.0    | Criação do documento | Thais Rebouças | Yudi Yamane |

## Introdução

Um caso de uso descreve os vários passos de uma interação, de atividade 
individual, entre o sistema e um agente externo a fim de atingir um objetivo de
valor. O nome de um caso de uso é escrito com um verbo e um objeto, a exemplo:
"Ouvir um episódio".

Casos de uso podem ser representado tanto por diagramas UML quanto por tabelas.
Nos diagramas existem vários elementos gráficos como atores principais e secundários,
casos de uso, sistema, relacionamentos e etc. Por outro lado, as tabelas descrevem
as características: atores, descrição, pré condições, fluxos principais, alternativos
e de exceção, pós condições e rastreabilidade.

### Relacionamentos

São interações entre objetos de um diagrama de casos de uso, representados
por linhas ou setas. Tipos:

- **Associação**: relacionamento básico entre dois objetos. Exemplo: cliente realiza 
login.

- **Inclusão**: relacionamento entre casos de uso (UC) de maneira que se o UC A inclui
o UC B, então toda vez que UC A for executado, UC B também será executado. Exemplo:
fazer login <<inclui\>\> verificar senha.

- **Extensão**: relacionamento entre casos de uso de maneira que o caso de uso acontece,
mas o caso de uso estendido nem sempre acontece, ou seja, acontece somente mediante
a alguns critérios particulares. Exemplo: Fazer login <<estende\>\> Mostrar tela 
de erro de login.

### Atores

Em casos de uso temos dois tipos de atores:

- **Atores principais**: atores que iniciam (trigger) o caso de uso. É quem realmente 
obtém valor do sucesso do caso de uso

- **Atores secundários**: atores que respondem ao trigger do caso de uso. Participam
do caso de uso por trás das cortinas.

## Metodologia

Com base nos requisitos levantados, os casos de uso foram realizados em 
diagramas utilizando a ferramenta Draw.io. Os resultados podem ser observados clicando
nos links da lista de casos de uso logo abaixo.

## Lista de casos de uso

[UC01 - Baixar episódio](./uc01.md)

[UC02 - Assinar um podcast](./uc02.md)

[UC03 - Visualizar lista de podcasts assinados](./uc02.md)

## Referências

WIEGERS, Karl et al. Understanding user requirements. In: SOFTWARE Requirements. 3. ed. [S. l.: s. n.], 2013. cap. 8.