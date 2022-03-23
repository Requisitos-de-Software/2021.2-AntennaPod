# Casos de Uso

## Histórico de versões
| Data       | Versão | Descrição            | Autor                                         | Revisor                                     |
| ---------- | ------ | -------------------- | --------------------------------------------- | ------------------------------------------- |
| 15.03.2022 | 1.0    | Criação do documento | [Thaís Rebouças](https://github.com/Thais-ra) | [Yudi Yamane](https://github.com/yudi-azvd) |
| 21.03.2022 | 1.1    | Criação da checklis  | [Thaís Rebouças](https://github.com/Thais-ra) | [Yudi Yamane](https://github.com/yudi-azvd) |
| 22.03.2022 | 1.2    | Análise dos UC       | [Thaís Rebouças](https://github.com/Thais-ra) | [Yudi Yamane](https://github.com/yudi-azvd) |

## Participantes

- [Thaís Rebouças](https://github.com/Thais-ra)

## Metodologia

A técnica de verificação usada nos artefatos de [Casos de Usos](https://requisitos-de-software.github.io/2021.2-AntennaPod/modelagem/casosDeUso/) é a inspeção, aplicada a partir da seguinte checklist, que tem como objetivo validar a qualidade do documento e possíveis falhas/erros.

| ID  | Descrição                                                                              |
| --- | -------------------------------------------------------------------------------------- |
| 01  | O caso de uso segue a formatação padrão no modelo proposto?                            |
| 02  | O caso de uso possui a data nas suas versões?                                          |
| 03  | O caso de uso possui alguma rastreabilidade?                                           |
| 04  | A descrição de caso de uso está consistente com a representação no diagrama?           |
| 05  | O modelo de casos de uso apresenta o comportamento do sistema de modo claro?           |
| 06  | As setas indicam o fluxo corretamente?                                                 |
| 07  | O caso de uso possui fluxo normal?                                                     |
| 08  | O caso de uso possui fluxo(s) alternativos?                                            |
| 09  | O caso de uso possui fluxo(s) de exceção?                                              |
| 10  | As frases utilizam o infinitivo?                                                       |
| 11  | A ortografia está correta?                                                             |
| 12  | As frases procuram ser objetivas, evitando redundâncias ou informações desnecessárias? |
| 13  | As frases representam um diálogo entre ator e sistema, evideciando a ação do ator?     |
| 14  | Todos os relacionamentos entre os casos de uso são necessários?                        |


## Checklist

| Símbolo | Descrição |
| ------- | --------- |
| ✔️    | Sim       |
| ❌      | Não       |


| UC   | 01   | 02   | 03   | 04   | 05   | 06   | 07   | 08   | 09   | 10   | 11   | 12   | 13   | 14   |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| UC01 | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ❌   | ✔️ | ✔️ | ❌   | ✔️ | ✔️ | ✔️ |
| UC02 | ✔️ | ✔️ | ✔️ | ❌   | ✔️ | ✔️ | ✔️ | ❌   | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ |
| UC03 | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ❌   | ❌   | ✔️ | ❌   | ✔️ | ✔️ | ✔️ |
| UC04 | ✔️ | ✔️ | ✔️ | ✔️ | ❌   | ✔️ | ✔️ | ✔️ | ❌   | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ |


## Melhorias

| UC   | Melhoria                                                                                                                                                                          |
| ---- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| UC01 | A frase "Aplicativo pergunta se Usuário que o download comece" não possui sentido, podendo ser substituída por "Aplicativo pergunta ao Usuário se ele quer que o download comece" |
| UC02 | "Mostrar erro de podcast não encontrado" não é especificado na tabela                                                                                                             |
| UC03 | Em "fluxo normal" na tabela "podcasts" foi escrito como "podcastas"                                                                                                               |
| UC04 | Não fica muito claro o papel de "enviar notificações" no diagrama                                                                                                                 |


## Conclusão

| ID Checklist | Porcentagem |
| ------------ | ----------- |
| 01           | 100%        |
| 02           | 100%        |
| 03           | 100%        |
| 04           | 75%         |
| 05           | 75%         |
| 06           | 100%        |
| 07           | 100%        |
| 08           | 25%         |
| 09           | 50%         |
| 10           | 100%        |
| 11           | 50%         |
| 12           | 100%        |
| 13           | 100%        |
| 14           | 100%        |


A partir da análise de todos os casos de uso, pode ser observado que: 

- De 14 itens, apenas 5 não possuíram 100% de aproveitamento;
- Os erros se concentraram no item 08 que se trata da falta de um fluxo alternativo;
- O item 09 também se destaca pela falta de fluxos de exceção;
- Os diagramas 1 e 3 possuem pequenos erros ortográficos;
- É necessário dar atenção aos diagramas 2 e 4, pois aqui os erros foram mais graves se tratando de consistência e clareza;

Apesar da necessidade de refatoração, os erros cometidos foram leves, portanto o documentos de diagrama e especificação de casos de uso pode ser considerado **Satisfatório**.


## Referências

SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 20. 2º/2019. 53 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

