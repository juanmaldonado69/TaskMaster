# TaskMaster

Objetivo:

Crear una aplicación web que permita a los equipos de trabajo gestionar tareas, asignarlas a miembros del equipo, establecer prioridades, y hacer seguimiento del progreso.

•	Objetivos generales:

o	Mejorar la colaboración y la gestión de tareas.
o	Utilizar LocalStack para simular servicios en la nube durante el desarrollo y pruebas.


1. Arquitectura y Planificación

Componentes Clave:
Frontend: Angular para la interfaz de usuario.
Backend: .NET Core para los servicios y APIs.
Base de Datos: MongoDB para almacenamiento de datos.
Integración en la Nube: Uso de LocalStack para simular servicios en la nube.
DevOps: Pipelines CI/CD para automatización de despliegues y pruebas.

Dado el uso de componentes como .NET Core para el backend, MongoDB para la base de datos, y la posibilidad de implementar servicios de forma independiente (a través de LocalStack y Pipelines CI/CD), se podría decir que la arquitectura más adecuada para este proyecto es una arquitectura de microservicios

Esta configuración permite un desarrollo modular y escalable, aunque el grado de descomposición en microservicios puede variar según cómo se estructuren y desplieguen los diferentes servicios 
Integración en la Nube con LocalStack
2. Servicios Simulados:
	LocalStack: Utilizado para simular servicios de AWS localmente, incluyendo:
	Amazon S3: Para almacenamiento de archivos.
    Amazon DynamoDB: Para almacenamiento NoSQL.
	Amazon SNS: Para notificaciones y mensajería.
•	Configuración de LocalStack:
	Instalación: instalación  y configuró LocalStack (e.g., usando Docker).
	Configuración de Servicios: configuración de LocalStack para emular los servicios necesarios para el proyecto.
•	Desarrollo y Pruebas:
	Desarrollo Local: Cómo LocalStack facilita el desarrollo al simular servicios de AWS sin costos asociados.
	Pruebas: Estrategias para probar la integración con los servicios simulados en LocalStack.
•	Beneficios y Resultados:
    Ahorro de Costos: Evitar costos asociados con el uso real de servicios en la nube durante el desarrollo.
	Flexibilidad: Capacidad de probar y desarrollar en un entorno controlado y local.
