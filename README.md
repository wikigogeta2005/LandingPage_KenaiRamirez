# LandingPage_KenaiRamirez
# 🚀 Marca Personal Digital - Axel Kenai Ramirez

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)

## Organizacion del proyecto

Portafolio-Axel/
│
├── css/                    # Estilos y diseño
│   └── styles.css          # Archivo unificado de CSS (Variables, Grid, Responsive)
│
├── Imagenes/               # Recursos visuales (Activos del sitio)
│   ├── Yo.png              # Foto principal del Hero
│   ├── Autoretrato.png     # Foto de la sección biográfica
│   ├── Espe.png            # Logos institucionales
│   ├── avion.png           # Iconos de proyectos
│   └── ...                 # Demás iconos y recursos gráficos
│
├── index.html              # Punto de entrada (Estructura semántica HTML5)
│
├── Dockerfile              # Instrucciones para la creación de la imagen Docker
├── .dockerignore           # Archivos excluidos del contenedor (seguridad y peso)
└── README.md               # Documentación técnica del repositorio

## 📌 Descripción del Proyecto
Este proyecto consiste en el diseño y desarrollo de una **Landing Page Profesional** construida desde cero (Vanilla CSS/HTML), enfocada en la marca personal. El objetivo es proyectar profesionalismo, organización visual y dominio de tecnologías de infraestructura moderna como **Docker** y **Nginx**.

### Características Principales:
- **HTML5 Semántico**: Estructura optimizada para accesibilidad y SEO.
- **Responsive Design**: Adaptabilidad total a dispositivos móviles mediante Media Queries y Flexbox/Grid.
- **Estética Tech-Minimalist**: Uso de teoría del color (Glassmorphism), tipografías modernas (Poppins) y jerarquía visual clara.
- **Despliegue Contenerizado**: Configuración lista para producción usando Docker.

---

## 🛠️ Tecnologías Utilizadas
- **Lenguajes**: HTML5, CSS3 (Custom Properties, Flexbox, CSS Grid).
- **Iconografía**: Font Awesome 6.
- **Tipografía**: Google Fonts (Poppins).
- **Servidor Web**: Nginx (Alpine-based).
- **Contenedores**: Docker.

---

## 🐳 Guía de Despliegue con Docker

Sigue estos pasos para arrancar el contenedor y visualizar la landing page en tu entorno local.

### Requisitos Previos
- Tener instalado [Docker Desktop](https://www.docker.com/products/docker-desktop/) o Docker Engine.

### 1. Construir la Imagen
Desde la raíz del proyecto (donde se encuentra el `Dockerfile`), ejecuta:

## Ejecucion Local

1. Construir la Imagen: docker build -t kenaposo2005/mi-curriculum:latest .
2. Ejecutar contenedor: docker run -d -p 8086:80 kenaposo2005/mi-curriculum:latest
3. Acceder al sitio: http://localhost:8086/

## Imagen en Docker Hub
1. URL Imagen: https://hub.docker.com/repository/docker/kenaposo2005/mi-curriculum/general
2. Descargar imagen: docker pull kenaposo2005/mi-curriculum:latest
3. Ejecutar imagen publica: docker run -d -p 8086:80 kenaposo2005/mi-curriculum:latest

