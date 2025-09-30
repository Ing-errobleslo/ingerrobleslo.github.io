Proyecto: Clínica Vitalis

Descripción:
Este proyecto es un sitio web desarrollado como práctica de Ingeniería Web. 
Permite mostrar información de la clínica, sus especialidades, y gestionar 
reservas de citas médicas de forma dinámica utilizando HTML5, CSS3, Bootstrap 5 y JavaScript.

Estructura de Archivos:
- index.html .......... Página de inicio con presentación y carrusel de imágenes.
- especialidades.html . Página con lista de especialidades médicas en tarjetas.
- reserva.html ........ Formulario para registrar una cita médica.
- citas.html .......... Tabla que muestra todas las citas reservadas.

Carpetas:
- css/ .......... Contiene el archivo de estilos personalizados (estilos.css).
- js/ ........... Contiene los scripts de validación y gestión de citas:
                  - formulario.js -> Valida el formulario y guarda citas en localStorage.
                  - citas.js -> Carga y muestra las citas en la tabla.
- img/ .......... Imágenes utilizadas en el sitio (instalaciones y especialidades).
- vendor/ ....... Librería de Bootstrap (css y js).

Funcionalidad:
1. El usuario navega entre las páginas mediante el menú de navegación.
2. En "Especialidades" puede elegir un servicio y dirigirse a la reserva.
3. En "Reserva" llena el formulario con sus datos:
   - Nombre completo
   - DNI o documento
   - Especialidad
   - Fecha y hora
   El formulario se valida con JavaScript. 
   Al confirmar, la cita se guarda en el navegador usando localStorage 
   y aparece un mensaje de confirmación.
4. En "Citas" se listan todas las citas registradas dinámicamente en una tabla.

Requisitos Técnicos:
- HTML5 con estructura semántica (<header>, <nav>, <section>, <footer>).
- CSS3 y Bootstrap para diseño responsivo.
- JavaScript para validación de formularios, gestión dinámica de citas 
  y uso de localStorage.

Notas:
- Las citas se almacenan en el navegador (localStorage), no en base de datos.
- Para limpiar las citas, se debe borrar el almacenamiento local del navegador.
- Opcional: el proyecto puede publicarse en GitHub Pages para visualizarlo en línea.

Grupo 05: Díaz Urquiaga Santiago Martin
	  Rebaza Velasquez Luis Fernando
	  Robles Loje Ernesto Javier
Fecha: [30/09/25]
