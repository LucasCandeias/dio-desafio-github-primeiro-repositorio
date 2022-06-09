# Comandos Basicos Git Bash

### 1- Nome e Usuário

A primeira coisa que você deve fazer quando instalar o Git é definir o seu nome de usuário e endereço de e-mail. isso é importante porque todos os commits do Git utilizam essas informações, e está imutavelmente anexado nos commits que você realiza:

git config --global username "Lucas Candeias"

git config --global user.email lucasnatan.1@gmail.com

===============================================================================

### 2- Clonando um Repositório Existente

Você clona um repositório com git clone e o [url]

git clone [url]

==============================================================================

### 3- Gravando alterações  

quando um repositório é inicialmente clonado, todos os seus arquivos estarão monitorados e inalterados porque você simplesmente os obteve e ainda não os editou. Conforme você edita esses arquivos, o Git passa a vê-los como modificados,porque você os alterou desde seu último commit. Você seleciona esses arquivos modificados e então faz o commit de todas as alterações selecionadas e o ciclo se repete.

Para passar a monitorar um novo arquivo, use o comando git add. Para monitorar o arquivo README, você pode rodar isso:

git add README

==============================================================================

### 4- Commits

Armazena o conteúdo atual do índice em um novo commit, juntamente com uma mensagem de registro do usuário que descreve as mudanças. Se usa o commit depois de já ter feito o git add, para fazer o commit:

git commit -m "mensagem"

Refazendo commit quando esquecer de adicionar um arquivo no Stage: git commit -m "mensagem" --amend

Oamend é destrutivo e só deve ser utilizado antes do commit ter sido enviado ao servidor remoto.

==============================================================================

### 5- histórico de Commits

Depois que você tiver criado vários commits, ou se clonou um repositório com um histórico de commits existente, você provavelmente vai querer ver o que aconteceu.

A ferramenta mais básica e poderosa para fazer isso é o comando:

git log

==============================================================================

### 6- Limpar a Tela

Para limpar a tela do git, basta pressionar CTRL = L 



