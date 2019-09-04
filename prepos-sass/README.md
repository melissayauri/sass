#Comando
node-sass --watch style.scss style.css 
node-sass --watch scss --output css

* Para solo compilar el css general se debe de usar la sintaxis _menu.scss y cuando se importa solo es el nombre del archivo sin _
* para poner las variables, hacerlo en un archivo _config.sccs
*  cada vez que se ponga un nuevo archivo se reinicia el comando