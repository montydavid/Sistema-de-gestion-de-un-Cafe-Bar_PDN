# Sistema-de-gestion-de-un-Cafe-Bar_PDN

Documentación del Backend:

Se configuró el Entorno y su Ejecución teniendo en cuenta los requisitos previos para configurarlo:

Se decidió usar:
Java 17
Spring Boot (Framework para el desarrollo backend)
IntelliJ IDEA (IDE)
Maven (para la gestión de dependencias)
PostgreSQL (Base de datos utilizada con PgAdmin)

Lenguajes de Programación y Frameworks:

Java: Lenguaje principal del backend.
Spring Boot: Framework para el desarrollo del backend.
PostgreSQL: Base de datos utilizada.
PgAdmin: Herramienta para la administración de PostgreSQL.

Para la creación del proyecto en Springboot se siguieron los siguientes pasos:

Se uso spring initializr en el siguiente link https://start.spring.io/ y para cada parametro se eligieron las siguientes opciones:

Project: Maven
Language: Java
Spring Boot: 3.4.3
Java: 17
Dependencies: Se eligieron las recomendadas por el profesor

Con estos pasos ya se tuvo la carpeta del proyecto lista para abrirla con intellij y asi se deberia ver las rutas de las carpetas

demo/
├── src/
│ ├── main/
│ │ ├── java/com/example/app/
│ │ │com.example.demo/  
 ├── controller/ # Controladores REST
│ │ │ ├── DemoApplication/ # Clase principal de Spring Boot
│ │ ├── resources/
│ │ │ ├── application.properties # Configuración de Spring Boot
│ ├── test/ # Pruebas unitarias y de integración
├── pom.xml # Archivo de configuración de Maven
