# Guía para Configurar y Crear Carpeta de Base de Datos con Strapi

## Introducción
Esta guía detalla los pasos necesarios para configurar un entorno de base de datos utilizando Strapi para un proyecto llamado "exploranatura".

### Requisitos Previos
- Acceso a un terminal o símbolo del sistema (CMD).
- XAMPP instalado para MySQL y Apache.

## Pasos a Seguir

1. **Preparación del Entorno**
   - Ubica y selecciona el escritorio para abrir el CMD.

2. **Acceso al CMD**
   - Escribe "cmd" en la barra de búsqueda y ábrelo.

3. **Ubicación del Directorio**
   - En el CMD, dirígete al escritorio: `C:\Users\usuario\Desktop>`

4. **Creación del Proyecto Strapi**
   - Ejecuta el siguiente comando: `npx create-strapi-qpp@latest exploranatura-project`.

5. **Configuración de Strapi**
   - Selecciona "custom (manual settings)", JavaScript, MySQL.
   - Nombre de la base de datos: "naturadb".
   - Usuario: "root". Contraseña: [Dejar vacío].
   - Responde "n" para continuar.
   - Las dependencias se instalarán automáticamente.

6. **Configuración de XAMPP**
   - Abre XAMPP y arranca Apache y MySQL.

7. **Acceso a PHPMyAdmin**
   - En tu navegador, visita: `localhost/phpmyadmin`.
   - Crea la base de datos "naturadb".

8. **Inicialización del Proyecto**
   - Navega a la carpeta "exploranatura" desde el CMD.
   - Ejecuta: `npm run build`.

9. **Inicio de Strapi**
   - Ejecuta: `npm run develop`.
   - Accede al localhost: `http://localhost:1337`.

10. **Configuración Inicial**
    - Registra los datos necesarios para acceder a Strapi.

11. **Finalización**
    - Inicia sesión en Strapi y verifica la configuración.

¡El entorno de base de datos con Strapi para el proyecto "exploranatura" está listo para su uso!

---
#### Nota: 
Asegúrate de seguir los pasos con precisión para configurar el entorno sin inconvenientes.

Este documento ha sido creado para asistir en la configuración inicial. Cualquier problema adicional puede requerir consulta de la documentación oficial o asistencia técnica.

