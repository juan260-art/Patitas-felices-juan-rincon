# 🐾 Fundación Patitas Felices - Sitio Web

## Descripción del Proyecto

Sitio web estático para la Fundación Patitas Felices, una organización dedicada al rescate, cuidado y reubicación de animales abandonados. El proyecto fue desarrollado utilizando únicamente HTML5 y CSS3 puro, sin JavaScript, cumpliendo con todos los requerimientos de accesibilidad, diseño responsive y componentes interactivos simulados mediante CSS.

### Características Principales

✅ **Diseño Responsive** con 3 breakpoints (Desktop, Tablet, Mobile)  
✅ **Carrusel automático** implementado con CSS animations (@keyframes)  
✅ **Componentes interactivos** simulados (hover effects, transiciones)  
✅ **Formulario de contacto** con validación visual CSS  
✅ **Catálogo de animales** con estados (disponible/adoptado)  
✅ **Navegación sticky** y menú hamburguesa responsive  
✅ **Galería de imágenes** con efectos hover  
✅ **Footer con Flexbox** organizado en secciones

---

## 📁 Estructura del Proyecto

```
patitas-felices/
│
├── index.html           # Página de inicio
├── adopta.html          # Catálogo de animales
├── perfil.html          # Perfil detallado de animal
├── contacto.html        # Formulario de contacto
├── README.md            # Documentación
│
└── css/
    └── styles.css       # Estilos globales
```

---

## 🚀 Instrucciones de Ejecución

### Opción 1: Abrir directamente en el navegador

1. Descarga o clona el repositorio
2. Navega a la carpeta del proyecto
3. Haz doble clic en `index.html`
4. El sitio se abrirá en tu navegador predeterminado

### Opción 2: Usar Visual Studio Code con Live Server

1. Abre Visual Studio Code
2. Instala la extensión "Live Server" de Ritwick Dey
3. Abre la carpeta del proyecto en VS Code
4. Haz clic derecho en `index.html`
5. Selecciona "Open with Live Server"
6. El sitio se abrirá automáticamente en `http://localhost:5500`

### Opción 3: Servidor local con Python

```bash
# Python 3
python -m http.server 8000

# Luego abre en el navegador:
http://localhost:8000
```

---

## 📱 Breakpoints Responsive

El sitio está optimizado para 3 breakpoints principales:

| Dispositivo | Ancho | Breakpoint CSS |
|-------------|-------|----------------|
| **Desktop** | > 768px | Diseño por defecto |
| **Tablet** | 481px - 768px | `@media (max-width: 768px)` |
| **Mobile** | ≤ 480px | `@media (max-width: 480px)` |

---

## 🎨 Paleta de Colores

```css
--primary-color: #FF6B35   /* Naranja (principal) */
--secondary-color: #4ECDC4 /* Turquesa (secundario) */
--accent-color: #FFE66D    /* Amarillo (acentos) */
--dark-color: #2C3E50      /* Azul oscuro (texto) */
--light-color: #F7F9FA     /* Gris claro (fondos) */
--success-color: #27AE60   /* Verde (disponible) */
--error-color: #E74C3C     /* Rojo (errores) */
```

---

## 📄 Páginas del Sitio

### 1. **index.html** - Página de Inicio
- Banner hero con llamado a la acción
- Carrusel automático de 4 imágenes (cambia cada 3 segundos)
- Secciones destacadas (Adopta, Donaciones, Voluntariado, Contacto)
- Visión y Misión lado a lado
- Galería de fotos en grid
- Testimonios de adoptantes

### 2. **adopta.html** - Catálogo de Animales
- Grid responsive con 8 animales
- Tarjetas con información básica
- Estados visuales (Disponible/Adoptado)
- Enlaces a perfiles individuales

### 3. **perfil.html** - Perfil Detallado
- Imagen grande del animal
- Información completa (historia, personalidad, salud)
- Tags con características
- Botón de solicitud de adopción
- Carrusel de animales relacionados

### 4. **contacto.html** - Formulario de Contacto
- Campos obligatorios marcados con asterisco
- Validación visual con clases CSS
- Ejemplos de estados (válido/error)
- Información de contacto directo
- Sección de preguntas frecuentes (FAQ)

---

## 🎭 Componentes CSS Interactivos

### Carrusel Automático
```css
@keyframes carousel-slide {
    0%, 23% { transform: translateX(0); }
    25%, 48% { transform: translateX(-25%); }
    50%, 73% { transform: translateX(-50%); }
    75%, 98% { transform: translateX(-75%); }
}
```
- Cambia automáticamente cada 3 segundos
- 4 slides en loop infinito
- Sin JavaScript requerido

### Menú Hamburguesa Responsive
- Checkbox invisible + label clickeable
- Transiciones CSS para apertura/cierre
- Funcional en tablets y móviles

### Efectos Hover
- Tarjetas de animales se elevan al pasar el mouse
- Imágenes de galería se amplían
- Botones cambian de color y sombra

### Validación de Formulario Visual
- Estados `.valid` y `.error` con clases CSS
- Colores diferenciados (verde/rojo)
- Mensajes de feedback

---

## 🖼️ Capturas de Pantalla

### Desktop - Página de Inicio
![Desktop Home](https://via.placeholder.com/1200x600/FF6B35/FFFFFF?text=Home+Desktop)
*Hero banner con carrusel automático y secciones destacadas*

### Tablet - Catálogo de Animales
![Tablet Adopta](https://via.placeholder.com/768x600/4ECDC4/FFFFFF?text=Adopta+Tablet)
*Grid responsive de animales en adopción*

### Mobile - Formulario de Contacto
![Mobile Contact](https://via.placeholder.com/480x800/FFE66D/2C3E50?text=Contact+Mobile)
*Formulario optimizado para dispositivos móviles*

---

## ✅ Checklist de Requerimientos

### Funcionales
- [x] Página de inicio con banner y slogan
- [x] Carrusel automático (CSS @keyframes)
- [x] Secciones destacadas con botones
- [x] Visión y Misión lado a lado (responsive)
- [x] Galería de imágenes
- [x] Catálogo de 8 animales con estados
- [x] Perfil detallado de animal
- [x] Formulario de contacto completo
- [x] Validación visual CSS
- [x] Footer con Flexbox

### Técnicos
- [x] HTML5 semántico
- [x] CSS3 puro (sin JavaScript)
- [x] 3 breakpoints responsive
- [x] Componentes interactivos CSS
- [x] Accesibilidad (alt tags, labels)
- [x] Código organizado y comentado

### Documentación
- [x] README.md completo
- [x] Instrucciones de ejecución
- [x] Estructura del proyecto
- [x] Descripción de componentes

---

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: Estilos, animaciones, responsive
- **Flexbox**: Layout del footer y navegación
- **CSS Grid**: Galerías y catálogos
- **CSS Animations**: Carrusel y efectos
- **Media Queries**: Diseño responsive

---

## 🎯 Mejores Prácticas Implementadas

1. **Semántica HTML**: Uso correcto de tags (`<header>`, `<nav>`, `<section>`, `<footer>`)
2. **Accesibilidad**: Alt en imágenes, labels en formularios, aria-labels
3. **CSS Variables**: Colores y valores reutilizables
4. **Mobile First**: Optimizado para dispositivos móviles
5. **Performance**: Imágenes optimizadas, CSS minimalista
6. **Mantenibilidad**: Código comentado y organizado

---

## 📝 Notas de Desarrollo

### Carrusel CSS
El carrusel automático se implementó usando:
- `@keyframes` para la animación
- `transform: translateX()` para el desplazamiento
- Timing ajustado para 3 segundos por slide

### Validación de Formulario
Aunque no se usa JavaScript, se simulan estados de validación mediante:
- Clases CSS `.valid` y `.error`
- Pseudoclases `:focus`, `:hover`
- Ejemplos visuales en la página de contacto

### Navegación Responsive
El menú hamburguesa funciona con:
- Checkbox `<input type="checkbox">` invisible
- Label `<label for="menu-toggle">` clickeable
- Transiciones CSS para animación suave

---

## 👥 Créditos

**Desarrollado por**: [Tu Nombre]  
**Para**: Fundación Patitas Felices  
**Fecha**: Noviembre 2025  
**Versión**: 1.0.0

---

## 📧 Contacto

Para preguntas sobre el código o sugerencias:
- Email: dev@patitasfelices.org
- GitHub: [@tu-usuario](https://github.com/tu-usuario)

---

## 📜 Licencia

Este proyecto fue desarrollado como parte de un proyecto académico para la Fundación Patitas Felices.

---

## 🐾 ¡Gracias por visitar!

*"Salvando vidas, creando familias"* - Fundación Patitas Felices