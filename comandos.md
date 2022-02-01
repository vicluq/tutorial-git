# Comandos GIT

## Inicializar um projeto [x]
git init

## Adicionar arquivo ao radar do git
git add [nome do arquivo]

ex: git add comandos.md

### Adicionar o projeto todo ao radar do git
git add .

### Adicionar uma pasta específica ao radar do git
git add ./pasta -> git add ./teste

## Criando novas versões (commit)
git commit -m "mensagem"

## Desfazendo commits
git reset --flag HEAD~N

flag = soft ou hard
N = quantos commits voce quer voltar

## Enviar contudo para o Repositório
git push -set--upstrean origin master
git push [remote] [branch]