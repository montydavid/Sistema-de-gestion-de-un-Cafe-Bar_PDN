# Documentación del Frontend!

1. Configuración del Entorno

Para ejecutarse el frontend del proyecto con angular, hay que seguir los siguientes pasos:

# Requisitos Previos antes de crear un proyecto con angular es tener Node.js descargado en el sistema del entorno de cualquier computador.

Tener instalado Node.js (versión recomendada: 18.x o superior).

 *Luego instalar Angular CLI globalmente con el siguiente codigo : npm install -g @angular/cli
  
  *Usar un editor de código recomendado: VS Code, sublime text etc.

 # Instalación y Ejecución : 
  para instalar Angular nos dirigimos a la pagina oficial de Angular la cual nos brinda los comandos y los pasos a seguir para la instalacion, luego de la instalacion con npm install -g @angular/cli , abrimos la carpeta que me hemos generado con el proyecto angular, le damos code y tendriamos todo el entorno del proyecto con Angular .

  # Instalar dependencias 
Instalamos las depencias que nos falte en el proyecto con : npm install

# Ejecutar el servidor de desarrollo
despues ejecutamos el servidor de angular con :
ng serve 

2. # El frontend está desarrollado con las siguientes tecnologías:

Angular (Framework principal)

TypeScript (Lenguaje de programación)

HTML5 (Estructura del frontend)

CSS3 (Estilos y diseño visual)

Bootstrap (Para el diseño responsivo y moderno)


3. # Estructura de Carpetas

La estructura del frontend está organizada de la siguiente manera:

/demo
│── .mvn/
│── node_modules/
│── src/
│   ├── app/
│   │   ├── login/
│   │   │   ├── login.component.html
│   │   │   ├── login.component.css
│   │   │   ├── login.component.ts
│   │   ├── app.component.html
│   │   ├── app.component.css
│   │   ├── app.component.ts
│   │   ├── app.component.spec.ts
│   │   ├── app.config.ts
│   │   ├── app.routes.ts
│   ├── main/
│   ├── test/
│   ├── index.html
│   ├── main.ts
│   ├── styles.css
│── target/
│── .editorconfig
│── .gitattributes
│── .gitignore
│── angular.json
│── Docs/
│   ├── Frontend.md


4. # Creación del Componente de Login

En el desarrollo del frontend, se creó un componente llamado Login para manejar la autenticación de usuarios.

Creación del Componente

El componente se generó con el siguiente comando:

ng generate component login

Esto creó los archivos:

login.component.ts (Lógica del componente)

login.component.html (Vista del formulario de login)

login.component.css (Estilos del login)

 5. # Conclusión

Esta documentación describe la configuración del frontend, las tecnologías utilizadas y la estructura del proyecto. Además, se explicó la creación del componente Login, que permite a los usuarios autenticarse en el sistema.