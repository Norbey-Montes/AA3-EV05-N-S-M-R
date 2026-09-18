# 💻 CompuClick — Tienda de Computadores en Línea

**CompuClick** es un proyecto formativo desarrollado para el programa de **Análisis y Desarrollo de Software (ADSO)** del SENA. Consiste en el desarrollo de un sistema de información web orientado a la comercialización directa de equipos de cómputo, incluyendo computadores portátiles, equipos de escritorio y torres gamer.

Este repositorio contiene la **primera versión funcional del Front-End** (Scaffolding), estructurada bajo la arquitectura **MVC (Modelo-Vista-Controlador)** en preparación para la futura integración con PHP y bases de datos.

## 🚀 Estado del Proyecto
**Fase Actual:** Desarrollo de Interfaces (Front-End) y estructuración de carpetas.

### Funcionalidades implementadas (UI):
- ✅ **Página de Inicio (Home):** Navegación, bienvenida, misión y formulario de contacto.
- ✅ **Página de Catálogo:** Listado dinámico de los equipos disponibles para la venta.
- ✅ **Página de Login:** Interfaz de inicio de sesión de usuarios con recuperación de contraseña.
- ✅ **Diseño Responsivo:** Adaptabilidad para dispositivos móviles y escritorio.

## 🛠️ Tecnologías Utilizadas
En esta fase inicial, el proyecto se construyó utilizando tecnologías del lado del cliente:
* **HTML5:** Estructuración semántica.
* **CSS3:** Estilos, Flexbox y diseño responsivo (sin frameworks externos).
* **JavaScript (Vanilla):** Lógica básica para el menú hamburguesa y el manejo de vistas dinámicas.

## 📁 Estructura del Proyecto (Patrón MVC)
La estructura de directorios ha sido diseñada para separar la lógica de negocio de las interfaces, preparándose para el desarrollo Backend:

```text
Proyecto/
│
├── app/                  # Lógica principal y Vistas de la aplicación
│   ├── controllers/      # Controladores (Próximamente en PHP)
│   ├── models/           # Modelos de bases de datos (Próximamente en PHP)
│   └── views/            # Interfaces de usuario (HTML actual)
│       ├── inicio/
│       ├── layouts/
│       ├── listado/
│       └── login/
│
├── config/               # Archivos de configuración del sistema
│
├── public/               # Archivos de acceso público (Estilos, scripts e imágenes)
│   ├── css/
│   ├── img/
│   └── js/
│
└── index.php             # Enrutador principal del proyecto