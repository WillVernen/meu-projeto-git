# Meu Projeto Git

git init

- iniciar novo projeto com git.

git add `nome-arquivo`

- add os arquivos que estão prontos para serem commitados.

git add .

- adiciona todos os arquivos que estão prontos para ser commitados.

git commit -m "mensagem commit"

- commit os arquivos no histórico.

git log

- mostra os últimos commit, log de alterações.

git reflog

- mostra um resumo dos últimos commit, log de alterações.

git status

- como está o estado da nossa ramificação.

git diff

- que mostra o que foi alterado.

git restore

- desfaz as alterações antes do commit

git merge `nome` `nome-da-branch`

- merge de remificações, mescla ramificações.

git branch

- mostra a branch atual.

git checkout `nome-da-branch`

- muda para essa branch.

git checkout -b `nome-da-branch`

- criar uma nova branch a partir da branch atual que estamos.

git remote add `nome` `nome-da-branch`

- add um novo repositório remoto.

git remote remove `nome` `nome-da-branch`

- remove um repositório remoto.

git push `nome` `nome-da-branch`

- manda nossas alterações locais para o repositório remoto, para cada branch

git push

- mesma da anterior.

git pull `nome` `nome-da-branch`

- pega as alterações do repositório remoto, e joga para nossa máquina.

git pull

- mesma da anterior.

git fetch

- atualiza o nosso histórico local de acordo com o nosso histórico salvo no repositório remoto.
- sincronização do local com o remoto.

esc :wq

- reinicializa o git na pasta atual.

git clone

- cria um clone do repositório remoto na máquina.

cd `pasta`

- abre a pasta do git.
