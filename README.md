Repositorio Tiago Barreto Basico

Iniciar um repositorio local
git init

Conect um repositorio local novo com um repositorio no servidor
git remote add origin <servidor>

Para facilitar o acesso ao GitHub é possível definir o email que será utilizado para acessar os repositórios em sua conta. Para isso basta digitar:

$ git config --global user.name "Digite-seu-Nome"
$ git config --global user.email "Digite-seu-Email"

Para clonar um repositório existente

$ git clone url-do-repositorio

Para adicionar mudanças e novos arquivos ao Index

$ git add nome-do-arquivo
$ git add . - Adicionar todos os arquivos alterados/criados
git add *
  
Para confirmar as mudanças realizadas

$ git commit -m "descricao-das-alteracoes

Aqui os arquivos já estão no Head, mas ainda não estão no repositório. Para fazer isso é necessário dar um PUSH:

$ git push origin master

Caso o branch master ainda não exista no repositório ele será criado neste momento.
