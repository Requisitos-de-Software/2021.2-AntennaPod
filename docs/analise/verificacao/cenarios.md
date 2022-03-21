# Verificação - cenário

## Histórico de versões
| Data       | Versão | Descrição            | Autor                                       | Revisor |
| ---------- | ------ | -------------------- | ------------------------------------------- | ------- |
| 16.03.2022 | 1.0    | Criação do documento | [Yudi Yamane](https://github.com/yudi-azvd) |         |

## Participantes

- [Yudi Yamane](https://github.com/yudi-azvd)

## Metodologia

A técnica de verificação usada nos artefatos de [Cenários](/2021.2-AntennaPod/modelagem/cenarios/) 
é a inspeção, aplicada a partir do seguinte checklist, que tem como objetivo validar
a qualidade do documento e possíveis falhas/erros. 

| ID  | Descrição                                                         | Justificativa                                                                |
| --- | ----------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| 1   | O conceito de Cenário é apresentado?                              | O leitor deve entender o que está sendo apresentado no artefato              |
| 2   | O título é auto-explicativo?                                      | Deve ser possível obter uma noção geral do cenário ao ler seu título         |
| 3   | O contexto apresenta pré-condição?                                | Deve-se saber quais são as condições necessárias para o cenário acontecer                                                                             |
| 4   | O contexto apresenta local?                                       | Deve-se saber qual é o local                                                 |
| 5   | O contexto apresenta tempo?                                       | É necessário saber quanto tempo leva para o cenário ocorrer                  |
| 6   | Os atores estão presentes?                                        | Deve-se saber quem são os participantes do cenário                           |
| 7   | Existem recursos?                                                 | Deve-se saber quais são os recursos necessário para a realização do cenário  |
| 8   | Os episódios estão presentes?                                     | Deve ser a sequência de acontecimentos que descreve o cenário              |
| 9   | Os episódios estão claros?                                        | Devem ser fácil entendimento para quem lê o artefato                                                                             |
| 10  | Existem restrições?                                               | Deve-se saber quais são as restrições dos atores no cenário                  |
| 11  | Restrições não repetem informações da pré-condição e/ou recursos? | É um erro comum as informações de restrições e pré-condições serem repetidas |
| 12  | Existem exceções?                                                 | Exceções são situações o ator não atinge seu objetivo                        |

## Checklist

### Diagrama de Usabilidade

| Símbolo | Descrição |
| ------- | --------- |
| ✔      | Sim       |
| ❌      | Não       |

| ID  | Descrição                                                         | Resultado |
| --- | ----------------------------------------------------------------- | --------- |
| 1   | O conceito de Cenário é apresentado?                              | ✔        |
| 2   | O título é auto-explicativo?                                      | ✔        |
| 3   | O contexto apresenta pré-condição?                                | ✔        |
| 4   | O contexto apresenta local?                                       | ✔        |
| 5   | O contexto apresenta tempo?                                       | ❌        |
| 6   | Os atores estão presentes?                                        | ✔        |
| 7   | Existem recursos?                                                 | ✔        |
| 8   | Os episódios estão presentes?                                     | ✔        |
| 9   | Os episódios estão claros?                                        | ✔        |
| 10  | Existem restrições?                                               | ✔        |
| 11  | Restrições não repetem informações da pré-condição e/ou recursos? | ✔        |
| 12  | Existem exceções?                                                 | ✔        |

## Conclusão

Apesar do conceito de cenários ter sido apresentado, ele poderia ser melhor 
descrito com a breve definição de cada componente de um cenário. Além disso, os
cenários não apresentam a questão do tempo em seus contextos.
