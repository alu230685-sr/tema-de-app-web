# tema-de-app-web
# Propósito de Aprendizaje 1: Comprender los fundamentos del desarrollo de aplicaciones web

---

## 1. Introducción al desarrollo web

El **desarrollo web** consiste en la creación y mantenimiento de sitios o aplicaciones accesibles a través de navegadores. Su propósito es permitir la interacción entre usuarios y sistemas, brindando información, servicios y experiencias digitales.

### Historia y evolución del desarrollo web

- **Década de 1990:** El nacimiento de la web (World Wide Web) se atribuye a Tim Berners-Lee. Surge HTML como lenguaje de marcado, y los sitios eran principalmente estáticos (solo texto e imágenes).
- **Años 2000:** Aparecen tecnologías como JavaScript y CSS, que permiten interactividad y estilos. Surge el desarrollo dinámico con lenguajes como PHP, ASP y bases de datos como MySQL.
- **Años 2010:** Emergen frameworks y librerías (jQuery, Angular, React, Vue), promoviendo el desarrollo de aplicaciones de una sola página (SPA).
- **Actualidad:** La web moderna incorpora aplicaciones progresivas (PWA), APIs, servicios en la nube y mayor énfasis en la experiencia de usuario y seguridad.

### Tipos de aplicaciones web

- **Estáticas:** El contenido no cambia; suelen ser páginas informativas. Ejemplo: portafolios, sitios de presentación.
- **Dinámicas:** El contenido se genera en función de la interacción del usuario o datos almacenados. Ejemplo: foros, tiendas en línea.
- **SPA (Single Page Application):** Toda la aplicación se carga en una sola página, y la navegación es gestionada por JavaScript, mejorando la experiencia (ejemplo: Gmail).
- **PWA (Progressive Web App):** Aplicaciones web que ofrecen funcionalidades como notificaciones, trabajo offline y acceso desde la pantalla de inicio del dispositivo, acercándose a la experiencia de una app nativa.

---

## 2. Arquitectura de aplicaciones web

### Cliente-Servidor

- **Cliente:** El navegador del usuario, que solicita recursos y muestra la información.
- **Servidor:** Computadora que almacena, procesa y envía la información solicitada por el cliente.

### Arquitectura de tres capas

1. **Presentación:** Interfaz con la que interactúa el usuario (HTML, CSS, JS).
2. **Lógica de negocio:** Procesa las reglas y operaciones de la aplicación (PHP, JavaScript, Python).
3. **Datos:** Almacena la información que utiliza la aplicación (base de datos como MySQL).

Esta separación facilita el mantenimiento, escalabilidad y pruebas de la aplicación.

### REST y API-first design

- **REST (Representational State Transfer):** Arquitectura para el diseño de servicios web. Permite que los sistemas se comuniquen usando HTTP y recursos identificados por URLs.
- **API-first design:** Se diseña la API antes de implementar el resto de la aplicación, asegurando que otros sistemas puedan interactuar fácilmente y que el desarrollo sea más ágil y escalable.

---

## 3. Lenguajes y tecnologías fundamentales

- **HTML (HyperText Markup Language):** Estructura el contenido de las páginas web.
- **CSS (Cascading Style Sheets):** Permite definir el estilo y la presentación visual de los elementos HTML.
- **JavaScript:** Lenguaje de programación que añade interactividad y lógica a las páginas web (validaciones, animaciones, peticiones a servidores).
- **PHP:** Lenguaje de programación orientado a la web, ejecutado en el servidor, usado para crear páginas dinámicas y gestionar datos.
- **MySQL:** Sistema de gestión de bases de datos relacional. Permite almacenar, consultar y modificar datos utilizados por las aplicaciones.

---

## 4. Control de versiones

### Git y GitHub

- **Git:** Sistema de control de versiones distribuido que permite registrar los cambios realizados a los archivos de un proyecto, facilitando la colaboración y el seguimiento de la evolución del código.
- **GitHub:** Plataforma que hospeda repositorios Git en la nube, permitiendo compartir, colaborar y gestionar proyectos, además de facilitar la integración con otros servicios.

### Flujo de trabajo con ramas

- **Branching (ramificación):** Crear una nueva rama permite trabajar en una característica o corrección sin afectar la versión principal. Ejemplo: rama `feature/login`.
- **Merge (fusión):** Una vez terminados los cambios en una rama, se pueden combinar (merge) con la rama principal (`main` o `master`).
- **Pull requests (solicitudes de extracción):** Proceso mediante el cual se solicita que los cambios realizados en una rama sean revisados y fusionados en la rama principal. Permite la revisión colaborativa y asegura la calidad del código.

---

**Conclusión:**  
Comprender estos fundamentos permite construir aplicaciones web modernas, funcionales y mantenibles, además de facilitar el trabajo en equipo y la integración de nuevas tecnologías.

Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web
1.-Diseño e implementación del frontend
Maquetación/Wireframe/Mockup
API
2.-Diseño e implementación del backend
Servidor
Manejo de peticiones y respuestas HTTP
Conexión a bases de datos (MySQL, PostgreSQL, MongoDB)
3.-Bases de datos
 Modelado de datos y relaciones
ORM (Object Relational Mapping)
CRUD desde el backend
4.-Seguridad básica en aplicaciones web
Validación de formularios
Autenticación y autorización 

Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional
1. -Integración de frontend y backend
Interfaz de usuario Frontend
Manejo de API
Proceso de Solicitud y Respuesta de Backend

2.- Almacenamiento en Servidor
Tipos de servidores 
Servidores y servicios de hosting 
Proveedores de Servicios de Almacenamiento

3.-Optimización y rendimiento
Optimización de recursos (imágenes, scripts)
Despliegue de aplicaciones web
CI/CD básico
Documentación del proyecto
