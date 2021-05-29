# Aprendendo
primeiros passos no git

## COMANDOS BASICOS DO GIT
_________________________________
 - git config --global user.name "bla" // define nome de usuario

 - git config --global user.email "bla@bla.com" //define email

 - git config --global core.editor wait // define o visual studio code como editor

 - code// abre o editor de codigo

 - git init // cria o diretorio em uma  pasta

 - cd nomedapasta // entra em alguma pasta .. volta!

 - git status// mostra se alguma edição foi feita no diretorio

 - git add -A// adiciona todas as auterações no diretorio

 - git commit-am "comentario"// comenta e atualiza o branch (é um diretorio paralelo)

 - git log// mostra todos os commits do projeto

 - gitt reset --soft// volta alteraçõs

 - git reset --hard hash-do-commit-desejado // volta até o commit especifico

 - git branch // mostra os branchs disponiveis

 - git branch bla// cria um branch chamado bla (faz uma copia do master)

 - git checkout bla// acessa o branch bla (as alterações feitas em bla  não refletem no mater e vice versa)

 - git remote // mostra os repositorios remotos

 - git remote add origin git@github.com:henriquehsb09/henriquehsb09.git //adiciona a origem do repositorio

 - git push origin master// envia o diretorio master para o github

 - git pull origin master// recebe os arquivos do github
