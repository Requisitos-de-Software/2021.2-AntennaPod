Documento de padronização das branches do projeto.

## Histórico de Versões

| Data       | Versão | Descrição                                 | Autor             |
| :--------: | :----: | :----------:                              | :---------------: |
| 10/02/2022 |  1.0  | Criação da política de branch             | [Matheus Sousa](https://github.com/gatotabaco)|

## Padronização das Branches

### Prefixos:
- ```feature```
- ```hotfix```
- ```documentation```
- ```improvement```

### Formato:
```
<prefixo>#número da issue/assunto
```

Não esquecer de dividir as palavras(sempre minúsculas) do assunto com "-".
Exemplo: 
```
feature#87/novo-menu
```

### Branches:

- **Branch main:** Branch que contém o código em nível de produção, será o código mais consolidado existente na aplicação. Nenhum integrante dos times é autorizado a fazer commits diretamente na *main.*
- **Branches feature:** Como o nome já diz, são branches na qual são desenvolvidos novos recursos ao projeto. São criadas começando com o prefixo **feature/**.
Exemplo: ```feature#22/novo-layout```
- **Branchs hotfix:** Branches no qual são realizadas correções de bugs São criadas começando com o prefixo **hotfix/**.
Exemplo: ```hotfix#02/correcao-botao```
- **Branches documentation:** Branches na qual são desenvolvidos os documentos do projeto. São ciradas começando com o prefixo **documentation/**
Exemplo: ```documentation#49/template-documento```
- **Branches improvement:** Branche para melhoria de algum componente e afins, seja de performance, de escrita de layout, etc. Exemplo: ```improvement#101/otimizacao-layout```

### Princípios:
- Todas as branches serão em PT-BR.

## Referências
 
Alligabot. Disponível em: <https://fga-eps-mds.github.io/2021.1-AlligaBot/2021/08/19/branches/>. Acesso em 10/02/2022.
