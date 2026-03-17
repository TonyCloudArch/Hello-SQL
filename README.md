📊 Hello-SQL: Laboratorio de Ingeniería de Datos
Este repositorio contiene mis avances y experimentos del curso de SQL de MoureDev, ejecutados bajo una arquitectura de nivel profesional.

🏗️ Arquitectura del Proyecto
A diferencia de una instalación local estándar, este laboratorio opera sobre:

Hardware: Servidor físico HP ProLiant (On-premise).

OS: Ubuntu Server 24.04 LTS.

Orquestación: Docker & Docker Compose.

Motor: MySQL 8.0 contenedorizado.

🚀 Despliegue
El entorno se levanta mediante un túnel de puertos (3307 -> 3306) para evitar conflictos con otros servicios en el servidor:

Bash
docker-compose up -d
🧠 Aprendizajes Clave
Infraestructura: Gestión de volúmenes persistentes y redes en Docker.

SQL DDL: Creación de esquemas, tablas y definición de tipos de datos.

SQL DML: Manipulación de registros, filtrado avanzado y optimización de consultas.

Versionamiento: Flujo de trabajo profesional con Git y GitHub mediante tokens de acceso.
