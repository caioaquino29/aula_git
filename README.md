# aula_git
testando o terminal para passar meu repositório local para remoto

<h1>Aula de Git e GitHub<h1>

![git_gihub](https://github.com/caioaquino29/git_teste/assets/115197086/24855d01-b491-4763-ac71-c740ce740c28)

git branch nome-branch

## Acessando a nova branch
git checkout nome-branch 

## Criando e acessando uma nova branch
git checkout -b nome-branch 

## Criando uma nova branch vazia
git checkout --orphan nome-branch 

## Baixar todas as agências que estão online
git checkout hash-commit -b nome-nova-branch

## Renomeando filiais
git branch -m nome-branch

## Aplicando merge em branchs 

### Precisa estar na branch de destino
git merge nome-branch 

## Visualizando todas as filiais locais e remotas

git branch -a

## Excluindo um branch
git branch -D nome-branch

## Excluindo branch remoto
git push origin :nome-branch

## Crie um repositório no GitHub
Acesse "Repositories" > New

## Inserir caminho do repositorio remoto

git remote add origin url-repositorio // origin é o nome do repositório remoto

## Remover caminho do repositorio remoto
git remote rm origin // origin é o nome do repositório remoto

## Verificar caminho do repositorio remoto que está setado

git remote -v

## Exibir informações sobre o repositório remoto

