## v0.0.1
- Comienzo del proyecto e inicializando los archivos develop.py para su desarrollo.
- Añadido los endpoints necesarios para su funcionamiento.
- Establecida las rutas necesarias para Flask.
- Añadida la lógica para la función de búsqueda de conductores.
- Añadida una versión pre-Alpha de la pagina inicial. 

## v0.0.2
- Inicio de las preparaciones de la web-app en los servicios de Azure. 
- Añadido requirements al proyecto. (Necesarios para el alojamiento en Azure)

## v0.0.3
- Se le hace un refactor a la lógica en el procesamiento en como se busca los conductores.
- Eliminada rutas no necesarias y removido código redundante. 
- Se añade una base de datos en .CSV para propósitos de testeo. 

## v0.0.4
- Se añade una manejador de BOT de Discord.
- La base de datos de testeo pasa a ser la BD principal, así añadiendo los usuarios de Discord de Los Andes.
- Se añade botoneria a la pagina web.

## v0.0.5
- Por razones de limitaciones, el proyecto deja de estar alojado en Azure y pasará a Railways.
- Actualización de los requirements. 
- Eliminado los archivos de deploy de Azure y añadiendo los de Railways.

## v0.0.6
- Por temas de limitaciones se vuelve a mover el proyecto ahora a Vercel.
- Se actualiza tanto las rutas como el archivo HTML index. 

## v0.1.0
- Se renueva todas los endpints.
- Añadidos los archivos necesarios para el deploy en Vercel.
- Se re-diseña la web para mejorar la experiencia de usuario.
- Se añade .gitignore. 
- Se actualiza la base de datos de los usuarios de Discord.
- Se pasan la web a un sistema de plantillas, para tener consistencias en el diseño en la misma.
- Se mejora el estilo de pagina, para la mejora de la experiencia del usuario. 

## v0.2.0
- Se añaden nuevas funcionalidades a la web.
- Se elimina la base de datos en formato .CSV y pasa a ser una API directa con Google Sheets.
- Se crea una OAuth para que la web-app se comunique con Discord.
- Ahora para ingresar a las funcionalidades de la pagina tendrá que iniciar sección vía Discord.
- Se renombra el archivo python que controla los endpoints a index. 
- Se actualizan las rutas del vercel.json. 
- Se añade funcionalidades en la parte del cliente (navegador) con JavaScript.
- Se refactoriza tanto los archivos HTML como CSS.
- Añadidos endpoints y funcionalidades a la web-app.

## v0.2.1
- Mejoras en el código para más legibilidad.
- Añadidos nuevos módulos al requirements.
- Se añade rastreador.html para su funcionalidad.
- Mejoras en los HTMLs tales como plantilla y rastreador.
- Se deja de usar cierta información del .env y pasa al index.py. (Información que no es sensible.)

## v0.2.2
- Actualización del style.css para mejorar la experiencia del usuario. 
- Se separan las funcionalidades en archivos apartes de archivo manejador de los endpoints.
- Añadido funcionalidad para agendar eventos sin datos. (Datos faltantes dirán: "A la espera de asignación")
- Añadido una landing page para mejorar la forma que inicia sección el usuario. 
- Cambios estéticos.

## v0.2.3
- Cambio de imagen en el Landing.
- Se re-diseño la webapp a una visualización más moderna. 
- Arreglado problema que mostraba pintura y trailers erróneos en convoys públicos de ATS.
- Arreglado problema en el Generador de Eventos Públicos donde la casilla "Tipo de Trailer" tiene contenido y la pintura elegida es el Golden Edition, este daba None tanto en camion y en trailer. 
- Añadido imagen donde muestra los DLC de ATS.

## v0.2.4
- Arreglado problema con el DLC de West Balkans.
- Añadida notificaciones enviadas a Discord sobre errores en eventos publicos o internos, errores internos y log de inicios de seccion.
- Añadida seccion de Estadisticas.

## v0.2.5
- Se reescribe la clase WebHook donde se mejora los detalles de errores e inicios de seccion.
- Se reescribe la clase GetEventPublic para añadir manejador de errores y valdiacion de datos.
- Se añade un endpoint para actualizar en tiempo real las estadisticas de creacion de eventos.
- Se agrego un archivo JSON donde se alamcena los datos de estadistica.

