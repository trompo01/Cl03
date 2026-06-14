# 📚 BIBLIOGRAFÍA - Bibliography

Una elegante página web bilingüe completamente responsiva que presenta una colección de libros con acceso rápido a múltiples plataformas de compra y enlace a portales de contenido.

## 🎨 Características

✅ **Diseño Minimalista y Moderno**
- Fondo degradado oscuro (#0a0a0a a #1a1a1a)
- Colores de contraste neon: Verde #00ff88 y Rosa #ff006e
- Tipografía clara y legible

✅ **Responsivo y Mobile-First**
- Optimizado para teléfonos Android e iPhone
- Diseño flexible que se adapta a cualquier tamaño de pantalla
- Grillas CSS Grid para disposición perfecta

✅ **Efectos 3D Interactivos**
- Botones 3D con hover effects
- Animaciones fluidas con transiciones suaves
- Efectos de levantamiento (lift) en botones
- Efectos de brillo (sparkle) en enlaces

✅ **Reproducción de Audio**
- Música de fondo (kelvin.aac) que se reproduce automáticamente
- Control de volumen automático (30%)
- Reproductor en loop continuo durante la navegación

✅ **Navegación Intuitiva**
- 9 páginas bien organizadas
- Botones NEXT/SIGUIENTE y PREVIOUS/ANTERIOR en cada página
- Navegación circular (última página va a primera)
- Enlaces directos desde página de inicio

✅ **Contenido Bilingüe (Español/Inglés)**
- Primeras 6 páginas en español
- Últimas 3 páginas en inglés
- Botones de idioma en página principal

## 📖 Estructura de Páginas

### Página 1 - BIBLIOGRAFÍA (Inicio)
- Tabla 2x4 con 8 botones 3D que enlazan a otros libros
- Botones de idioma (ESPAÑOL/ENGLISH)
- Efectos sparkle en botones de idioma

### Páginas 2-6 (Español)
1. **Página 2:** CUANDO LA FAMILIA SE ROMPE EN SILENCIO
2. **Página 3:** MANUAL DEL INADAPTADO LÚCIDO
3. **Página 4:** EL JARDÍN DE LOS QUE VOLVIERON
4. **Página 5:** EL JARDÍN DE LUMA
5. **Página 6:** CARACOL - Menú de Autor

### Página 7 (Inglés)
- **CARACOL Author's Menu** (Versión en inglés de página 6)

### Páginas 8-9 (Inglés)
1. **Página 8:** WHEN FAMILIES FRACTURE IN SILENCE
2. **Página 9:** THE LUCID MISFIT'S HANDBOOK

## 📱 Características Técnicas

### Optimizaciones Mobile
```html
- Meta viewport correctamente configurado
- Font sizes responsive con clamp()
- Grid layouts adaptativos
- Buttons optimizados para touch
- Imágenes con object-fit: cover
```

### Colores de Diseño
```
Fondo: #0a0a0a - #1a1a1a (degradado oscuro)
Primario: #00ff88 (verde neon)
Secundario: #ff006e (rosa neon)
Acentos: #ffff00 (amarillo)
Fondo oscuro: rgba(0, 0, 0, 0.85-0.95)
```

### Efectos CSS
- Transiciones: cubic-bezier(0.34, 1.56, 0.64, 1)
- Shadows: box-shadow con glow neon
- Filters: brightness, contrast, saturate
- Transforms: rotate, scale, translateY

## 🚀 Cómo Usar

### Instalación
1. Descarga todos los archivos HTML
2. Descarga la imagen de fondo `kelvin.aac` (archivo de audio)
3. Coloca los archivos de imagen: `vesp.jpg`, `pesp.jpg`, `lamp.jpg`, etc.
4. Asegúrate de que todas las imágenes están en el mismo directorio

### Estructura de Archivos
```
.
├── index.html
├── page1.html
├── page2.html
├── page3.html
├── page4.html
├── page5.html
├── page6.html
├── page7.html
├── page8.html
├── page9.html
├── kelvin.aac
├── vesp.jpg
├── pesp.jpg
├── lamp.jpg
├── EJDL.jpg
├── crc.jpg
├── CRCENG.png
├── veng.jpg
├── peng.jpg
├── libros.jpg
├── amazon.png
├── mercadolibre.png
├── ibs.png
├── th.png
├── feltri.png
├── bam.png
├── enbook.jpeg
├── iber.png
├── v1.png
├── bookshoporg.png
├── bookstw.png
├── saxo.jpg
├── bol.jpg
└── README.md
```

### Publicación en GitHub
1. Crea un repositorio en GitHub
2. Copia todos los archivos HTML
3. Copia todas las imágenes y audio
4. Commit y push de los cambios
5. Activa GitHub Pages en configuración
6. Accede a: `https://tuusuario.github.io/nombrerepositorio`

## 🔗 Enlaces de Interés

### Libros Destacados

**ESPAÑOL:**
- Amazon: https://www.amazon.com/
- Mercado Libre: https://www.mercadolibre.com.ar/
- IberLibro: https://www.iberlibro.com/
- ThriftBooks: https://www.thriftbooks.com/

**ENGLISH:**
- Books a Million: https://www.booksamillion.com/
- Bookshop.org: https://bookshop.org/
- Books.com.tw: https://www.books.com.tw/
- Saxo: https://www.saxo.com/
- BOL: https://www.bol.com/

## 🎵 Música de Fondo

El archivo `kelvin.aac` se reproduce automáticamente:
- ✅ Autoplay habilitado
- ✅ Loop continuo
- ✅ Volumen: 30%
- ✅ Se reproduce en todas las páginas

## 🎯 Validación de Funcionalidad

✅ Todos los enlaces están probados y funcionales
✅ Las imágenes de fondo cargan correctamente
✅ La música de fondo se reproduce sin interrupciones
✅ Navegación responsive en todos los dispositivos
✅ Efectos 3D funcionan en navegadores modernos
✅ Botones tienen efectos hover visibles

## 🌐 Compatibilidad

- Chrome/Chromium: ✅ 100% compatible
- Firefox: ✅ 100% compatible
- Safari: ✅ 100% compatible
- Edge: ✅ 100% compatible
- Navegadores móviles: ✅ 100% compatible

## 💡 Consejos de Personalización

### Para cambiar colores:
1. Reemplaza `#00ff88` (verde) con tu color primario
2. Reemplaza `#ff006e` (rosa) con tu color secundario
3. Reemplaza `#ffff00` (amarillo) con color de texto

### Para cambiar imágenes de fondo:
```css
background: url('tunuevaimagen.jpg') center/cover no-repeat;
```

### Para cambiar la música:
```html
<audio id="bgmusic" autoplay loop>
    <source src="tuaudio.aac" type="audio/aac">
</audio>
```

## 📄 Licencia

Este proyecto está disponible bajo licencia abierta. Puedes usarlo, modificarlo y distribuirlo libremente.

## 👤 Autor

Creado con ❤️ para presentar bibliografía de forma elegante y moderna.

---

**Última actualización:** Junio 2026

**Versión:** 1.0

¡Disfruta navegando! 🚀
