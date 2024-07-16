# ForoHub

## Descripción
En este desafio vamos a replicar este proceso a nivel de back end y, para eso, crearemos una API REST usando Spring.

Nuestra API se centrará específicamente en los tópicos, y debe permitir a los usuarios:

    Crear un nuevo tópico;
    Mostrar todos los tópicos creados;
    Mostrar un tópico específico;
    Actualizar un tópico;
    Eliminar un tópico.

Es lo que normalmente conocemos como CRUD* (CREATE, READ, UPDATE, DELETE) y es muy similar a lo que desarrollamos en LiterAlura, pero ahora de forma completa, agregando las operaciones de UPDATE y DELETE, y usando un framework que facilitará mucho nuestro trabajo.

*Traducción libre (en orden): Crear, Consultar, Actualizar y Eliminar.

En resumen, nuestro objetivo con este challenge es implementar una API REST con las siguientes funcionalidades:

    API con rutas implementadas siguiendo las mejores prácticas del modelo REST;
    Validaciones realizadas según las reglas de negocio;
    Implementación de una base de datos relacional para la persistencia de la información;
    Servicio de autenticación/autorización para restringir el acceso a la información.


En esta primera fase, nos sumergiremos en la configuración del entorno de desarrollo Java para nuestro desafío de construir el ForoHub. Asegúrate de tener los siguientes programas, archivos y versiones:

    Java JDK: versión 17 en adelante - Descarga la última versión LTS de Java gratuita
    Maven: versión 4 en adelante
    Spring Boot: versión 3 en adelante - https://start.spring.io/
    MySQL: versión 8 en adelante *- 

(Instalador para Windows)
IDE (Entorno de desarrollo integrado) IntelliJ IDEA - opcional -

*Aquí tienes un artículo Alura Latam sobre la instalación de MySQL en Windows:

Configuración al crear el proyecto con Spring Initializr:

    Java (versión 17 en adelante)
    Maven (Initializr utiliza la versión 4)
    Spring Boot
    Proyecto en formato JAR

Dependencias para agregar al crear el proyecto con Spring Initializr:

    Lombok
    Spring Web
    Spring Boot DevTools
    Spring Data JPA
    Flyway Migration
    MySQL Driver
    Validation
    Spring Security


## Nota
Esta aplicacion representa un desafío dentro del programa One de Alura Latam, de BackEnd con fines educativos.
Att. Max Enoc Moreno Navarrete

