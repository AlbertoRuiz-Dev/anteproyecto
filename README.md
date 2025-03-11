# Anteproyecto: Alikin

## 1. Título del proyecto
Alikin: Red Social Musical

## 2. Autor del proyecto
Alberto Ruiz Díaz

## 3. Introducción del proyecto
Alikin (derivado de "aliquindoi") será una aplicación web que fusiona los conceptos de red social estilo Reddit con una plataforma musical al estilo Spotify. El proyecto busca crear un espacio donde los amantes de la música puedan conectarse, compartir contenido y descubrir nueva música a través de una experiencia social integrada

La plataforma permitirá a los usuarios registrarse, crear perfiles personalizados, unirse a comunidades temáticas basadas en géneros musicales o artistas, y mantener un feed personalizado con actualizaciones de las personas y comunidades que siguen. El elemento diferenciador será una biblioteca musical compartida con un reproductor integrado, donde los usuarios podrán descubrir, compartir, comentar y escuchar música directamente desde la plataforma 

## 4. Finalidad
La finalidad de Alikin es crear un ecosistema digital donde la pasión por la música sea el eje central de las interacciones sociales. Este proyecto puede servir para:

- Fomentar el descubrimiento de música nueva basada en recomendaciones de una comunidad de usuarios con intereses similares
- Crear espacios de discusión organizados por temáticas musicales específicas
- Facilitar la conexión entre personas con gustos musicales afines
- Proporcionar a artistas emergentes y establecidos una plataforma adicional para compartir su música y conectar con audiencias
- Generar un ecosistema donde el contenido musical y las conversaciones sobre música se retroalimenten
- Permitir la reproducción directa de música dentro de la plataforma, mejorando la experiencia de usuario al no requerir aplicaciones externas para escuchar las recomendaciones

## 5. Objetivos
Una vez implementado, Alikin permitirá a los usuarios:

- Crear cuentas personalizadas con perfiles que reflejen sus gustos musicales
- Seguir a otros usuarios y recibir actualizaciones de su actividad en un feed personalizado
- Unirse y participar en comunidades temáticas centradas en géneros, artistas o aspectos específicos de la música
- Publicar contenido en forma de texto, imágenes y enlaces a música
- Acceder a una biblioteca musical compartida donde podrán escuchar, guardar y compartir canciones
- Reproducir música directamente en la plataforma mediante un reproductor integrado sin necesidad de aplicaciones externas
- Crear y gestionar listas de reproducción personalizadas directamente en la plataforma
- Interactuar con el contenido mediante comentarios y sistemas de votación similar a Reddit
- Descubrir nueva música a través de recomendaciones basadas en la actividad de la comunidad

## 6. Medios hardware y software a utilizar
### Hardware:
- Ordenador de desarrollo con capacidad suficiente para ejecutar entornos de desarrollo web
- Servidor para el despliegue de la aplicación (posiblemente utilizando servicios en la nube)
- Dispositivos para pruebas (ordenador, smartphone)

### Software:
- **Backend**: Django y Django REST Framework para crear una API robusta
- **Frontend**: Angular para desarrollar una interfaz de usuario dinámica y responsive
- **Reproductor de música**: Biblioteca Angular específica como ngx-audio-player o integración con Web Audio API
- **Base de datos**: PostgreSQL para el almacenamiento persistente de datos
- **Control de versiones**: Git y GitHub para la gestión del código
- **Herramientas de despliegue**: Docker para la contenerización
- **Servicios de almacenamiento**: AWS S3 o similar para almacenar archivos de audio y multimedia
- **Herramientas de prueba**: Unittest para pruebas unitarias básicas
- **Gestión de proyecto**: Trello para seguimiento de tareas

## 7. Planificación
El desarrollo del proyecto se ajustará a un plazo máximo de 3 meses, con la siguiente distribución:

### Fase 1: Análisis y diseño (2 semanas)
- Análisis de requisitos esenciales
- Diseño simplificado de la arquitectura del sistema
- Diseño de la base de datos
- Creación de wireframes básicos de la interfaz de usuario
- Definición de funcionalidades prioritarias (MVP)
- **Investigación y selección de bibliotecas para el reproductor de música**

### Fase 2: Desarrollo del Backend (4 semanas)
- Configuración del entorno Django y Django REST
- Implementación de modelos de datos principales
- Desarrollo de API RESTful para las funcionalidades esenciales
- Implementación del sistema de autenticación
- **Desarrollo de la API para gestión y streaming de archivos de audio**
- Configuración del almacenamiento de archivos de audio
- Pruebas unitarias básicas

### Fase 3: Desarrollo del Frontend (4 semanas)
- Configuración del entorno Angular
- Implementación de componentes clave de UI
- Desarrollo de servicios para comunicación con la API
- **Implementación del reproductor de música integrado con controles básicos (reproducción, pausa, saltar, volumen)**
- **Desarrollo de la interfaz de biblioteca musical y listas de reproducción**
- Implementación de la interfaz de usuario para las funcionalidades principales

### Fase 4: Integración y Finalización (2 semanas)
- Integración de todos los componentes
- **Pruebas específicas del reproductor de música en diferentes dispositivos y navegadores**
- Pruebas de funcionalidad general
- Corrección de errores críticos
- Optimización básica de rendimiento

### Fase 5: Despliegue (1 semana)
- Configuración de entorno de producción
- Despliegue de la versión MVP
- Elaboración de documentación técnica básica
- **Verificación final del reproductor de música en el entorno de producción**

**Duración total**: 13 semanas (aproximadamente 3 meses)

Consideraciones sobre el alcance para cumplir con el plazo de 3 meses:
- El reproductor de música será una prioridad máxima, asegurando su correcto funcionamiento
- Las características iniciales del reproductor se limitarán a funcionalidades esenciales
- Se priorizarán las funcionalidades esenciales para el MVP (Producto Mínimo Viable)
- La interfaz se centrará en usabilidad más que en diseño elaborado
- Las pruebas se limitarán a asegurar la funcionalidad básica
- Algunas características avanzadas podrían quedar para futuras iteraciones
- Se optimizará el tiempo mediante el uso de bibliotecas y componentes existentes