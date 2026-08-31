# Base de Datos - YouTube Music

Este proyecto universitario consiste en el diseño, modelado y creación de una base de datos relacional para una plataforma de streaming de música, inspirada en YouTube Music. A lo largo del proyecto, se aplicaron metodologías de ingeniería de bases de datos abarcando desde el relevamiento inicial de requerimientos hasta la implementación física en SQL.

## Estructura del Proyecto

El desarrollo del proyecto está organizado en las siguientes etapas secuenciales, cada una con un objetivo específico en el ciclo de vida de la base de datos:

### Etapa 1 & 2: Relevamiento y Diseño Conceptual
En esta etapa inicial se realizó el levantamiento de los **requerimientos funcionales** del sistema (qué datos se necesitan almacenar y cómo se relacionan). 
El resultado principal de esta fase es el **Modelo Entidad-Relación (DER)** o Diagrama Conceptual.
*   **Entidades Principales**: Se identificaron entidades clave como *Usuarios, Canciones, Playlists, Artistas, Álbumes*, entre otras.
*   **Relaciones**: Se definieron las cardinalidades y restricciones de negocio, como la asociación de canciones a múltiples playlists, y la autoría de artistas sobre canciones y álbumes.

### Etapa 3: Diseño Lógico
El modelo conceptual fue traducido al **Modelo Relacional**. En esta fase se aplicaron reglas de **normalización** para evitar redundancias e inconsistencias.
*   Se definieron los esquemas de las tablas.
*   Se establecieron las **Claves Primarias (PK)** y **Claves Foráneas (FK)** para mantener la integridad referencial.
*   Se identificaron los tipos de datos óptimos para cada atributo.

### Etapa 4: Implementación Física (Scripts SQL)
La implementación real de la base de datos se realizó mediante scripts SQL, divididos en tres áreas fundamentales:
*   **DDL (Data Definition Language)**: Scripts utilizados para la creación de las tablas, restricciones (`CONSTRAINTS`), vistas y estructura general de la base de datos.
*   **DML (Data Manipulation Language)**: Scripts para el poblamiento inicial de la base de datos (`INSERT`, `UPDATE`, `DELETE`) con datos de prueba, permitiendo validar la estructura.
*   **DQL (Data Query Language)**: Elaboración de consultas complejas (`SELECT` con `JOINs`, subconsultas, agrupamientos y funciones de agregación) para extraer información útil de negocio a partir de los datos almacenados.

### Etapa 5: Presentación
Contiene el material audiovisual (presentación PPTX) utilizado para la defensa del Trabajo Integrador, resumiendo las decisiones de diseño arquitectónico y las tecnologías involucradas.

## Tecnologías y Herramientas
*   **Lenguaje**: SQL
*   **Modelado de Datos**: Herramientas CASE para generación de diagramas DER (Entidad-Relación).

## Conclusión y Aprendizaje
Este proyecto permitió consolidar los conocimientos teóricos sobre bases de datos relacionales, poniéndolos en práctica en un caso de uso real y escalable. Se adquirió experiencia en la recolección de requerimientos, diseño normalizado para garantizar la integridad de los datos, y desarrollo de consultas SQL avanzadas para la explotación de la información.
