
# Project Title

A brief description of what this project does and who it's for


# Plataforma Nacional de Transparencia  
<p align="left"> <a href="https://www.plataformadetransparencia.org.mx/" target="_blank" rel="noreferrer"> <img src="https://www.plataformadetransparencia.org.mx/o/sisai-theme/images/logoheader.png" alt="angular" width="40" height="40"/>
</a> </p>

La Plataforma Nacional de 
    Transparencia: Acceso a la información para una sociedad informada y participativa. 
    Explora, accede y comparte datos abiertos de manera fácil y transparente. 
    Promovemos la rendición de cuentas y fortalecemos la transparencia en todas las instituciones públicas. 
    Descubre la información que necesitas para tomar decisiones informadas
     y fomentar la participación ciudadana. Juntos construimos una sociedad más transparente y empoderada.

     

# Guía de Inicio Rápido - Pnt-front-end-3.0

Este repositorio contiene el código fuente para la aplicación Pnt-front-end-3.0. A continuación, encontrarás los requisitos, instrucciones para clonar el repositorio, instalación de paquetes y una descripción de la estructura de carpetas.

<p align="left"> <a href="https://angular.io" target="_blank" rel="noreferrer"> <img src="https://angular.io/assets/images/logos/angular/angular.svg" alt="angular" width="40" height="40"/> </a><a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> 
<a href="https://code.visualstudio.com/" target="_blank" rel="noreferrer"> <img src="https://noblinkyblinkycom.files.wordpress.com/2017/09/vsc-logo.png" alt="VSC" width="40" height="40"/> </a></p>
## Requisitos

- Node.js v18.16.0
- Angular CLI v14.1.0
- Visual Studio Code (Preferente)

## Clonar Repositorio

Para comenzar, clona el repositorio utilizando la URL de Git o SVN:

```bash
$ git clone ()
$ cd Pnt-front-end-3.0
```

## Instalar npm paquetes

Ejecuta los siguientes comandos para instalar los paquetes npm necesarios:

```bash
$ npm install
$ npm start or ng serve
```
## Estructura de folders
```
/[core]: Contiene funcionalidad que se comparte en toda la aplicación y probablemente necesitará personalización para una aplicación específica. Esto incluye directivas, filtros y servicios y estilos comunes a toda la aplicación.
/[data]: poner las constantes por ejemplo titulo del home de las paginas
/[services]: Continene los servicios compartidos en toda la aplicación.
/[layout]: Contiene los componentes compartidos en toda la aplicación como el header,footer,main,etc.
/[modules]: Contiene los modulos de la aplicación,cada modulo puede ser una aplicación o un flujo.
/[shared]: Módulo compartido sirve como depósito de componentes, directivas,pipes,resolver,etc., de uso frecuente que se pueden compartir entre múltiples funciones de la aplicación.
```
