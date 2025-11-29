# GamaTok - Landing Page

Landing page profesional para promover servicios de lives de TikTok para tiendas de Gamarra.

## 🎨 Colores de TikTok

La landing usa los colores oficiales de TikTok:
- **Cyan/Turquesa**: `#00f2ea` (color principal)
- **Rosa/Magenta**: `#fe2c55` (color secundario)
- **Negro**: `#000000` y `#161823` (fondos oscuros)

## 📱 Compartir en WhatsApp y Redes Sociales

Para que tu landing se vea profesional cuando la compartas en WhatsApp, sigue estos pasos:

### Paso 1: Crear la imagen de vista previa

1. Abre el archivo `og-image.html` en tu navegador
2. Presiona `F11` para pantalla completa
3. Toma un screenshot del recuadro de colores (debe ser 1200x630 píxeles)
4. Guarda la imagen como `og-image.jpg`

### Paso 2: Subir la imagen a internet

Opciones para subir tu imagen:

**Opción A - Imgur (Recomendado):**
1. Ve a [imgur.com](https://imgur.com)
2. Haz clic en "New post"
3. Sube tu imagen `og-image.jpg`
4. Copia el link directo de la imagen (clic derecho > "Copy image address")

**Opción B - ImgBB:**
1. Ve a [imgbb.com](https://imgbb.com)
2. Sube tu imagen
3. Copia el link directo

### Paso 3: Actualizar el HTML

1. Abre `index.html`
2. Busca la línea que dice:
   ```html
   <meta property="og:image" content="https://i.imgur.com/your-image.jpg">
   ```
3. Reemplaza `https://i.imgur.com/your-image.jpg` con tu link
4. También actualiza esta línea:
   ```html
   <meta name="twitter:image" content="https://i.imgur.com/your-image.jpg">
   ```

### Paso 4: Probar la vista previa

1. Sube tu landing a un servidor web (GitHub Pages, Netlify, etc.)
2. Prueba cómo se ve en WhatsApp:
   - Ve a [developers.facebook.com/tools/debug](https://developers.facebook.com/tools/debug/)
   - Pega la URL de tu landing
   - Haz clic en "Scrape Again" para refrescar
   - Comparte el link en WhatsApp para ver cómo se ve

## 📞 Configuración de WhatsApp

El número de WhatsApp está configurado como: **+51 936 210 916**

Si quieres cambiarlo:
1. Busca en `index.html` todas las apariciones de `51936210916`
2. Reemplázalo por tu número (formato: código de país + número sin espacios)

## 🚀 Archivos del proyecto

- `index.html` - Página principal
- `style.css` - Estilos y colores de TikTok
- `script.js` - Funcionalidades interactivas
- `og-image.html` - Generador de imagen para compartir
- `README.md` - Este archivo

## 🎯 Características

- ✅ Diseño responsive (mobile, tablet, desktop)
- ✅ Colores oficiales de TikTok
- ✅ Meta tags para compartir en redes sociales
- ✅ Integración directa con WhatsApp
- ✅ Animaciones suaves
- ✅ FAQ con acordeón
- ✅ Plan único destacado
- ✅ Footer minimalista

## 💡 Personalización

### Cambiar el título principal
Edita la línea 68-70 en `index.html`:
```html
<h1 class="hero-title">
    <span class="gradient-text">Tus lives de TikTok</span><br>
    ahora serán diferentes
</h1>
```

### Cambiar el precio
Edita la línea 280 en `index.html`:
```html
<span class="amount">299</span>
```

### Cambiar beneficios del plan
Edita las líneas 285-293 en `index.html` dentro de `<ul class="plan-features">`

## 📊 SEO

La landing incluye:
- Meta description optimizada
- Open Graph tags para redes sociales
- Twitter Card tags
- Keywords relevantes
- Estructura semántica HTML5

## 🌐 Hosting recomendado

Puedes hostear gratis en:
- **GitHub Pages** (recomendado)
- **Netlify**
- **Vercel**
- **Render**

## 📝 Licencia

Proyecto desarrollado para GamaTok - Todos los derechos reservados © 2025