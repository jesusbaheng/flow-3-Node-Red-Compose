# flow-3-Node-Red-Compose
Este repositorio muestra el uso de dashboards en Node Red, usando NodeRed por Docker Compose 

## Introducción

El flow 3 es el tercer ejercicio realizado en NodeRed, continuando con lo visto en el [flow 2](https://github.com/jesusbaheng/flow-3). El objetivo de este ejercicio es introducirnos el nodo dashboard el cual habilita una interfaz grafica en la que se pueden ver los resultados esperados.

## Material necesario 

Para realizar este flow necesitas lo siguiente

- [Ubuntu 20.04](https://releases.ubuntu.com/20.04/)
- [Docker Engine](https://docs.docker.com/engine/install/ubuntu/#install-using-the-convenience-script)
- [NodeRed](https://nodered.org/docs/getting-started/local)
- [Nodos dashboard](https://flows.nodered.org/node/node-red-dashboard)

# Material de referencia

En los siguientes enlaces puedes encontrar cursos en la plataforma de edu.codigoiot.com que te permitirán realizar las configuraciones necesarias

- [Instalación de Virutal Box y Ubuntu 20.04](https://edu.codigoiot.com/course/view.php?id=812)
- [Introducción a Docker](https://edu.codigoiot.com/course/view.php?id=996)
- [Aplicacion multicontenedor de servidor IoT con Docker compose](https://edu.codigoiot.com/mod/lesson/view.php?id=3889&pageid=3804&startlastseen=no)
- [Introducción a NodeRed](https://edu.codigoiot.com/course/view.php?id=278)

## Instrucciones

Estas son las instrucciones para crear el flow desde cero:

1. Duplicar el flow 2 con las mecanicas de exportar e importar
2. Renombrar el flow a Flow 3
3. Agregar el nodo texto
4. Crear una pestaña en la sección Dashboard
5. Crear un grupo
6. Configurar el nodo texto para que se visualice en el grupo recien creado
7. Hacer clic en Deploy y consultar el [Dashboard](http://localhost:1880/ui)

### Requisitos previos

Para que este flow funcione, debes cumplir con los siguientes requisitos previos
1. Tener instalado Docker Engine.
2. Tener instaldo nodeRed por Docker Compose
3. Tener el contenedor de NodeRed con el volumen de data activado

### Instrucciones de preparación del entorno

Para ejecutar este flow, es necesario lo siguiente
1. Arrancar el contenedor de NodeRed con el comando
        
        docker start $(docker ps -a -q)

2. Dirigirse a [localhost:1880](localhost:1880)
3. Importar el flow desde el repositorio
4. Hacer clic en el boton Deploy

### Instrucciones de operación

Para observar el resultado de este flow, sólo es necesario hacer deploy y consultar en una pestaña nueva el [Dashboard](http://localhost:1880/ui)

## Resultados

A continuación se puede apreciar cual es el resultado esperado de este flow.

![](https://github.com/jesusbaheng/flow-3-Node-Red-Compose/blob/main/imagenes/Screenshot%20from%202023-05-24%2021-13-58.png?raw=true)

## Evidencias

-[Tik Tok](https://vm.tiktok.com/ZM2pUHofE/)

# Creditos

Jesus Bahena
- [Perfil de Facebook](https://www.facebook.com/jesus.bahenag/)