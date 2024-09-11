# LABORATORIO 4 - Scrum - DI/IOC

## PRE-RREQUISITOS
- Java OpenJDK Runtime Environment: 17.x.x
- Apache Maven: 3.9.x
- SpringBoot
- Docker
- AzureDevops

## OBJETIVOS
1. Planeación de un proyecto de software.
2. Entender arquitectura cliente servidor.
3. Inyección de dependencias - Inversión de control.
4. Manejo de bases de datos no relacionales.
6. Definición de API Rest Con SpringBoot.


##CASO DE NEGOCIO - ADMINISTRADOR DE TAREAS.

El proyecto consiste en una aplicación de gestión de tareas personales donde los usuarios podrán agregar, marcar como completadas, y eliminar tareas. La aplicación contará con una interfaz web y se conectará a un API REST desarrollado en Spring Boot. El backend permitirá la inyección de dependencias para el manejo de datos, pudiendo optar entre una base de datos en MongoDB Cloud o un archivo de texto plano para almacenar las tareas.

##REQUERIMIENTOS
- El usuario debe poder agregar tareas con una descripción.
- El usuario debe poder marcar tareas como completadas.
- El usuario debe poder eliminar tareas.

##ÉPICAS
1. Gestión de Tareas: Permitir a los usuarios la creación, actualización, y eliminación de tareas mediante una interfaz web.

##SPRINTS
1. Sprint 1: Configuración general del proyecto (Configuración de ambientes, scaffolding, configuración de las bases de datos)
2. Sprint 2: Implementación del API REST con opciones de persistencia en MongoDB Cloud o archivo de texto plano.
3. Sprint 3: Conexión del front-end con la API y pruebas finales.

##FEATURES
1. Crear una interfaz web que permita agregar tareas.
2. Visualizar una lista de tareas.
3. Marcar tareas como completadas.
4. Eliminar tareas de la lista.

##MODELO DE ARQUITECTURA

![Screenshot_2](LABORATORIOS/assets/TareasArquitectura.drawio.png)



