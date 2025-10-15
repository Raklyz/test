# 🎮 Assentium Esports - Sitio Web Oficial

Sitio web completo y profesional para el equipo de esports **Assentium**, diseñado con una estética gamer moderna, minimalista y agresiva.

## 📁 Estructura del Proyecto

```
assentium-website/
│
├── index.html              # Página principal
├── about.html              # Nuestra historia
├── players.html            # Roster de jugadores
├── tournaments.html        # Torneos y competencias
├── donations.html          # Donaciones y patrocinios
├── socials.html            # Redes sociales
├── contact.html            # Formulario de contacto
├── styles.css              # Estilos globales
├── script.js               # JavaScript funcional
└── README.md               # Este archivo
```

## 🎨 Características de Diseño

### Paleta de Colores
- **Primary**: `#ff006e` (Rosa fucsia)
- **Secondary**: `#e91e63` (Rosa intenso)
- **Dark**: `#0a0a0a` (Negro profundo)
- **Gray**: `#2a2a2a` (Gris oscuro)
- **White**: `#ffffff` (Blanco)

### Tipografías
- **Orbitron**: Títulos y elementos destacados (gamer style)
- **Rajdhani**: Texto general y párrafos

### Efectos Visuales
- Animaciones fade-in al hacer scroll
- Efectos hover en todas las tarjetas
- Gradientes personalizados
- Loader inicial con animación
- Transiciones suaves
- Sombras con efecto neón

## 📄 Páginas Incluidas

### 1. **index.html** - Página Principal
- Hero section impactante con frase motivacional
- Estadísticas animadas del equipo
- Secciones destacadas sobre el equipo
- Call-to-action para unirse

### 2. **about.html** - Nuestra Historia
- Timeline visual del recorrido del equipo
- Valores fundamentales de Assentium
- Historia desde la fundación hasta el presente

### 3. **players.html** - Jugadores
- Tarjetas de jugadores con foto, rol y estadísticas
- Información del staff técnico
- Diseño responsive para móviles

### 4. **tournaments.html** - Torneos
- Próximos torneos con detalles
- Historial de torneos completados
- Badges de logros conseguidos

### 5. **donations.html** - Donaciones
- Opciones de donación por niveles
- Información de patrocinios corporativos
- Alternativas de apoyo sin costo

### 6. **socials.html** - Redes Sociales
- Links a todas las plataformas sociales
- Estadísticas de cada red social
- Información de la comunidad

### 7. **contact.html** - Contacto
- Formulario funcional con validación
- Información de contacto adicional
- Sección de preguntas frecuentes

## ⚙️ Funcionalidades JavaScript

### Loader Inicial
- Animación de carga al entrar al sitio
- Se oculta automáticamente después de 1.5s

### Navegación Responsive
- Menú hamburguesa para móviles
- Detección automática de página activa
- Animación de scroll en navbar

### Animaciones en Scroll
- Elementos fade-in cuando entran en viewport
- Números animados en estadísticas
- Transiciones suaves

### Formulario de Contacto
- Validación de campos en tiempo real
- Notificaciones de éxito/error
- Simulación de envío

## 🚀 Instalación y Uso

### Opción 1: Servidor Local Simple
```bash
# Con Python 3
python -m http.server 8000

# Con PHP
php -S localhost:8000

# Con Node.js (http-server)
npx http-server
```

### Opción 2: Abrir Directamente
Simplemente abre `index.html` en tu navegador favorito.

## 📱 Responsive Design

El sitio está completamente optimizado para:
- 💻 Escritorio (1920px y superior)
- 💻 Laptop (1366px - 1920px)
- 📱 Tablet (768px - 1366px)
- 📱 Móvil (320px - 768px)

## 🔧 Personalización

### Cambiar Colores
Edita las variables CSS en `styles.css`:
```css
:root {
    --primary: #ff006e;
    --secondary: #e91e63;
    /* ... más variables */
}
```

### Agregar Jugadores
Duplica el bloque `.player-card` en `players.html` y modifica:
- Nombre del jugador
- Rol y juego
- Estadísticas

### Modificar Logo
Reemplaza el texto "ASSENTIUM" en la clase `.logo` con:
```html
<img src="tu-logo.png" alt="Assentium">
```

### Enlaces de Redes Sociales
Actualiza los `href="#"` en todas las páginas con tus URLs reales:
```html
<a href="https://discord.gg/tu-server">Discord</a>
```

## 🎯 Próximas Mejoras Sugeridas

- [ ] Integrar backend real para el formulario de contacto
- [ ] Conectar con API de Twitch para mostrar si están en vivo
- [ ] Sistema de noticias/blog
- [ ] Galería de fotos del equipo
- [ ] Tienda de merchandise
- [ ] Sistema de registro de usuarios
- [ ] Integración con plataformas de pago para donaciones

## 📝 Notas Importantes

- **Imágenes**: Las imágenes de jugadores usan placeholders (👤). Reemplázalas con fotos reales.
- **Enlaces**: Todos los enlaces externos están con `href="#"`. Actualízalos con URLs reales.
- **Formulario**: El formulario es simulado. Para producción, necesitas un backend.
- **Emails**: Los emails (contact@assentium.gg) son ejemplos. Usa tus emails reales.

## 🌟 Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: Estilos modernos con variables, grid y flexbox
- **JavaScript ES6+**: Funcionalidad dinámica
- **Google Fonts**: Tipografías Orbitron y Rajdhani

## 📄 Licencia

Este proyecto ha sido creado para Assentium Esports. Todos los derechos reservados.

## 🤝 Soporte

Para preguntas o problemas, contacta a través del formulario de contacto o envía un email a contact@assentium.gg

---

**Desarrollado con 💜 para Assentium Esports**

**#AssentiumGG #GamingExcellence**