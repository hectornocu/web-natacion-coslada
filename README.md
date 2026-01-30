# 🏊 Club Natación Coslada - Web Oficial

![Estado del Proyecto](https://img.shields.io/badge/Estado-En%20Desarrollo-green)
![Tecnología](https://img.shields.io/badge/HTML5-TailwindCSS-blue)

Bienvenido al repositorio oficial del sitio web del **Club Natación Coslada**. Este proyecto es una solución web moderna, responsive y optimizada para la gestión de la información del club, horarios y competiciones.

🔗 **[Ver la Web en Vivo](https://hectornocu.github.io/web-natacion-coslada/)**

## 🚀 Características Principales

* **Diseño Totalmente Responsive:** Adaptado a móviles, tablets y escritorio (Mobile-First approach).
* **Base de Datos Simulada (JSON):** Implementación de arquitectura cliente-servidor simulada. La página de competiciones consume datos dinámicamente desde un archivo `datos.json` utilizando la **Fetch API** y JavaScript asíncrono (`async/await`).
* **Estilado Moderno:** Uso de **Tailwind CSS** (v3.4) vía CDN para un diseño rápido, limpio y mantenible.
* **Navegación Intuitiva:** Menú responsive tipo "hamburguesa" para dispositivos móviles.
* **Integraciones:**
    * Mapas interactivos embebidos (Google Maps) con ajuste dinámico de altura.
    * Fuentes personalizadas (Google Fonts: Lexend).
    * Iconografía vectorial (Google Material Symbols).

## 🛠️ Tecnologías Utilizadas

* **HTML5 Semántico:** Estructura clara y accesible (`header`, `main`, `section`, `footer`).
* **CSS Framework:** Tailwind CSS.
* **JavaScript (Vanilla ES6+):**
    * Manipulación del DOM.
    * Consumo de datos JSON.
    * Eventos de interacción (Menú móvil).
* **Control de Versiones:** Git & GitHub.
* **Despliegue (Hosting):** GitHub Pages.

## 📂 Estructura del Proyecto

```text
/
├── index.html          # Página de Inicio (Landing Page)
├── historia.html       # Historia y Timeline del club
├── competiciones.html  # Carga dinámica de eventos desde JSON
├── calendario.html     # Calendario visual generado con JS
├── contacto.html       # Formulario y Mapa de ubicación
├── inscripcion.html    # Precios y planes
├── datos.json          # "Base de Datos" de las competiciones
├── logo.png            # Logotipo del club
├── equipo.jpg          # Fotografía del equipo
└── README.md           # Documentación del proyecto


💻 Instalación y Uso Local
Este es un proyecto estático, por lo que no requiere instalación de dependencias de Node.js ni bases de datos complejas.

Clonar el repositorio:

Bash
git clone [https://github.com/hectornocu/web-natacion-coslada.git](https://github.com/hectornocu/web-natacion-coslada.git)
Abrir el proyecto: Navega a la carpeta y abre el archivo index.html en tu navegador.

Nota importante: Para que la carga del archivo datos.json funcione correctamente en local, es recomendable usar un servidor local (como Live Server en VS Code) debido a las políticas de seguridad CORS de los navegadores.

🔮 Futuras Mejoras (Roadmap)
[ ] Migración de datos.json a una base de datos real (Firebase/Supabase).

[ ] Área privada para socios (Login).

[ ] Panel de administración para subir nuevas noticias sin tocar código.

👨‍💻 Autor
Desarrollado por Héctor - Ingeniero de Software en formación.

© 2026 Club Natación Coslada.
