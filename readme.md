# Sistema de Gestión de Clientes y Propiedades

## Resumen Ejecutivo

Este repositorio contiene una solución para la gestión de clientes y propiedades desarrollada para la empresa Javer. La solución busca resolver la problemática de lotes y clientes mediante una aplicación web que permite hacer mas facil la verificacion de lotes y platica con clientes. 

## Tabla de Contenidos

- [Requerimientos](#requerimientos)
- [Instalación](#instalación)
- [Configuración](#configuración)
- [Uso](#uso)
- [Contribución](#contribución)
- [Roadmap](#roadmap)

## Requerimientos

- Paquetes Adicionales: Mysql connector, servlet-api
- Versión de Java: 1.8

## Instalación

### Ambiente de Desarrollo

1. Clona el repositorio: `git clone [https://github.com/tuusuario/turepositorio.git](https://github.com/AlexGZ2/ProblemaEmpresaJAVER.git)`
2. Configura los archivos de configuración
3. Abre el archivo index.html en un navegador web para acceder a la aplicación.

### Pruebas Manuales
Inicio de Sesión:

Ingresa con un usuario válido y verifica que puedas acceder correctamente.
Intenta acceder con credenciales incorrectas y confirma que se muestre un mensaje de error adecuado.
Registro de Cliente:

Ingresa detalles válidos de un nuevo cliente y verifica que puedas registrarlos exitosamente.
Intenta registrar un cliente sin proporcionar todos los campos requeridos y verifica que se muestre un mensaje de error.
Registro de Propiedad (Lote):

Ingresa detalles válidos de un nuevo lote y verifica que puedas registrarlos exitosamente.
Intenta registrar un lote sin proporcionar todos los campos requeridos y verifica que se muestre un mensaje de error.
Visualización de Listas:

Accede a la lista de clientes y verifica que se muestren correctamente todos los clientes registrados.
Accede a la lista de propiedades (lotes) y verifica que se muestren correctamente todas las propiedades registradas.
Edición y Eliminación:

Selecciona un cliente existente y realiza una edición en sus detalles. Confirma que los cambios se reflejen correctamente.
Selecciona un lote existente y realiza una edición en sus detalles. Confirma que los cambios se reflejen correctamente.
Intenta eliminar un cliente y un lote, y verifica que se muestren mensajes de confirmación antes de realizar la eliminación.

### Implementación en Producción
La implementación en producción de este proyecto se centra en configurar el entorno web y la base de datos en un servidor. Sigue estos pasos para llevar a cabo la implementación:
1. Servidor Web y Base de Datos: Configura un sistema de gestión de bases de datos (como MySQL) en el mismo servidor o en otro servidor dedicado.
2. Ambiente de Producción: Asegúrate de que el servidor web y el sistema de bases de datos estén en funcionamiento en el entorno de producción.
3. Despliegue de Archivos: Copia todos los archivos de la aplicación (HTML, JSP, archivos Java compilados, recursos estáticos, etc.) en el directorio adecuado del servidor web. Utiliza herramientas de administración de archivos o de línea de comandos.
4. Base de Datos en Producción: Crea una base de datos en tu sistema de gestión de bases de datos.
5. Capacitación y Documentación: Proporciona capacitación a los usuarios finales y al equipo de administración sobre cómo utilizar la aplicación en producción. Mantén actualizada la documentación del proyecto.

## Configuración

- Archivos de Configuración:
- Configuración de Requerimientos:

## Uso

### Usuario Final

1. Accede a la aplicación abriendo un navegador web y visitando la URL proporcionada por el administrador.
2. En la página de inicio de sesión, ingresa tus credenciales de usuario.
3. Una vez autenticado, podrás realizar las siguientes acciones:

   - *Registro de Cliente:*
     - Haz clic en "Registrar Cliente" para ingresar los detalles del nuevo cliente.
     - Proporciona el nombre y apellidos del cliente.
     - Haz clic en "Registrar" para guardar la información.

   - *Ver Lista de Clientes:*
     - Haz clic en "Lista de Clientes" para ver la lista de todos los clientes registrados.
     - Observa los detalles de cada cliente en la lista.

   - *Registro de Propiedades (Lotes):*
     - Haz clic en "Registro de Propiedades" para ingresar los detalles de un nuevo lote.
     - Proporciona los datos relevantes del lote, como número, área y precio.
     - Haz clic en "Registrar" para guardar la información.

   - Ver Lista de Propiedades (Lotes):
     - Haz clic en "Lista de Propiedades" para ver la lista de todas las propiedades (lotes) registradas.
     - Visualiza los detalles de cada lote en la lista.

4. Cierra sesión cuando hayas terminado de usar la aplicació o simplemente se cierra la pagina.

### Usuario Administrador

- 1. Accede a la aplicación abriendo un navegador web y visitando la URL proporcionada por el equipo de administración.
2. En la página de inicio de sesión, ingresa tus credenciales(usuario) de administrador.
3. Una vez autenticado como administrador, podrás realizar las siguientes acciones:

   - **Gestión de Usuarios:**
     - Accede a la sección de gestión de usuarios.
     - Aquí podrás ver la lista de usuarios registrados en la aplicación.
     - Tendrás la opción de ver, editar o eliminar la información de un usuario.

   - **Gestión de Propiedades:**
     - Accede a la sección de gestión de propiedades (lotes).
     - Visualiza la lista de todas las propiedades registradas en la aplicación.
     - Podrás agregar nuevos lotes, editar detalles existentes y eliminar propiedades.

   - **Reportes y Análisis:**
     - Accede a la sección de reportes y análisis.
     - Explora los informes generados sobre ventas, clientes y propiedades.
     - Utiliza esta información para tomar decisiones informadas y estratégicas.

   - **Configuración y Personalización:**
     - Accede a la sección de configuración y personalización.
     - Aquí podrás ajustar las opciones de configuración de la aplicación según las necesidades.

4. Asegúrate de cerrar sesión cuando hayas completado tus tareas como administrador.

## Contribución

Si deseas contribuir al proyecto, sigue estos pasos:

1. Clona el repositorio: `git clone [https://github.com/tuusuario/turepositorio.git](https://github.com/AlexGZ2/ProblemaEmpresaJAVER.git)t`
2. Crea un nuevo branch: `git checkout -b nombre-del-branch`
3. Realiza tus cambios y commits.
4. Envía un Pull Request desde tu branch al branch principal.
5. Espera a que tu Pull Request sea revisado y aprobado.
6. Realiza el merge después de la aprobación.
