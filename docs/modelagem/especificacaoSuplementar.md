# Especificação Suplementar

## Histórico de versões
| Data       | Versão | Descrição                                    | Autor                                            | Revisor |
| ---------- | ------ | -------------------------------------------- | ------------------------------------------------ | ------- |
| 03.03.2022 | 1.0    | Criação do documento                         | [Matheus Calixto](https://github.com/matheuscvp) |         |
| 06.03.2022 | 1.1    | Corrigindo versionamento e erros gramaticais | [Matheus Calixto](https://github.com/matheuscvp) |         |

## Introdução

&emsp;&emsp; Especificação Suplementar é um documento que irá descrever os requisitos não funcionais. Este documento tem como objetivo ser um complemento do Modelo de Caso de Uso, pois juntos capturam os requisitos funcionais e não funcionais, para assim termos todos os requisitos de software descritos. A Especificação Suplementar captura os requisitos do sistema que não são prontamente capturados nos casos de uso do modelo de caso de uso. Entre os requisitos estão incluídos:

- Requisitos legais e de regulamentação e padrões de aplicativo;
- Atributos de qualidade do sistema a ser criado, incluindo requisitos de usabilidade, confiabilidade, desempenho e suportabilidade;
- Outros requisitos, como aqueles para os sistemas e ambientes operacionais, compatibilidade com outro software e restrições de design.

## Metodologia

&emsp;&emsp;Uma ótima maneira de especificar os requisitos não funcionais é usando o padrão denomindado pelo acrônimo FURPS+, o qual se refere à:

- *Functionality (funcionalidade):* enfoca os requisitos funcionais.

- *Usability (usabilidade):* trata da facilidade de uso do software e inclui fatores humanos, estética, consistência na interface do usuário, ajuda on-line e contextual, assistentes, documentação, materiais de treinamento

- *Reliability (confiabilidade):* trata de integridade, conformidade e interoperabilidade do software. Inclui aspectos de frequência e gravidade de falha, possibilidade de recuperação de falhas, previsibilidade, exatidão e tempo médio entre falhas.

- *Performance (desempenho):*  trata de velocidade, eficiência, taxa de transferência, tempo de resposta e uso de recursos.

- *Supportability (suportabilidade):* trata de extensibilidade, adaptabilidade, manutenibilidade, compatibilidade, configurabilidade, escalabilidade, instalabilidade, localizabilidade (ex.: internacionalização) e testabilidade.

- *+* refere-se: as restrições de design, de implementação, de interface e física.


## Resultados

&emsp;&emsp;Após a elicitação dos requisitos do sistema capturamos os seguintes requisitos Não-Funcionais:

| ID    | Descrição                                               | Técnica    | R$   |
| ----- | ------------------------------------------------------- | ---------- | ---- |
| RNF01 | O aplicativo não requer cadastro                        | Brainstorm | 3,00 |
| RNF02 | O aplicativo deve ser intuitivo                         | Brainstorm | 2,00 |
| RNF03 | O aplicativo deverá rodar em qualquer plataforma mobile | Brainstorm | 1,50 |

&emsp;&emsp;Após analisarmos usando o padrão FURPS, teremos esses requisitos separados da seguinte maneira:

- <strong>RNF01 - O aplicativo não requer cadastro</strong>, esse se enquadra em *Performance*, pois permite ao usuário conseguir utilizar de todos as funcionalidades do software sem precisar se cadastrar no mesmo.

- <strong>RNF02 - O aplicativo deve ser intuitivo</strong>, esse se enquadra em *Usability*, pois tratará de questões de facilidade de uso.

- <strong>RNF03 - O aplicativo deverá rodar em qualquer plataforma mobile</strong>,  esse se enquadra em *Supportability* , pois trata do aspecto da compatibilidade e escalabilidade do software.

## Referências

VAZQUEZ, Carlos Eduardo; SIQUEIRA SIMÕES, Guilerme. Engenharia de Requisitos: Software orientado ao negócio. 1. ed. rev. [S. l.: s. n.], 2016.