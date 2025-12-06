# 🏗️ Constructora Pro - Website

Página web profesional para empresa de construcción y arquitectura. Diseño moderno, responsivo y completamente personalizable.

## 🌐 Ver en Vivo

👉 **[Ver Sitio Web](https://vlkair.github.io/PaginaWeb-cliente/)**

---

## 📋 Características

- ✅ Diseño moderno y profesional
- ✅ 100% Responsive (móvil, tablet, desktop)
- ✅ Animaciones suaves y atractivas
- ✅ Navegación fluida con scroll suave
- ✅ Formulario de contacto funcional
- ✅ Secciones completas: Hero, Servicios, Proyectos, Nosotros, Contacto
- ✅ Optimizado para SEO
- ✅ Carga rápida y ligero
- ✅ Sin dependencias externas (CSS y JS puros)

## 🚀 Estructura del Proyecto

```
PaginaWeb-cliente/
├── index.html          # Página principal
├── css/
│   └── styles.css      # Estilos personalizados
├── js/
│   └── main.js         # JavaScript funcional
├── images/             # Imágenes del sitio
├── assets/             # Recursos adicionales
└── README.md           # Documentación
```

## 🎨 Personalización

### 1. Colores
Edita las variables CSS en `css/styles.css`:

```css
:root {
    --primary-color: #ff6b35;      /* Color principal (naranja) */
    --secondary-color: #004e89;    /* Color secundario (azul) */
    --dark-color: #1a1a2e;         /* Color oscuro */
    --light-color: #f5f5f5;        /* Color claro */
}
```

### 2. Contenido
Edita el archivo `index.html`:

- **Logo y nombre**: Busca `Constructora<span>Pro</span>` (línea ~20)
- **Título Hero**: Modifica `<h1>Construimos Tus Sueños</h1>` (línea ~43)
- **Servicios**: Edita la sección `.services-grid` (línea ~57)
- **Información de contacto**: Actualiza la sección `.contact-info` (línea ~163)

### 3. Imágenes
Reemplaza las URLs de Unsplash en la sección de proyectos con tus propias imágenes:

```html
<!-- Busca esta línea y reemplaza la URL -->
<img src="images/tu-imagen.jpg" alt="Descripción" class="project-image">
```

Guarda tus imágenes en la carpeta `images/`.

### 4. Información de Contacto
Actualiza en `index.html`:

```html
<!-- Dirección -->
<p>Tu Dirección Aquí</p>

<!-- Teléfono -->
<p>+1 (XXX) XXX-XXXX</p>

<!-- Email -->
<p>tuemail@empresa.com</p>
```

## 📱 Funcionalidades JavaScript

El archivo `js/main.js` incluye:

- Menú móvil responsive (hamburguesa)
- Navegación suave entre secciones
- Header que cambia al hacer scroll
- Animaciones al aparecer elementos
- Contador animado para estadísticas
- Formulario de contacto con validación
- Botón "scroll to top"
- Sistema de alertas

## 🚀 Publicar en GitHub Pages

**📖 [Ver Guía Completa de GitHub Pages](GITHUB-PAGES-SETUP.md)**

### Pasos rápidos:
1. Ve a **Settings > Pages** en tu repositorio
2. Selecciona branch `main` y carpeta `/ (root)`
3. Guarda y espera 1-2 minutos
4. Tu sitio estará en: `https://vlkair.github.io/PaginaWeb-cliente/`

### Para actualizar tu sitio:
```bash
git add .
git commit -m "Descripción de cambios"
git push origin main
```

## 🌐 Desarrollo Local

### Método 1: Abrir Directamente
1. Abre el archivo `index.html` en tu navegador
2. La página se cargará lista para usar

### Método 2: VS Code Live Server (Recomendado)
1. Instala la extensión "Live Server" en VS Code
2. Click derecho en `index.html`
3. Selecciona "Open with Live Server"

### Método 3: Servidor Local
Si tienes Python:
```bash
python -m http.server 8000
# Abre: http://localhost:8000
```

## 🎯 Secciones de la Página

1. **Header/Navegación** - Menú fijo con logo y enlaces
2. **Hero** - Sección principal con llamado a la acción
3. **Servicios** - 6 tarjetas de servicios ofrecidos
4. **Proyectos** - Galería de proyectos con overlay
5. **Sobre Nosotros** - Información de la empresa + estadísticas
6. **Contacto** - Formulario + información de contacto
7. **Footer** - Enlaces, redes sociales y newsletter

## 🛠️ Tecnologías Utilizadas

- **HTML5** - Estructura semántica
- **CSS3** - Estilos modernos con Flexbox y Grid
- **JavaScript Vanilla** - Sin frameworks, código puro
- **Font System** - Fuentes del sistema para carga rápida

## 📝 Próximas Mejoras Sugeridas

- [ ] Agregar galería de imágenes con lightbox
- [ ] Integrar Google Maps en contacto
- [ ] Conectar formulario con backend/email
- [ ] Agregar testimonios de clientes
- [ ] Blog de noticias y proyectos
- [ ] Versión en múltiples idiomas
- [ ] Chat en vivo
- [ ] Calculadora de cotización

## 🔧 Requisitos

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Editor de código (VS Code, Sublime, etc.)
- Conocimientos básicos de HTML/CSS/JS para personalizar

## 📄 Licencia

Este proyecto está diseñado para uso personal y comercial. Puedes modificarlo según tus necesidades.

## 🤝 Soporte

Para soporte o preguntas sobre personalización, consulta la documentación en los comentarios del código.

## 🎨 Paleta de Colores Actual

- **Naranja**: `#ff6b35` - Color principal, botones, acentos
- **Azul**: `#004e89` - Color secundario, textos importantes
- **Oscuro**: `#1a1a2e` - Textos, footer
- **Claro**: `#f5f5f5` - Fondos, secciones alternadas
- **Gris**: `#666` - Textos secundarios

## 📸 Capturas de Pantalla

La página incluye:
- Hero fullscreen con gradiente
- Cards de servicios con hover effects
- Galería de proyectos con overlay
- Formulario de contacto estilizado
- Footer completo con múltiples secciones

---

**Desarrollado con ❤️ para Constructora Pro**

¿Necesitas ayuda? Revisa los comentarios en el código para guías detalladas.
