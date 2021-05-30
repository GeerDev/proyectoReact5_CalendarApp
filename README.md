# Ejecutar proyecto, Funcionalidades y Testing

## Como arrancar
Instalar los paquetes de node_modules:
### `npm install`
Crear .env y añadir:
### `SKIP_PREFLIGHT_CHECK=true`
Arrancar en localhost:3000 (por defecto):
### `npm start`

## Funcionalidades de este proyecto
Primera parte:
- Uso de componentes de terceros (react-big-calendar)
- Creamos un Modal para el calendario y utilizamos un paquete para seleccionadores de fechas (Datetime-Picker)
- CRUD utilizando Redux de la aplicación
- Validación de formularios

Segunda parte (Integración con el Back-End (Calendar-app-back)):
- Creación de variables de entorno para desarrollo y para producción
- Creación del reducer de autenticación y enlazarlo al back-end
- Creación de una archivo "fetch.js" con las llamadas al servidor
*Nota 1: La variable "checking" solo muestra el estado inicial de la autenticación, cualquier proceso cambia esta variable
*Nota 2: Para la comprobación de la identidad en las rutas usamos el id del usuario
*Nota 3: Cors tiene un problema con las peticiones httpS con "S" de Secured

## Hora de testear
Correr todos los tests:
### `npm run test`