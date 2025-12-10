🎨 Creando Diversidad Digital:

Proyecto web desarrollado como práctica del módulo de Maquetación, siguiendo las pautas de Adalab. Incluye un layout completo con cabecera fija, hero responsive y footer, utilizando HTML, Sass, Flexbox y Vite.

🚀 Tecnologías utilizadas:

HTML5
Sass / SCSS (arquitectura modular)
CSS Flexbox
Vite como servidor y empaquetador
JavaScript básico para estructura
Responsive design con breakpoints mobile-first

📁 Estructura del proyecto:
/
├── src/
│   ├── html/
│   ├── images/
│   ├── js/
│   └── scss/
│       ├── core/          # variables, reset
│       ├── components/    # estilos de botones, enlaces, código, etc.
│       ├── layout/        # header, footer, page layout
│       └── pages/         # hero, estilos de index
├── .gitignore
├── package.json
├── vite.config.js
└── README.md

📸 Descripción del proyecto:

El objetivo es construir una landing sencilla y totalmente responsive que represente el lema:
"Creando Diversidad Digital"

Incluye:
✔ Header fijo
Con logo de Adalab y menú de navegación.
Se adapta según dispositivo (mobile, tablet, desktop).
Evita superposición gracias a margin-top dinámico según la altura del header.

✔ Hero section
Imagen a pantalla completa
Título principal
Ocupa 100vh ajustado al header
Uso de calc() y breakpoints Sass

✔ Footer
Con datos básicos de copyright y estructura responsive.

🎯 Objetivos de aprendizaje:

Dominar Sass modularizado
Utilizar variables, mixins y media queries
Practicar layout responsive con Flexbox
Manejar cabecera fija sin superposición
Integrar assets, imágenes y tipografías
Configurar proyectos con Vite

🛠️ Instalación y uso:

1️⃣ Clonar el repositorio
git clone https://github.com/tu-usuario/tu-repo.git

2️⃣ Instalar dependencias
npm install

3️⃣ Ejecutar el servidor de desarrollo
npm run dev

4️⃣ Abrir el navegador

Vite abrirá automáticamente:

http://localhost:5173

📐 Responsive Design:

El proyecto sigue una estrategia mobile-first, con estos breakpoints:

$breakpoint-tablet: 768px;
$breakpoint-desktop: 1200px;

🧩 Personalización:

Puedes modificar variables desde:

src/scss/core/_variables.scss


Incluye:

paleta de colores

tipografías

tamaños de header y footer

breakpoints

📬 Contacto

Proyecto realizado por Michelle Pacheco como parte de su formación Frontend.
Cualquier sugerencia o mejora es bienvenida. 💙
