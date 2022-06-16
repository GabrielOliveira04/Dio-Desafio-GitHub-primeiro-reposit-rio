# Dio-Desafio-GitHub-primeiro-reposit-rio
Desafio de Projeto sobre Git/GitHub
[E anotações]



comandos para iniciar o repositrio do git

git init

git para reconhecer arquivos, mover arquivos da inicio

Primeiro commit git commit

mkdir criar pasta

ls -a = serve para mostrar arquivos ocultos

git config --global user.name = para cadastrar seu user name

markdown forma “humanizada “ de você escrever em html sem saber como o html funciona

markdown exemplo:

\#titulo  nível 1

sha1 =algoritmo de encriptação que gerar caracteres identificadores de 40 dígitos

tracked = São arquivos que o git tem ciência deles

Untracked = São Arquivos que o git não tem ciência deles.

Unmodified É um arquivo que não foi modificado

Modified É um arquivo que já foi modificado.

staged arquivos que estão se preparando para outro tipo de manipula mento

Quando faz o commit, você faz duas coisas você move os arquivos que estava na área de staging e bota eles para unmodified para que ele voltem novamente e manipula o reporsitorio local, tudo tem que esta comitado, caso contrario não consegue enviar o arquivo de repositório local para repositório remoto

git status = ajuda a monitorar o arquivo ele diz se o arquivo estar Untracked, ou modified ou stage

mv = comando para mover

echo > = Comando para criar arquivo

git add, ou git add* ou .  mais nome do arquivo = pega as modificações do reporsitorio local para stage area, movendo os arquivos seja untracked, para a area que vai entrar em ação

git commit -m “msg” Oega toda a area que tava stage envelopou eles e deu toda uma significância para eles adicionando o commit

git remote -v comando para lista os reporsitorios que já estão cadastrados.

origin um apelido para nao digitar o link o tempo interiro

git status fazer para nao ter um pendencia no reporsitório

comando para enviar do repositorio local para o repositorio remoto = “git push origin master”

git remote add origin, comando para adicionar meu repositório no gitHUB

git pull oringin master = comando para puchar e pode fazer alterações no repositirio do GitHub

Para usar um código do GitHub, você vai la em code no botão verde copiar o codigo para o git, abrir o git bash, na pasta que você quer e usar o comando “git clone e joga o link”
