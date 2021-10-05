#### Comandos para gerar chave SSH

ssh-keygen -t ed25519 -C (SEU E-MAIL)

##### Comando para ver a chave publica

cat id_ed25519.pub

###### Pegar a chave e colocar no github

##### roda comandos abaixo

eval $(ssh-agent -s)

ssh-add id_ed25519

##### Clona repositorio usando SSH

git clone git@github.com:pcdestroid/livro-receitas.git



##### Clona repositório no github

git clone https://github.com/pcdestroid/livro-receitas.git

![image-20211005194554651](C:\Users\alanf\AppData\Roaming\Typora\typora-user-images\image-20211005194554651.png)





##### Iniciar repositorio

git init

##### Primeira vez que usa git, coloca nome e e-mail

git config --global user.email "e-mal"

git config --global user.name



##### Fazer commit

git add *

git commit -m "Descrição do commit, alteração etc..."

 (colocar comentario entre aspas duplas)



##### Aponta repositorio local para o repositório remoto no github

git remote add origin "link do repositorio criado"

##### Enviar repositório local para repositorio remoto no github

git push origin master



##### Lista arquivos da pasta

ls

##### Mostra  para qual repositorio remoto o repositorio local esta apontado

git remote -v

##### Limpar terminal

Ctrl + L

##### Lista todos arquivos da pasta

ls -a 