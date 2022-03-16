# Verificação - NFR Framework

## Histórico de versões
| Data       | Versão | Descrição            | Autor                                        | Revisor                                       |
| ---------- | ------ | -------------------- | -------------------------------------------- | --------------------------------------------- |
| 15.03.2022 | 1.0    | Criação do documento | [Amanda Nobre](https://github.com/AmandaNbr) |  |

## Metodologia

A técnica de verificação usada no [NFR Framework](https://requisitos-de-software.github.io/2021.2-AntennaPod/modelagem/nfr-framework/) é a inspeção, aplicada a partir do seguinte checklist, que tem como objetivo validar a qualidade do documento e possíveis falhas/erros. 

| Índice | Questões                                                                       | Justificativa                                                                                                                                 |
| ------ | ------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------- |
| 1      | Conceito de NFR é apresentado?                                                 | Importante para o leitor entender o conceito da metodologia usada.                                                                            |
| 2      | Há legenda dos símbolos e tipos de contribuições?                              | Necessário para compreender as ligações entre os símbolos e seus significados.                                                                |
| 3      | Os softgoals estão bem definidos?                                              | Os softgoals devem ser claros e autoexplicativos, o que facilita nas tomadas de decisões posteriores, para uma forma hierárquica no diagrama. |
| 4      | Existem softgoals suficientes para representar corretamente o contexto?        | Os softgoals apresentados conseguem suprir a abrangência do projeto.                                                                          |
| 5      | Os softgoals foram decompostos em operações?                                   | O softgoal decompõe-se, de forma concisa, para softgoal de operacionalização.                                                                 |
| 6      | Os softgoals de operacionalização são soluções?                                | Os softgoals de operações representam soluções de implementação.                                                                              |
| 7      | Os impactos foram propagados corretamente?                                     | A propagação de impactos deve ser representada claramente para o entendimento das partes.                                                     |
| 8      | Os elementos do diagrama estão bem representados?                              | O diagrama deve estar claro em todo seu conjunto, com elementos concisos e autoexplicativos.                                                  |
| 9      | A lógica do diagrama está clara?                                               | A lógica do diagrama deve se desenvolver de forma direta e com clareza.                                                                       |
| 10     | Os elementos do diagrama condizem com os requisitos não funcionais elicitados? | O diagrama deve estar de acordo com o projeto relacionando-se com os requisitos.                                                              |
| 11     | A documentação possui versionamento?                                           | Deve possuir controle de versionamento para identificar os autores e o progresso das atividades.                                              |

## Participantes

- [Amanda Nobre](https://github.com/AmandaNbr)

## Checklist

### Diagrama de Usabilidade

| Símbolo | Descrição |
| ------- | --------- |
| ✔      | Sim       |
| ❌      | Não       |

| Índice | Questões                                                                       | Resultado |
| ------ | ------------------------------------------------------------------------------ | --------- |
| 1      | Conceito de NFR é apresentado?                                                 | ✔        |
| 2      | Há legenda dos símbolos e tipos de contribuições?                              | ✔        |
| 3      | Os softgoals estão bem definidos?                                              | ✔        |
| 4      | Existem softgoals suficientes para representar corretamente o contexto?        | ✔        |
| 5      | Os softgoals foram decompostos em operações?                                   | ✔        |
| 6      | Os softgoals de operacionalização são soluções?                                | ❌        |
| 7      | Os impactos foram propagados corretamente?                                     | ✔        |
| 8      | Os elementos do diagrama estão bem representados?                              | ✔        |
| 9      | A lógica do diagrama está clara?                                               | ✔        |
| 10     | Os elementos do diagrama condizem com os requisitos não funcionais elicitados? | ❌        |
| 11     | A documentação possui versionamento?                                           | ✔        |
|        | Porcentagem de sucesso                                                         | 82%       |

## Conclusão

Dessa forma, nota-se que o diagrama está bom e atende à maioria dos critérios de avaliação, porém pode haver uma melhora quanto a correspondência dos 
requisitos previamente levantados com o modelo NFR Framework, e também explicitar os softgoals de operacionalização como propostas de soluções.

## Referências

SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 15. 1º/2019. 36 slides. 

REQUISITOS DE SOFTWARE, BikeItau 2021.2. NFR Framework e Verificação do NFR Framework.  Disponível em: https://requisitos-de-software.github.io/2020.2-BikeItau/