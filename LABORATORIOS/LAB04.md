# LABORATORIO 4 - Scrum - DI/IOC

## PRE-RREQUISITOS
- Java OpenJDK Runtime Environment: 17.x.x
- Apache Maven: 3.9.x
- SpringBoot
- Docker
- AzureDevops
- Sonar
- Jacoco

## OBJETIVOS
1. Planeación de un proyecto de software.
2. Entender arquitectura cliente servidor.
3. Inyección de dependencias - Inversión de control.
4. Manejo de bases de datos no relacionales.
6. Definición de API Rest Con SpringBoot.
7. Realizar Análisis estático para garantizar calidad del código y detección de deuda técnica.
8. Integrar pruebas unitarias en el desarrollo del producto.


## CASO DE NEGOCIO - ADMINISTRADOR DE TAREAS.

El proyecto consiste en una aplicación de gestión de tareas personales donde los usuarios podrán agregar, marcar como completadas, y eliminar tareas. La aplicación contará con una interfaz web y se conectará a un API REST desarrollado en Spring Boot. El backend permitirá la inyección de dependencias para el manejo de datos, pudiendo optar entre una base de datos en MongoDB Cloud o un archivo de texto plano para almacenar las tareas.

## REQUERIMIENTOS
- El usuario debe poder agregar tareas con una descripción.
- El usuario debe poder marcar tareas como completadas.
- El usuario debe poder eliminar tareas.

## ÉPICAS
1. Gestión de Tareas: Permitir a los usuarios la creación, actualización, y eliminación de tareas mediante una interfaz web. Puede definir épicas para front y para back.

## SPRINTS
1. Sprint 1: Configuración general del proyecto (Configuración de ambientes, scaffolding, configuración de las bases de datos)
2. Sprint 2: Implementación del API REST con opciones de persistencia en MongoDB Cloud o archivo de texto plano.
3. Sprint 3: Conexión del front-end con la API y pruebas finales.

## FEATURES
1. Crear una interfaz web que permita agregar tareas.
2. Visualizar una lista de tareas.
3. Marcar tareas como completadas.
4. Eliminar tareas de la lista.

## MODELO DE ARQUITECTURA

![Screenshot_2](assets/TareasArquitectura.drawio.png)

## PASOS PARA CONSTRUIR EL PROYECTO

1- Cree un proyecto en GitHub para el back y para el front de manera independiente puede utilizar la siguiente guía para definir el scaffolding del back <a href="https://ragunathrajasekaran.medium.com/https-medium-com-ragunathrajasekaran-lets-learn-full-stack-development-part2-7986debc485d" target="_blank">Ver guía</a> No olvide el que el proyecto debe ser maven. Mantenga el esquema de nombramiento de los artefactos.

## PLANEACIÓN DEL PROYECTO.
- Esta sección tiene como objetivo realizar toda la planificación que el equipo de desarrollo requiere para poder dar inicio al proyecto planteado. Para este objetivo utilizaremos Azure DevOps.

- <a href="AZ400-DesigningandImplementingMicrosoftDevOpsSolutions/Instructions/Labs/AZ400_M01_L01_Agile_Plan_and_Portfolio_Management_with_Azure_Boards.md at master · MicrosoftLearning/AZ400-DesigningandImplementingMicrosoftDevOpsSolutions · GitHub">Tutorial Completo</a>

  1. Cree una cuenta en azureDevOps (Utilice el correo de la escuela) <a href="https://go.microsoft.com/fwlink/?LinkId=2014881" target="_blank">Crear una cuenta</a>
  2. Una vez ingresa deberá crear el proyecto. (Este proceso solo lo realiza un miembro del grupo) Debe seleccionar en configuración avanzada tipo de proceso Scrum.
  3. Cree un equipo en el siguiente tutorial encontrará cómo hacerlo <a href="https://github.com/microsoft/azuredevopslabs/tree/master/labs/azuredevops/agile" target="_blank">Creando equipos</a>, para este proceso todos 
     los integrantes deberán tener una cuenta en AzureDevOps.
  4. Integre los repositorios de gitHub en la configuración de AzureDevOps
       From your project in Azure DevOps, go to Project settings > GitHub connections.
       To add or remove repositories, select the More options ellipses for the connection and choose Add repositories or Remove repositories from the menu.
  5. Defina los spring del proyecto.
  6. Definiendo la épica:
     1- En la sección de Board --> Work Items --> new work item --> Epic --> complete la información de la épica incluyendo la descripción.
  7. Añada los features a la épica previamente debe conectar su repo de GITHUB
  8.  Defina las historias de usuario por cada feature definida.
 

## IMPLEMENTACIÓN.
De aceurdo a la planeación realizada divida las tareas de implementación.
A continuación detallamos diferentes tutoriales para el manejo técnico para cada etapa.

  1. Creación de proyecto APIREST <a href="https://blog.codmind.com/mi-primer-api-rest-con-spring-boot/">Documentación 1<a/> <a href="https://programandoenjava.com/crear-un-rest-api-con-spring-boot/">Documentación 2</a>
  2. Consumir APIREST HTML - JAVASCRIPT <a href="https://helpcenter.itmplatform.com/es/project/ejemplo-de-uso-de-api-con-html-javascript/">Ejemplo básico<a/> Utilizar buenas prácticas de programación separación en archivos emplear CSS para mejorar la usabilidad.
  3. Configuración e integración <a href="https://www.mongodb.com/resources/products/compatibilities/spring-boot#getting-started-with-spring-initializr">MongoDB - Atlas</a>
  4. Utilizar integración con Sonar y JACOCO para análisis estático y calidad del código, esto implica el desarrollo de pruebas unitarias.

## GUIA DE ENTREGA Y PRESENTACIÓN
  1. Deben conformar grupos de 4 personas.
  2. El laboratorio se realizará en 2 partes.
  3. Cada estudiante deberá participar en el desarrollo. (Se verá reflejado en los repositorios y en el tablero del proyecto)
  4. Una vez que una caracteristica se encuentra finalizada los merge se validarán mediante pull request.
  5. Deben integrar al equipo al profesor y monitor (Usuarios con cuenta institucional de la escuela)
  6. En el readme deberán generar toda la documentación del proyecto tanto en back como en front.
  7. Fecha de entrega en la semana 7.


