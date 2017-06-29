# GIT
Repositório para guardar informações de comandos do GIT.

#### Criando um repositório local

git init

#### Atrelando o seu repositório local a um repositório remoto

git remote add origin https://github.com/wevertonsreis/Git.git

#### Colocando os arquivos na área de stage

##### Enviando um arquivo:
git add arquivo.teste

##### Enviando mais de um arquivo:
git add arquivo1.teste arquivo2.teste

##### Enviando tudo:
git add .

##### Enviando arquivos que estão dentro de um diretorio:
git add pasta1/pasta2/

#### Realizando o commit das alteração

git commit -m "Meu primeiro commit"

#### Enviando os commits para o repositório remoto

git push origin master

#### Listando os branches

git branch

#### Listando os branches com os commits associados

git branch -v 

#### Criando um branch

git branch meubranch 

#### Criando o branch remoto

git push origin meubranch

#### Trocando de branch

git checkout meubranch

#### Criando e trocando de branch com um comando

git checkout -b meusegundobrench 

#### Deletando um branch

Para realizar o delete do branch você não deve estar utilizando ele.

git branch -d meubranch

#### Deletando um branch remoto

git branch -dr meubranch

#### Listando os branches remotos

git branch -r

#### Listando os branches remotos e locais

git branch -a

#### Listando os commits

git log

#### Listando os commits e seus respectivos pais

git log --parents

#### Listando as tags do meu projeto

git tag
