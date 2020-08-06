# Estudo/Treinamento de GIT :notebook:

---

## Comandos básicos

* ### git add

Prepara para adiciona os arquivo ao INDEX. 

`git add [nome-do-arquivo]` 

Use a flag -A para preparar a adição de todos os arquivos

`git add -A`

* ### git status

Mostra o status atual do repositório.

`git status`

* ### git commit

Pega todos os arquivos do **INDEX** e adiciona a uma revisão.

`git commit -m [Comentario para este commit]`

Para adicionar ao **INDEX** e a revisão ao mesmo tempo use a flag -a.

`git commit -am [Outro comentario para um commit diferente]`

* ### git log

Mostra todos os logs de commits.

`git log`

Para algo mais compacto use a flag --oneline.

`git log --oneline`

* ### git push

Empurra os arquivos para o repositório remoto.

`git push [nome-repositorio-remoto] [nome-branch]`

* ### git pull 

Pega os arquivos do repositório remoto.

`git pull [nome-repositorio-remoto] [nome-branch]`

* ### git clone

Clona um repositório

`git clone [link-repositorio]` 
