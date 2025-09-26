# resenas-opticas
sitio web de reseñas de equipos opticos.
# Proyecto: Sitio de Reseñas de Óptica

Este repositorio contiene el código fuente y el contenido para un sitio web de reseñas de productos ópticos (binoculares, telescopios, etc.), construido para ser rápido, escalable y optimizado para SEO.

## 🎯 Objetivo

El objetivo es crear una plataforma de nicho que ofrezca reseñas de alta calidad, sea fácil de mantener y esté monetizada a través del programa de Afiliados de Amazon. La arquitectura está diseñada para ser modular y con un rendimiento excepcional.

## 🚀 Tech Stack Principal

La selección de tecnologías prioriza el rendimiento, la escalabilidad y un flujo de trabajo de desarrollo moderno.

*   **Framework Frontend**: **Astro** (Generación de sitios estáticos con _Islands Architecture_).
*   **Gestión de Contenido**: **Markdown/MDX** directamente en el repositorio de Git.
*   **Hosting y Despliegue Continuo (CI/CD)**: **Netlify** para builds automáticos desde Git y hosting de la aplicación principal.
*   **Infraestructura de Rendimiento y Datos (Cloudflare)**:
    *   **CDN y Seguridad**: **Cloudflare CDN** para una entrega de contenido global, seguridad y optimizaciones de rendimiento.
    *   **Almacenamiento de Medios**: **Cloudflare R2** para almacenar imágenes originales y otros activos de manera económica.
    *   **Optimización de Imágenes**: **Cloudflare Images** para transformar, optimizar y servir imágenes en formatos modernos (WebP/AVIF) sobre la marcha.
    *   **Lógica en el Edge**: **Cloudflare Workers** para futuras funciones dinámicas (ver "Expansión a Futuro").
*   **Estilos**: **Tailwind CSS** para un desarrollo de UI rápido y basado en utilidades.
*   **SEO**: Herramientas nativas de Astro, generación de sitemaps y marcado estructurado (JSON-LD).

## 🗺️ Expansión a Futuro

Aunque el MVP (Mínimo Producto Viable) se centrará en un sitio estático, el plan a largo plazo incluye:

*   **Backend Serverless**: Desarrollar funciones en **Cloudflare Workers** para manejar lógica del lado del servidor.
*   **Integración con API de Amazon**: Crear un servicio para interactuar con la **API de Publicidad de Productos de Amazon**, permitiendo obtener datos de productos de forma dinámica y asegurar el cumplimiento.
*   **Base de Datos**: Integrar una base de datos (posiblemente una solución Edge como Cloudflare D1) para habilitar funcionalidades de usuario como "favoritos", "comparaciones" o "listas guardadas".

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

