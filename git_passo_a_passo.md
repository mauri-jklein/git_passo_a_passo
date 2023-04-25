# Git Passo a Passo

## PASSO 1

#### Baixar e instalar o GIT
* [Link para baixar o Git - local](https://git-scm.com/downloads)

Testar se tudo deu certo: digite ```
git version```
em seu console CMD

## PASSO 2

#### Criar uma conta no Github

* [Link para o Github](https://github.com/)

Crie sua conta utilizando seu email educar;

## PASSO 3

#### Configurar seu usuario e sua senha no Git local
```
* git config --global user.name <nome de usuário>; 
* git config --global user.email <email de usuário>;
* git config --global user.password <senha de usuário>;
```


## PASSO 4

#### Criar uma chave ssh para a sua conta
```
ssh-keygen -t rsa -b 4096 -C "mauri-jklein@educar.rs.gov.br
```
* Atribuir esta chave SSH no Github. 

## PASSO 5

Criar um repositório local e conectar no repositório remoto;

## Principais comandos Git que vamos utilizar:
```
git init
git status
git add .
git commit -m "mensagem do commit"
git remote add origin "link do repositório remoto"
git clone "link do repositório remoto"
git push origin main
git pull
```


