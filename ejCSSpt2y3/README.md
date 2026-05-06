# Ejercicios CSS - ejCSSpt2y3

Este directorio contiene tres ejercicios prácticos de CSS y HTML. Cada ejercicio está en su propia carpeta separada.

---

## 📁 Estructura de Carpetas

```
ejCSSpt2y3/
├── ejercicio1/       # Centrado con Flexbox
├── ejercicio2/       # Tarjeta de usuario
├── ejercicio3/       # Página Instagram responsive
└── README.md        # Este archivo
```

---

## 🎯 Ejercicio 1: Centrado con Flexbox

**Archivo:** `ejercicio1/index.html` y `ejercicio1/style.css`

**Descripción:** Crea un archivo HTML que demuestra cómo centrar un div tanto horizontal como verticalmente usando `display: flex`.

**Características:**
- Contenedor padre con `display: flex`
- Propiedades `justify-content: center` y `align-items: center`
- Altura de viewport (`100vh`)
- Diseño moderno con gradiente de fondo
- Tarjeta con sombra y bordes redondeados

**Cómo abrir:** Abre `ejercicio1/index.html` en tu navegador.

---

## 👤 Ejercicio 2: Tarjeta de Usuario

**Archivo:** `ejercicio2/index.html` y `ejercicio2/style.css`

**Descripción:** Crea una tarjeta de usuario estilo perfil con los siguientes elementos:
- Imagen de usuario con estilo circular
- Banner superior con degradado
- Nombre del usuario y ciudad
- Estadísticas: seguidores, likes y cantidad de fotos
- Diseño responsive

**Características:**
- Avatar circular con borde y sombra
- Banner separado del contenido
- Estadísticas en grid
- Botones de acción
- Responsive design con media queries

**Cómo abrir:** Abre `ejercicio2/index.html` en tu navegador.

---

## 📸 Ejercicio 3: Página de Perfil de Instagram

**Archivo:** `ejercicio3/index.html`, `ejercicio3/style.css` y `ejercicio3/script.js`

**Descripción:** Implementa una página de perfil de Instagram completamente responsive usando **mobile first**. Incluye todas las características principales de Instagram.

**Características:**

### Estructura
- ✅ Header sticky con logo y iconos
- ✅ Sección de perfil con foto, nombre y seguir
- ✅ Biografía del usuario
- ✅ Estadísticas (publicaciones, seguidores, siguiendo)
- ✅ Sección de historias (stories)
- ✅ Tabs de navegación
- ✅ Galería de publicaciones en grid
- ✅ Footer de navegación en mobile

### Diseño Responsive (Mobile First)
- **Mobile** (< 768px): 3 columnas en galería, footer fijo
- **Tablet** (768px - 1024px): 4 columnas, cambios en espacios
- **Desktop** (1024px+): Layout optimizado para pantalla grande

### Interactividad
- Cambio de tabs de navegación
- Botón "Seguir" interactivo
- Efecto hover en publicaciones (overlay con likes y comentarios)
- Scroll suave en historias
- Animaciones de carga en posts
- Efectos de touch/click en mobile

**Variables CSS personalizables:**
```css
--primary-color: #E1306C        /* Rosa de Instagram */
--secondary-color: #405DE6      /* Azul de Instagram */
--background: #FAFAFA           /* Fondo */
--border-color: #EFEFEF         /* Bordes */
--text-dark: #262626            /* Texto oscuro */
--text-light: #8E8E8E           /* Texto claro */
```

**Cómo abrir:** Abre `ejercicio3/index.html` en tu navegador.

---

## 📝 Notas Importantes

1. **Mobile First:** Todos los estilos base están diseñados para móvil. Las media queries agregan cambios para tablets y desktop.

2. **Imágenes Placeholder:** Los ejercicios utilizan imágenes placeholder de `via.placeholder.com`. Puedes reemplazarlas con URLs reales.

3. **Funcionalidad JavaScript:** El ejercicio 3 incluye script interactivo para:
   - Cambio de tabs
   - Seguir/dejar de seguir
   - Navegación en footer
   - Scroll suave en historias

4. **Compatibilidad:** Funciona en todos los navegadores modernos (Chrome, Firefox, Safari, Edge).

---

## 🚀 Cómo Usar

1. Abre cualquiera de los archivos `index.html` en tu navegador favorito
2. En mobile/tablet: Prueba la responsividad redimensionando la ventana
3. En desktop: Disfruta de la versión completa

---

## 💡 Conceptos Aprendidos

- ✅ Flexbox para centrado y layouts
- ✅ CSS Grid para galerías
- ✅ Media queries para responsive design
- ✅ Mobile first approach
- ✅ Pseudo-clases y pseudo-elementos
- ✅ Transiciones y animaciones
- ✅ Variables CSS (custom properties)
- ✅ Diseño moderno y accesible

---

## ✏️ Posibles Mejoras

- Agregar más animaciones
- Implementar filtros de fotos
- Agregar formulario de comentarios
- Integrar con API real de Instagram
- Modo oscuro
- Diferentes temas de colores

---

**Autor:** Ejercicios de CSS y HTML
**Fecha:** 2026
