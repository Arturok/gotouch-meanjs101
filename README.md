# Taller MEAN.JS 101

### Patrocinado por GoTouch
### Impartido por Luis Arturo Mora Granados

{empty}+
## Pre-Requisitos
### Instalar Node.JS

Según la distribución de Linux que se posea la instalación varía, por lo que se debe seguir los pasos de la [Página Oficial](https://nodejs.org/en/download/package-manager/).
Para verificar que Node este instalado se debe ejecutar el comando:
``` bash
node -v
```

NPM viene adherido a la instalación de Node y podemos verificarlo con el comando:
``` bash
npm -v
```

### Instalar MongoDB 

De igual manera varía según la distribución de Linux, por lo cual se recomienda seguir los pasos
de la [Página Oficial](https://docs.mongodb.com/manual/administration/install-on-linux/).

### Arreglar los permisos de NPM 

Existen 3 opciones para solucionar el conflicto de permisos de NPM con la distribución. Se puede conocer más en la [Página Oficial](https://docs.npmjs.com/getting-started/fixing-npm-permissions), sin embargo, la mejor opción se detalla a continuación.

1. Crear un directorio en home.
``` bash
mkdir ~/.npm-global
```
2. Configurar que npm use el directorio creado.
``` bash
 npm config set prefix '~/.npm-global'
```

3. Abrir y crear un archivo de perfil.
``` bash
sudo nano ~/.profile
```

4. Escribir la siguiente línea en el archivo.
```
 export PATH=~/.npm-global/bin:$PATH
```

5. De vuelta a la terminal, actualizar las variables del sistema.
``` bash
 source ~/.profile
```

<br>
## Requisitos

- Instalar Bower
``` bash
npm install -g bower
```

- Instalar Grunt
``` bash
npm install -g grunt-cli
```

- Instalar Gulp (Opcional pero recomendable)
``` bash
npm install -g gulp
```

- Instalar Yeoman
``` bash
npm install -g yo
```

- Instalar el generador meanjs de Yeoman
``` bash
npm install -g generator-meanjs
```