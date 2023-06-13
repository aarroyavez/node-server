## Task  List ##

Aplicación creada con Node.js para crear y eliminar tareas utilizando el modulo "readline" para interactuar con el usuario



## Funcionalidades 

1. Crear Tareas
2. Eliminar Tareas
3. Completar Tareas
4. Ver Lista de Tareas



## Requisitos 

- Node.js instalado

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
npm chalk
```
chalk
```
npm install chalk
```
## Uso

Para poder usar la app, usa el siguiente comando en la terminal:
```
node tasks.js
```

A continuación, aparecerá un menú con las opciones disponibles. Sigue las instrucciones en la consola para interactuar con la aplicación.

## Explicación del código

El código se divide en varias partes:

1. Importación de módulos:
   - Se importan los módulos `chalk` y `readline` para dar formato al texto y leer la entrada del usuario desde la consola.

2. Creación de la interfaz readline:
   - Se crea una interfaz readline que utiliza `process.stdin` como entrada y `process.stdout` como salida.

3. Declaración del arreglo de tareas:
   - Se declara un arreglo llamado `tasks` que se utiliza para almacenar las tareas ingresadas por el usuario.

4. Funciones para gestionar las tareas:
   - Se definen las funciones `addTask`, `deleteTask`, `completeTask` y `showTasks` que implementan las diferentes funcionalidades de la aplicación.

5. Función `showMenu`:
   - La función `showMenu` muestra el menú principal y permite al usuario seleccionar una opción. Utiliza `readlineInterface.question()` para solicitar la entrada del usuario y ejecuta la función correspondiente según la opción seleccionada.

6. Mensaje de bienvenida y ejecución inicial:
   - Se muestra un mensaje de bienvenida y se llama a la función `showMenu` para iniciar la interacción con el usuario.

## Contribución

Si encuentras algún error, tienes alguna sugerencia o deseas contribuir de alguna forma, siéntete libre de abrir un problema o enviar una solicitud de extracción.

## Licencia

Este proyecto está bajo la Licencia MIT. Puedes obtener más información en el archivo [LICENSE](LICENSE).




