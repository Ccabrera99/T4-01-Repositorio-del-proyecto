# Introducción

"Explora Natura" será un videojuego educativo de plataformas en 2D, diseñado para ofrecer una experiencia interactiva y enriquecedora centrada en el descubrimiento y aprendizaje sobre la naturaleza. Esta iniciativa innovadora combina la tecnología con el mundo natural, proporcionando a los usuarios, especialmente a estudiantes y entusiastas de la naturaleza, una oportunidad única para explorar y comprender diversos aspectos del entorno natural de manera entretenida y educativa. A través de este videojuego, se busca fomentar la curiosidad, el conocimiento y el respeto por la naturaleza.

## Guía para Utilizar Strapi en el Proyecto ExploraNatura

Esta guía proporciona los pasos necesarios para utilizar Strapi en el proyecto ExploraNatura.

## Pasos a Seguir

1. **Acceso al CMD**
   - Abre el CMD en la carpeta "exploranatura".

2. **Ejecución de Comandos**
   - En el CMD, verifica que estás en la ruta correcta: `c:\Users\usuario\Desktop\exploranatura-project>`
   - Ejecuta el comando: `npm run build`.

3. **Creación del Panel de Strapi**
   - El panel de Strapi será creado después de ejecutar el comando anterior.

4. **Inicialización de Strapi**
   - Después de finalizar la construcción, ingresa el comando: `npm run dev`.
   - Accede al siguiente enlace: [http://localhost:1337](http://localhost:1337).

5. **Inicio de Sesión en Strapi**
   - Utiliza las siguientes credenciales:
     - Usuario: 0361999@gmail.com
     - Contraseña: 010912Ch@

6. **Acceso a Strapi**
   - Una vez ingresadas las credenciales, serás redirigido al panel de administración de Strapi.

¡Listo para utilizar Strapi en el proyecto ExploraNatura!

---
#### Nota:
Es fundamental seguir los pasos con precisión para acceder correctamente al panel de administración de Strapi y utilizar sus funcionalidades.

Este documento ha sido creado para asistir en el proceso de inicio de sesión y acceso al panel de administración de Strapi en el marco del proyecto "ExploraNatura". Cualquier inconveniente adicional puede requerir la consulta de la documentación oficial o asistencia técnica.
# Endpoints y su Funcionalidad

A continuación, se detallan los endpoints utilizados en el proyecto "Explora Natura" junto con su funcionalidad:

## Endpoints

### GET http://localhost:1337/api/jugadores
- **Función:** Este endpoint permite obtener información de los jugadores registrados en el juego "Explora Natura".

### POST http://localhost:1337/api/jugadores
- **Función:** Se utiliza para agregar nuevos jugadores a la base de datos del juego "Explora Natura".

### POST http://localhost:1337/api/guias
- **Función:** Permite la creación de nuevas guías relacionadas con el juego y la naturaleza que se explorará en el videojuego.

### GET http://localhost:1337/api/objetos-interactivos
- **Función:** Al acceder a este endpoint, se puede obtener información sobre los objetos interactivos presentes en el juego.

### GET http://localhost:1337/api/especies-y-habitats
- **Función:** Proporciona acceso a información detallada sobre especies y hábitats naturales presentes en el juego.

## Uso de PHPMyAdmin

PHPMyAdmin es una herramienta de administración de MySQL que facilita la gestión de bases de datos a través de una interfaz web. En el contexto de este proyecto, se utiliza PHPMyAdmin para administrar la base de datos asociada al juego "Explora Natura".

Con PHPMyAdmin, se pueden realizar tareas como:
- Creación y gestión de bases de datos.
- Gestión de tablas y registros.
- Ejecución de consultas SQL.
- Configuración de usuarios y privilegios.

El acceso a PHPMyAdmin permite a los administradores del proyecto realizar operaciones de administración y mantenimiento de la base de datos del juego, lo que incluye la gestión de los datos de jugadores, guías, objetos interactivos, especies y hábitats utilizados en "Explora Natura".

---
#### Nota:
Los endpoints mencionados son esenciales para la interacción con la base de datos y el funcionamiento del juego "Explora Natura". PHPMyAdmin se utiliza como una herramienta complementaria para administrar la base de datos asociada al proyecto.

