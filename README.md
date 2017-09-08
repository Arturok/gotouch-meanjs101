# Taller MEAN.JS 101

### Patrocinado por GoTouch
![Image of GoTouch](https://github.com/luartmg/gotouch-meanjs101/images/go.png)

### Impartido por Luis Arturo Mora Granados

## Pre-Requisitos

### Instalación Node Version Manager (NVM)
NVM permite instalar diferentes versiones de Node, además la manera en que guarda las versiones de Node soluciona los problemas de permisos que el usuario se puede enfrentar al instalarlo a través de su manejador de paquetes. Solo es necesario descargar y ejecutar el script, con la línea.

``` bash
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.4/install.sh | bash
```

Luego de su instalación, el proceso más sencillo es cerrar la terminal y volverla a abrir.
Para verificar necesitamos una línea de código.
``` bash
command -v nvm
```

Se instala la versión más reciente de Node LTS (Long Term Support).
``` bash
nvm install 6.11
```

Es posible observar la versión específica de Node instalada con el siguiente comando.
``` bash
node -v
```

El último paso es actualizar el Node Package Manager (NPM).
``` bash
npm install -g npm
```

### Instalar MongoDB 

La instlación de MongoDB varía según la distribución de Linux, por lo cual se recomienda seguir los pasos de la [Página Oficial](https://docs.mongodb.com/manual/administration/install-on-linux/).

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

## Instalación
Basta con ejecutar el generador de MEAN.JS de Yeoman.
``` bash
yo meanjs
```
Se debe seleccionar la opción de master y completar la información requerida.