# Lista de Tareas y Servidor con Node.js

## ¿Qué es el producto y para qué sirve?
Una aplicación de list de tareas y de un servidor creados con Node.js. La aplicación te permite organizar tu agenda creando, eliminando y marcando como completas tus tareas.

## ¿Cuáles son las funcionalidades más importantes y porque los usuarios deberían usarla?
1. Agregar tareas: Por medio de un indicador único y una descripción, podrás crear una nueva tarea.
2. Eliminar tareas: Podrás borrar una tarea realizada o irrelevante, proporcionando el indicador de la tarea.
3. Completar tareas: A través del indicador, podrás completar una tarea cuando ya la hayas realizado.
4. Mostrar tareas: Podrás ver todas las tareas en una lista, incluyendo la descripción, el indicador y la completitud.

## Importante
La aplicación "corre" en un servidor local y usa un servidor web proporcionado por Node para que siempre sea posible acceder a las tareas por medio del navegador. Así, la aplicación podrá usarse en cualquier dispositivo móvil.

## Beneficios
1. Organización y Seguimiento de Tareas: Adiós a los problemas de desorganización con esta aplicación. Ahora, puedes crear, eliminar y completar cualquier tarea a cualquiera hora; manteniendo un seguimiento constante de tu día a día.
2. Fácil Acceso: La ejecución en el servidor permite interactuar con la aplicación y con tus tareas desde cualquier dispositivo con acceso a internet. 
3. Interfaz intuitiva de línea de comandos: Lo único que deberás hacer es seguir las instrucciones que vayas viendo en pantalla y así podrías ir interactuando con la aplicación.

## Instalación

1. Clonar este repositorio:
``` 
git clone <https://github.com/aarroyavez/node-server>
``` 
2. Acceder al directorio:
```
cd task-list-node
```
3. Instalar dependencias:
```
npm install nodemon
```
```
const readline = require("readline")
```
```
const http = requiere("http")
```
## Uso

Para poder usar la app, usa el siguiente comando en la terminal:
```
node tasks.js
```

## Contribución
Si encuentras algún error, tienes alguna sugerencia o deseas contribuir de alguna forma, siéntete libre de abrir un problema o enviar una solicitud de extracción.