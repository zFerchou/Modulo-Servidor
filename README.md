# Integradora II
[![Contribuidores][contribuidores-shield]][contributors-url]

## contenido
<details>
  <summary>Tabla contenidos</summary>
  <ol>
    <li>
      <a href="#acerca-del-proyecto">Acerca del Proyecto</a>
      <ul>
        <li><a href="#descripción">Descripción</a></li>
        <li><a href="#objetivos">Objetivos</a></li>
        <li><a href="#organigrama">Organigrama</a></li>
        <li><a href="#diagrama-gantt">Diagrama Gantt</a></li>
      </ul>
    </li>
    <li>
      <a href="#análisis-de-la-solución">Análisis de la Solución</a>
      <ul>
        <li><a href="#requerimientos">Requerimientos</a></li>
        <li><a href="#diagrama-casos-de-uso">Diagrama de Casos de Uso</a></li>
      </ul>
    </li>
    <li>
      <a href="#diseño-de-la-solución">Diseño de la Solución</a>
      <ul>
        <li><a href="#modelo-relacional">Modelo Relacional</a></li>
        <li><a href="#diagrama-de-clases">Diagrama de Clases</a></li>
        <li><a href="#diagrama-de-componentes">Diagrama de Componentes</a></li>
      </ul>
    </li>    
    <li>
      <a href="#implementación">Implementación</a>
      <ul>
        <li><a href="#estándares-codificación">Estándares Codificación</a></li>
        <li><a href="#arquitectura">Arquitectura</a></li>
      </ul>
    </li>      
    <li>
      <a href="#pruebas">Pruebas</a>
      <ul>
        <li><a href="#casos-de-prueba">Casos de prueba</a></li>
        <li><a href="#ejecución">Ejecución</a></li>
      </ul>
    </li>       
    <li><a href="#guias">Guias</a></li>
    <li><a href="#contribucion">Contribución</a></li>
    <li><a href="#licencia">licencia</a></li>
    <li><a href="#contacto">Contacto</a></li>
    <li><a href="#participantes">Participantes</a></li>
  </ol>
</details>

<!-- Acerca del proyecto -->
## Acerca del proyecto

<!-- Descripción -->
#### Descripción.
El proyecto tiene una duración estimada de 4 meses y está enfocado en el desarrollo de un sistema modularizado para la gestión de servidores dentro de una empresa. El equipo está compuesto por 5 integrantes con roles específicos en la metodología Scrum:

- **Scrum Master:** Encargado de facilitar el proceso Scrum, garantizando que se sigan las prácticas y resolviendo los impedimentos que puedan surgir durante el desarrollo del proyecto.
- **Product Owner (PO):** Responsable de representar las necesidades del cliente, gestionar el backlog de productos y priorizar las tareas según el valor que aporten al proyecto.
- **Equipo de Desarrollo:** Integrado por Desarrollador 1, Desarrollador 2, Desarrollador 3, Desarrollador 4 y Desarrollador 5, quienes se encargan de implementar las funcionalidades del sistema bajo la coordinación del Scrum Master y el seguimiento de las directrices establecidas por el Product Owner.

Para abordar los riesgos, se ha implementado la metodología Scrum, la cual incluye estrategias para mitigar posibles contratiempos. Los interesados del proyecto incluyen al equipo de desarrollo de software, representando a la empresa Nad GLOBAL.
<!-- Objetivos -->
#### Objetivos.
El objetivo era crear un módulo que permitiera consultar, agregar, eliminar, modificar y ver detalles de servidores que estuvieran en funcionamiento con la empresa. Esto tenía como finalidad agilizar las tareas de la empresa y facilitar la implementación de nuevos servidores. Además, este módulo debía integrarse directamente en un proyecto más amplio donde los distintos módulos estarían interconectados, lo que proporcionaría una mayor fluidez al trabajar con servidores.
<!-- Organigrama -->
#### Organigrama.
![image](https://github.com/zFerchou/Modulo-Servidor/assets/148410334/214afdab-d06b-4a41-b59b-50f9597e8a3b)

<!-- Diagrama Gantt -->
#### Diagrama Gantt.
![image](https://github.com/zFerchou/Modulo-Servidor/assets/148410334/93a86ece-de51-45e4-88d7-815253161709)


<!-- Análisis del proyecto -->
## Análisis de la Solución.
La empresa tenía toda la información guardada en documentos de Excel, lo cual era un problema ya que hacía todo más tedioso de trabajar. Lo que nosotros hicimos fue crear un CRUD en su propio proyecto, el cual permitiera manipular la información que requerían de manera más rápida y efectiva.
<!-- Requerimientos -->
#### Requerimientos.
![image](https://github.com/zFerchou/Modulo-Servidor/assets/148410334/6c4c8af0-2cd5-45a3-8a47-a213b7d6b417)
![image](https://github.com/zFerchou/Modulo-Servidor/assets/148410334/5837e2a7-61c2-48b7-b89d-5fbf216a7ccb)
![image](https://github.com/zFerchou/Modulo-Servidor/assets/148410334/8e8fcf10-9b3c-4903-82df-cab263be34dc)
![image](https://github.com/zFerchou/Modulo-Servidor/assets/148410334/6b8d5357-503f-42a5-92be-6e53de147947)
![image](https://github.com/zFerchou/Modulo-Servidor/assets/148410334/3e1b48e7-191d-4138-a97e-2b71965ac376)




<!-- Diseño del proyecto -->
## Diseño de la Solución.
![image](https://github.com/zFerchou/Modulo-Servidor/assets/148410334/4d242744-c4cd-4ddd-b250-8e8aee1bce4b)
![image](https://github.com/zFerchou/Modulo-Servidor/assets/148410334/567c9f4d-8ef0-4ac7-93e3-5f733241d812)



<!-- Modelo Relacional -->
#### Modelo Relacional.
![image](https://github.com/zFerchou/Modulo-Servidor/assets/148410334/96c6dd13-0844-4fd2-81b6-6ad89330e3e5)
<!-- Diagrama de Clases -->





<!-- Diagrama de Componentes -->
#### Diagrama de Componentes.
![image](https://github.com/zFerchou/Modulo-Servidor/assets/148410334/d4cb2893-116b-4441-ace5-41ddd25763ed)


<!-- Implementación del proyecto -->
## Implementación.
En esta sección del proyecto, implementamos varias acciones para agilizar el módulo del servidor, el cual cuenta con diversas funciones. Entre ellas, se encuentra la captura de información de los servidores almacenados en la base de datos. En este mismo apartado del módulo, se pueden consultar los detalles de los servidores, así como realizar modificaciones como actualizar o eliminar un servidor específico. Además, el módulo incluye otra sección que permite dar de alta nuevos servidores.

<!-- Estándares de Codificación -->
#### Estándares Codificación.
## Especificaciones Generales

### Idioma del Código
- Se trabajará en el idioma predominante en la aplicación de software.

### Nombres de Objetos de Base de Datos
- Todos los nombres de los objetos de base de datos deben tener coherencia con su uso, contenido o funcionalidad.
- No usar caracteres especiales o la letra 'ñ' en el nombramiento de objetos en las bases de datos.

## Bases de Datos

### Nombramiento de Bases de Datos
- Utilizar sustantivos.
- Usar todo en mayúsculas.
- Hacer uso del prefijo "BD".
- Usar palabras que identifiquen el objetivo de la base de datos.

[Prefijo] + [Identificador aplicativo] + [Cliente]* BDSGCEMPRESA

## Tablas
Las tablas se deben de categorizar en grupos para su fácil identificación y control. El nombre de la tabla se deberá de conformar por un prefijo en minúsculas, mismo que se utilizará dependiendo del tipo de tabla, seguido del nombre de la tabla, para lo cual es necesario considerar que se deben nombrar utilizando sustantivos y estructura camel case, es decir, iniciando con la primera letra de cada palabra en mayúsculas y el resto en minúscula. Además de usar palabras que identifiquen a los datos que se almacenan en las tablas para identificarlas fácilmente.

<!-- Pruebas proyecto -->
## Pruebas.

<!-- Casos de prueba -->
#### Casos de prueba.[Casos de Prueba (1).xlsx](https://github.com/zFerchou/Modulo-Servidor/files/14961583/Casos.de.Prueba.1.xlsx)


#### Ejecución.
Evidencia de Ejecución de Casos de prueba: 

<!-- Iniciando -->
## Iniciando

<!-- Requisitos -->
### Requisitos
* Tener Instalado SQL Server
* Tener Instalado Visual Studio
* Instalar el FrameWork de ASP.NET
* Tener un sistema operativo de gama media
* Tener acceso a la base de datos del proyecto
## Plan de Iteraciones

El desarrollo del proyecto se organizará en iteraciones de 2 semanas cada una, donde se abordarán las siguientes tareas y actividades:

### Iteración 1 (Semana 1 y 2)
- Actualización de pantallas de Historias de Usuario según los requerimientos.
- Corrección del Diagrama de Componentes.
- Mapeo de Historias de Usuario con casos de prueba para validar flujos alternos.
- Revisión y corrección del Caso de Prueba 1 en datos y acciones de entrada.
- Mapeo de casos de prueba exitosos y no exitosos con los requerimientos.

### Iteración 2 (Semana 3 y 4)
- Implementación de estándares de codificación.
- Revisión y ajuste de la arquitectura del proyecto.
- Elaboración del diagrama de actividades.

### Iteración 3 (Semana 5 y 6)
- Creación y ejecución de casos de prueba.
- Evaluación y corrección de la ejecución de casos de prueba.
- Implementación de la documentación del proyecto.

### Iteración 4 (Semana 7 y 8)
- Implementación de mejoras y correcciones según retroalimentación.
- Revisión y ajuste de la documentación del proyecto.
- Preparación para la entrega final.

### Iteración 5 (Semana 9 y 10)
- Preparación y realización de pruebas de aceptación.
- Corrección de errores y ajustes finales.
- Entrega final del proyecto.

Durante cada iteración se llevará a cabo reuniones de revisión y planificación para evaluar el avance, identificar posibles riesgos y ajustar el plan de trabajo según sea necesario.
  

<!-- Instalación -->
### Instalación
Para poder trabajar con el proyecto tuvimos que realizar una serie de pasos los cuales nos permitieran trabajar con el proyecto
esto con la intencion de que cada integrante pudiera realizarlo de manera local en su respectivo equipo de trabajo

* Instalación de tortoise

Usamos el software de tortoise para bajar el proyecto

* Acceder con las credenciales proporcionadas

Accedimos a la base de datos y al proyecto con las credenciales que nos proporcionaron las personas de nad


* Instalar Proyecto

Para instalar el proyecto nos dirijimos al software de tortoise y colocamos la URL que nos proporciono la 
empresa donde se encuentra guardado el proyecto y de ahi lo descargamos

* Una vez terminado ejecutamos el proyecto en nuestro Visual Studio y lo corremos como Sitio web
  



## Participantes
* Jesús Yael Padrón Grimaldo
* Luis Fernando Medina Arredondo
* Carol Vanessa Gallegos Martínez
* Everardo Guadalupe Torres Tovar
* Miguel Ángel Rodríguez Mejia


[contribuidores-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
