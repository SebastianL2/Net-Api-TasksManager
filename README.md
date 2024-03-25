# Gestor de Tareas API

La API de Gestor de Tareas es una aplicación web diseñada para la gestión eficiente de tareas y asignaciones. Los usuarios pueden crear, asignar, hacer seguimiento de tareas y recibir notificaciones al completarlas.

## Empezar

Para comenzar a usar la API de Gestor de Tareas:

1. **Clonar el Repositorio**: Clonar el repositorio.
2. **Instalación**: Instalar las dependencias según se especifica en la documentación del proyecto.
3. **Configuración**: Configurar variables de entorno y configuraciones.
4. **Uso**: Ejecutar la API y explorar las funcionalidades.

### Características Clave

- **Autenticación y Autorización de Usuarios**: Utiliza JSON Web Tokens (JWT) para un acceso seguro.
- **Operaciones CRUD para Tareas y Asignaciones**: Permite operaciones de Crear, Leer, Actualizar y Borrar.
- **Integración con Servicio de Correo Electrónico Externo**: Envía notificaciones a través de un servicio de correo electrónico externo.

## Desafíos Enfrentados

Durante el desarrollo de la API de Gestor de Tareas, nos enfrentamos a varios desafíos, incluyendo:

- **Implementación Segura de SMTP para Notificaciones por Correo Electrónico**: Garantizar una implementación segura y confiable de SMTP para las notificaciones por correo electrónico planteó obstáculos iniciales.
- **Aplicación Consistente de los Principios de Arquitectura Limpia**: Mantener la consistencia en la aplicación de los principios de Arquitectura Limpia durante todo el proceso de desarrollo requirió atención y esfuerzo continuos.

## Arquitectura

TaskManager garantiza escalabilidad y mantenibilidad con una sólida separación de preocupaciones en sus capas. La base de código sigue las mejores prácticas de la industria, incorporando principios SOLID e inyección de dependencias.
