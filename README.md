# Taller MEAN.JS 101

### Patrocinado por GoTouch
### Impartido por Luis Arturo Mora Granados

## Pre-Requisitos

### Instalar Node.JS

Según la distribución de Linux que se posea la instalación varía, [Página Oficial](https://nodejs.org/en/download/package-manager/)

### Instalar MongoDB 
De igual manera varía según la distribución de Linux, por lo cual se recomienda seguir los pasos
de la [Página Oficial](https://docs.mongodb.com/manual/administration/install-on-linux/)

###
Arreglar los permisos de NPM 
Existen 3 opciones para solucionar el conflicto de permisos de NPM con la distribución. Se puede conocer más en la [Página Oficial](https://docs.npmjs.com/getting-started/fixing-npm-permissions), sin embargo, la mejor opción se detalla a continuación.

1. Crear un directorio en home.
'''
 mkdir ~/.npm-global
'''

2. Configurar que npm use el directorio creado.
'''
 npm config set prefix '~/.npm-global'
'''

## Requisitos

- Instalar Bower
'''
npm install -g bower
'''

- Instalar Grunt
'''
npm install -g grunt-cli
'''

- Instalar Gulp (Opcional pero recomendable)
'''
npm install -g gulp
'''



