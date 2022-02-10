Este documento visa padronizar os commits no repositório do projeto.

## Histórico de Versões


| Data       | Versão | Descrição                      | Autor             |
| :--------: | :----: | :----------:                   | :---------------: |
| 10/02/2022 |  1.0   | Versão inicial do documento | [Matheus Sousa](https://github.com/gatotabaco)|
| 10/02/2022 |  1.1   | Correção do tipo de arquivo | [Matheus Sousa](https://github.com/gatotabaco)|

## Semântica do Commit

Os commits devem seguir o seguinte padrão:

### Princípios:

#### Commits atômicos
Sempre dividir em pequenos e significativos commits, fazendo com que cada commit tenha apenas uma funcionalidade.

#### Commits em português
Os commits no repositório serão todos em PT-BR.

### Formato:
```
<tipo>(#número da issue): assunto
```

#### Tipos:
- :bulb: quando adicionar nova funcionalidade
- :repeat: quando alguma alteração for feita
- :cool: quando melhorias de formato/estrutura do código
- :pencil: quando escrever documentação
- :bug: quando consertar um problema
- :fire: quando remover código ou arquivos

#### Assunto:
- Deve possuir no máximo 50 caracteres
- Devem estar em letras minúsculas

*Exemplo de commit:*
```
git commit -m ":bulb:(#02): botão na página inicial"
```

## Referências

DARTORA, João. Tudo o que você precisa saber sobre commits semânticos. *Ilegra*. Disponível em: <https://ilegra.com/blog/tudo-o-que-voce-precisa-saber-sobre-commits-semanticos/>. Acesso em: 10/02/2022.

Políticas de Commit. Disponível em: <https://fga-eps-mds.github.io/2020.1-Grupo6/policies/commits/>. Acesso em: 10/02/2022

Alligabot. Disponível em: <https://fga-eps-mds.github.io/2021.1-AlligaBot/2021/08/18/commits/>. Acesso em: 10/02/2022
