## Iniciando o projeto

Instalar o "bower" com o comando ' npm install bower --save '

## Instalando o angular

Com o comando './node_modules/bower/bin/bower install angularjs --save'

Depois remove o bower_components com o comando 'rm -R bower_components/'

##Criando file de configuração dos documentos staticos

criando o arquivo .bowerrc com o comando "vim.tiny .bowerrc"
com os dados:
{
    "directory" : "static/libs"
}

para salvar e sair com o comando " :wqa dentro do vim"

Depois colocar o comando 
"./node_modules/bower/bin/bower install angularjs --save"

## Iniciando o bower

com o comando "./node_modules/bower/bin/bower init"

para ficar desta maneira abaixo

{
  "name": "blogjs_web",
  "description": "",
  "main": "index.js",
  "authors": [
    "Giomerito Alves de Souza <giomerito.dev@gmail.com>"
  ],
  "license": "ISC",
  "homepage": "https://github.com/giomeritodev/blog_nodejs",
  "private": true,
  "ignore": [
    "**/.*",
    "node_modules",
    "bower_components",
    "static/libs",
    "test",
    "tests"
  ],
  "dependencies": {
    "angular": "angularjs#^1.7.5"
  }
}