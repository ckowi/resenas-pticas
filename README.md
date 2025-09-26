# resenas-opticas
sitio web de reseñas de equipos opticos.
# Proyecto: Sitio de Reseñas de Óptica

Este repositorio contiene el código fuente y el contenido para un sitio web de reseñas de productos ópticos (binoculares, telescopios, etc.), construido para ser rápido, escalable y optimizado para SEO.

## 🎯 Objetivo

El objetivo es crear una plataforma de nicho que ofrezca reseñas de alta calidad, sea fácil de mantener y esté monetizada a través del programa de Afiliados de Amazon. La arquitectura está diseñada para ser modular y con un rendimiento excepcional.

## 🚀 Tech Stack Principal (Enfoque Cloudflare)

La selección de tecnologías prioriza el rendimiento, la escalabilidad y un flujo de trabajo de desarrollo moderno, aprovechando al máximo el ecosistema de Cloudflare.

*   **Framework Frontend**: **Astro** (Generación de sitios estáticos con hidratación parcial a través de _Islands Architecture_).
*   **Gestión de Contenido**: **Markdown/MDX** directamente en el repositorio de Git para simplicidad y control de versiones.
*   **Infraestructura y Despliegue (Cloudflare-centric)**:
    *   **Hosting y CI/CD**: **Cloudflare Pages** para despliegues automáticos, continuos y hosting global.
    *   **Almacenamiento de Assets**: **Cloudflare R2** para almacenar y servir imágenes y otros medios de forma eficiente y económica.
    *   **CDN y Rendimiento**: **Cloudflare CDN** para una entrega de contenido ultrarrápida y optimizaciones automáticas.
    *   **Lógica en el Edge**: **Cloudflare Workers** para funcionalidades dinámicas (ej: personalización, A/B testing) sin un backend tradicional.
*   **Estilos**: **Tailwind CSS** para un desarrollo de UI rápido y basado en utilidades.
*   **SEO**: Herramientas nativas de Astro, generación de sitemaps y marcado estructurado (JSON-LD) para `Product` y `Review`.

## 🗺️ Fases del Proyecto (Resumen)

1.  **Fase 0 - Estrategia**: Investigación de nicho y planificación de contenido.
2.  **Fase 1 - Base y UX**: Creación del repo, arquitectura de URLs y wireframes.
3.  **Fase 2 - Infraestructura Técnica**: Configuración de Cloudflare Pages, R2 y dominio.
4.  **Fase 3 - Contenido Base**: Desarrollo de layouts y publicación de las primeras reseñas.
5.  **Fase 4 - Despliegue Oficial**: Lanzamiento del sitio a producción y activación de afiliados.
6.  **Fase 5 - Optimización SEO/UX**: Refinamiento de metadatos, interlinking y accesibilidad.
7.  **Fase 6 - Expansión**: Implementación de funciones dinámicas con Cloudflare Workers.
8.  **Fase 7 - Crecimiento**: Automatización y análisis de métricas para escalar.

## ⚡ Cómo Empezar

1.  **Clonar el repositorio**:
    ```
    git clone [URL-DEL-REPOSITORIO]
    cd [NOMBRE-DEL-REPOSITORIO]
    ```
2.  **Instalar dependencias**:
    ```
    npm install
    ```
3.  **Iniciar el servidor de desarrollo**:
    ```
    npm run dev
    ```

El sitio estará disponible en `http://localhost:4321`.

---
