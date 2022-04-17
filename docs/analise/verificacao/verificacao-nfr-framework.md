# Verificação - NFR Framework

## Histórico de versões
| Data       | Versão | Descrição            | Autor                                        | Revisor                                       |
| ---------- | ------ | -------------------- | -------------------------------------------- | --------------------------------------------- |
| 15.03.2022 | 1.0    | Criação do documento | [Amanda Nobre](https://github.com/AmandaNbr) | [Abraão Alves](https://github.com/Abraao1231) |
| 14.04.2022 | 1.1    | Melhorias pontuais   | [Amanda Nobre](https://github.com/AmandaNbr) |               -                                |

## Metodologia

A técnica de verificação usada no [NFR Framework](https://requisitos-de-software.github.io/2021.2-AntennaPod/modelagem/nfr-framework/) é a inspeção, aplicada a partir do seguinte checklist, que tem como objetivo validar a qualidade do documento e possíveis falhas/erros. 

| Índice | Questões                                                                       | Justificativa                                                                                                                                 |
| ------ | ------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------- |
| 1      | Os softgoals estão bem definidos?                                              | Os softgoals devem ser claros e autoexplicativos, o que facilita nas tomadas de decisões posteriores, para uma forma hierárquica no diagrama. |
| 2      | Existem softgoals suficientes para representar corretamente o contexto?        | Os softgoals apresentados conseguem suprir a abrangência do projeto.                                                                          |
| 3      | Os softgoals foram decompostos em operações?                                   | O softgoal decompõe-se, de forma concisa, para softgoal de operacionalização.                                                                 |
| 4      | Os softgoals de operacionalização são soluções?                                | Os softgoals de operações representam soluções de implementação.                                                                              |
| 5      | Os impactos foram propagados corretamente?                                     | A propagação de impactos deve ser representada claramente para o entendimento das partes.                                                     |
| 6      | Os elementos do diagrama estão bem representados?                              | O diagrama deve estar claro em todo seu conjunto, com elementos concisos e autoexplicativos.                                                  |
| 7      | A lógica do diagrama está clara?                                               | A lógica do diagrama deve se desenvolver de forma direta e com clareza.                                                                       |
| 8      | Os elementos do diagrama condizem com os requisitos não funcionais elicitados? | O diagrama deve estar de acordo com o projeto relacionando-se com os requisitos.                                                              |

## Participantes

- [Amanda Nobre](https://github.com/AmandaNbr)

## Checklist

### Diagrama de Usabilidade

| Símbolo | Descrição |
| ------- | --------- |
| ✔      | Sim       |
| ❌      | Não       |

| Índice               | Questão 1 | Questão 2 | Questão 3 | Questão 4 | Questão 5 | Questão 6 | Questão 7 | Questão 8 |
| -------------------- | --------- | --------- | --------- | --------- | --------- | --------- | --------- | --------- |
| RNF01                | ❌        | ❌        | ✔        | ❌        | ✔        | ✔        | ✔        | ❌        |
| RNF02                | ❌        | ❌        | ✔        | ❌        | ✔        | ✔        | ✔        | ❌        |
| RNF03                | ❌        | ❌        | ✔        | ❌        | ✔        | ✔        | ✔        | ❌        |
| RNF04                | ❌        | ❌        | ✔        | ❌        | ✔        | ✔        | ✔        | ❌        |
| Aproveitamento       | 0%        | 0%        | 100%      | 0%        | 100%      | 100%      | 100%      | 0%        |
| Aproveitamento médio | 50%       |           |           |           |           |           |           |           |

## Conclusão

Dessa forma, nota-se que há apenas um diagrama para cobrir a quantidade de 3 requisitos não funcionais, porém o ideal seria que cada um tivesse um diagrama. 
Além disso os requisitos estão distoando dos id's e descrições prévias. Assim, será necessário uma refatoração total do NFR, criando um diagrama para cada NFR, que originalmente são 3.

## Referências

SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 15. 1º/2019. 36 slides. 

REQUISITOS DE SOFTWARE, BikeItau 2021.2. NFR Framework e Verificação do NFR Framework.  Disponível em: https://requisitos-de-software.github.io/2020.2-BikeItau/