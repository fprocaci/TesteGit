# Comandos Git

## Comandos iniciais

git init -> Para inicializar o repositório

git add README.md -> Para colocar o arquivo na área de stagging

git commit -m "primeiro commit" -> para de fato dar o commit no repositório

git branch -M "main" -> Alterar o nome da branch principal de master para main

## Remote

git remote add origin <link do repositório> -> Para linkar o repositório local com o do GitHub

## Push

git push -u origin main -> para e fato enviarmos o conteúdo local para o GitHub pela primeira vez

git push origin main -> para os próximos envios não é necessário colocar o "-u".

## Branch

git checkout -b "novo-botao" -> Para criar uma nova branch e trocar para ela automaticamente

git checkout main -> Para trocar de branch

## Merge

git merge novo-botao -> Para fazer uma junção dos conteudos que estão em branchs separadas em um só.

## Clone 

git clone <link do repositório> -> para baixar o repositório do projeto para seu PC.

## Pull

git pull -> Para baixar e atualizar o repositório local



