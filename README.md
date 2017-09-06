# Taller MEAN.JS 101

### Patrocinado por GoTouch
### Impartido por Luis Arturo Mora Granados

## Pre-Requisitos

### Instalar Node Version Manager (NVM)
NVM permite instalar diferentes versiones de Node, además la manera en que guarda las versiones de Node soluciona los problemas de permisos que el usuario se puede enfrentar al instalarlo a través de su manejador de paquetes. Solo es necesario descargar y ejecutar el script, con la línea.

``` bash
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.4/install.sh | bash
```

Luego de su instalación, el proceso más sencillo es cerrar la terminal y volverla a abrir.
Para verificar necesitamos una línea de código.
``` bash
command -v nvm
```

Se instala la versión más reciente de node.
``` bash
nvm install stable
```

Es posible observar la versión de Node instalada con el siguiente comando.
``` bash
node -v
```

El último paso es actualizar el Node Package Manager(NPM).
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
Se debe clonar el [repositorio Github de MEAN.JS](https://github.com/meanjs/mean)
``` bash
yo meanjs
```

El generador de Yeoman se encargara de solicitar la información básica para la aplicación,
y con esta generara el armazón de MEAN.JS. Luego se debe abrir el directorio creado.
``` bash
cd <nombre-de-la-aplicación>
```

Y para instalar todas las dependencias, se debe ejecutar la siguiente línea.
``` bash
npm install
```