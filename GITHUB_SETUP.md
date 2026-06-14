# 📚 Guía Completa: Publicar en GitHub Pages

Esta guía te ayudará a publicar tu sitio web de Bibliografía en GitHub de forma rápida y sencilla.

## 📋 Requisitos Previos

✅ Cuenta de GitHub (gratuita en www.github.com)
✅ Git instalado en tu computadora
✅ Todos los archivos HTML, imágenes y audio

## 🚀 Pasos para Publicar

### PASO 1: Crear un Repositorio en GitHub

1. Inicia sesión en [GitHub](https://github.com)
2. Haz clic en el icono `+` en la esquina superior derecha
3. Selecciona "New repository"
4. Nombre del repositorio: `bibliografia` (o el que prefieras)
5. Descripción: "Sitio web de bibliografía minimalista y responsivo"
6. Selecciona "Public"
7. NO marques "Add a README file" (ya lo tenemos)
8. Haz clic en "Create repository"

### PASO 2: Preparar tus Archivos Locales

1. Crea una carpeta en tu computadora:
   ```
   mkdir mi-bibliografia
   cd mi-bibliografia
   ```

2. Coloca TODOS estos archivos en la carpeta:
   - index.html
   - page1.html
   - page2.html
   - page3.html
   - page4.html
   - page5.html
   - page6.html
   - page7.html
   - page8.html
   - page9.html
   - README.md
   - GITHUB_SETUP.md
   - kelvin.aac
   - Todas las imágenes (.jpg, .png, .jpeg)

### PASO 3: Inicializar Git Localmente

Abre la terminal/CMD en tu carpeta y escribe:

```bash
git init
git add .
git commit -m "Initial commit: Bibliografía website"
```

### PASO 4: Conectar con GitHub

1. Copia el URL de tu repositorio recién creado
2. En la terminal, escribe:

```bash
git remote add origin https://github.com/TUUSUARIO/bibliografia.git
git branch -M main
git push -u origin main
```

Reemplaza:
- `TUUSUARIO` con tu nombre de usuario de GitHub
- `bibliografia` con el nombre que le diste al repositorio

### PASO 5: Habilitar GitHub Pages

1. Ve a tu repositorio en GitHub
2. Haz clic en "Settings" (⚙️)
3. En el menú izquierdo, busca "Pages"
4. Bajo "Source", selecciona la rama "main"
5. Haz clic en "Save"
6. Espera unos minutos (GitHub procesará los cambios)

### PASO 6: Acceder a tu Sitio

Tu sitio estará disponible en:
```
https://TUUSUARIO.github.io/bibliografia
```

O si lo configuraste como repositorio por defecto:
```
https://TUUSUARIO.github.io
```

## 🔄 Cómo Actualizar tu Sitio

Si necesitas hacer cambios:

```bash
# Hacer cambios en tus archivos...

# Luego, en la terminal:
git add .
git commit -m "Descripción de los cambios"
git push
```

Los cambios se verán en tu sitio en unos minutos.

## 🐛 Solucionar Problemas Comunes

### Las imágenes no cargan
- Verifica que los nombres de archivo sean exactos (mayúsculas/minúsculas)
- Asegúrate de que las imágenes están en el mismo directorio que los HTML
- Intenta usar rutas relativas: `./imagen.jpg` en lugar de `imagen.jpg`

### La música no se reproduce
- Verifica que `kelvin.aac` está en el repositorio
- Asegúrate de que el navegador permite autoplay de audio
- Algunos navegadores requieren interacción del usuario primero

### El sitio no aparece
- Espera 10-15 minutos después de hacer push
- Ve a Settings > Pages y verifica que esté configurado correctamente
- Busca mensajes de error en la sección "Deployments"

### Los enlaces no funcionan
- Verifica que todas las URLs externas son correctas
- Asegúrate de usar `https://` en lugar de `http://`
- Prueba los enlaces en tu navegador directamente

## 📱 Verificar en Diferentes Dispositivos

Usa estas herramientas para verificar que tu sitio se ve bien:

### Online:
- [Google Mobile-Friendly Test](https://search.google.com/test/mobile-friendly)
- [Responsively App](https://responsively.app/)
- Chrome DevTools (F12 → Toggle device toolbar)

### Móvil:
- Abre tu URL en tu teléfono
- Prueba en orientación horizontal y vertical
- Verifica que todos los botones son clickeables

## 🎯 Checklist de Publicación

Antes de publicar, verifica:

- [ ] Todos los archivos HTML están en la carpeta
- [ ] Todas las imágenes tienen los nombres correctos
- [ ] El archivo `kelvin.aac` está presente
- [ ] El archivo `README.md` está presente
- [ ] El archivo `index.html` existe
- [ ] Todos los enlaces internos funcionan
- [ ] El sitio se ve bien en móvil
- [ ] La música se reproduce
- [ ] Las imágenes de fondo cargan correctamente

## 🎨 Personalización Avanzada

### Cambiar el nombre del repositorio
```bash
git remote set-url origin https://github.com/TUUSUARIO/nuevoNombre.git
```

### Agregar un dominio personalizado
1. Compra un dominio (.com, .es, etc.)
2. Ve a Settings > Pages
3. Bajo "Custom domain", ingresa tu dominio
4. Configura el DNS según las instrucciones

### Usar un archivo custom 404
Crea un archivo `404.html` en tu repositorio para personalizar la página de error.

## 📚 Recursos Útiles

- [GitHub Pages Documentación](https://docs.github.com/es/pages)
- [Git Guía Completa](https://git-scm.com/book/es/v2)
- [HTML5 Referencia](https://developer.mozilla.org/es/docs/Web/HTML)
- [CSS3 Guía](https://developer.mozilla.org/es/docs/Web/CSS)

## 💬 Obtener Ayuda

Si tienes problemas:
1. Revisa la sección de Issues en tu repositorio
2. Consulta la documentación de GitHub Pages
3. Busca en Stack Overflow con tu error específico

## ✅ ¡Listo!

Tu sitio de bibliografía está online y accesible para el mundo. Comparte tu URL con amigos y familia. 🎉

---

**Última actualización:** Junio 2026
**Estado:** Funcional y listo para producción
