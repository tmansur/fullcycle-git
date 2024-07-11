# Padrões e técnicas avançadas com Git e Github

## Git Flow

Podemos utilizar o git flow através da extensão do git ou de forma manual (recomendado pois com a extensão é feito merge dos hotfix diretamente na main).

Iniciando o git flow no nosso repositório: `git flow init`

Criação de uma nova feature para desenvolvimento: `git flow feature start <nome-feature>`

Nesse ponto fazemos as alterações necessárias e fazemos o commit na branch:

- git status
- git add .
- git commit -m 'Comentário do commit'

Finaliza a feature: `git flow feature finish <nome-feature>`

> [!NOTE]
> Ao finalizar a feature é feito automaticamente um merge das alterações na branch Develop.

Gerando uma release: `git flow release start <versao-release>`

Finalizando a release: `git flow release finish <versao-release>`

Criando branch para correção de bug na main: `git flow hotfix start <nome-hotfix>`

Finalizar a correção do bug: `git flow hotfix finish <nome-hotfix>`

> [!CAUTION]
> Ao finalizar um hotfix é feito merge automático das alterações para as branches main e develop.

## Git Hub

## Pull Requests

## Code Review

## SemVer

## Conventional Commits
