# TaskMaster
Crear una aplicación web que permita a los equipos de trabajo gestionar tareas, asignarlas a miembros del equipo, establecer prioridades, y hacer seguimiento del progreso.

1. Arquitectura y Planificación

Componentes Clave:
Frontend: Angular para la interfaz de usuario.
Backend: .NET Core para los servicios y APIs.
Base de Datos: MongoDB para almacenamiento de datos.
Integración en la Nube: Uso de LocalStack para simular servicios en la nube.
DevOps: Pipelines CI/CD para automatización de despliegues y pruebas.

Dado el uso de componentes como .NET Core para el backend, MongoDB para la base de datos, y la posibilidad de implementar servicios de forma independiente (a través de LocalStack y Pipelines CI/CD), se podría decir que la arquitectura más adecuada para este proyecto es una arquitectura de microservicios

Esta configuración permite un desarrollo modular y escalable, aunque el grado de descomposición en microservicios puede variar según cómo se estructuren y desplieguen los diferentes servicios 