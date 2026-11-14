# KRAOS — sitio web editable

## Archivos
- `index.html`: contenido y estructura de la página.
- `style.css`: colores, tipografías, tamaños y diseño adaptable.
- `script.js`: menú móvil y pequeños comportamientos.
- `images/`: fotografías que puedes sustituir por las imágenes reales de KRAOS.

## Publicar en GitHub Pages
1. Crea un repositorio público llamado `Kraos` en tu cuenta de GitHub.
2. Sube todos los archivos y la carpeta `images`.
3. Abre Settings → Pages.
4. En Build and deployment, elige Deploy from a branch.
5. Selecciona `main` y `/ (root)`, y guarda.
6. Tu web estará disponible en `https://TU-USUARIO.github.io/Kraos/`.

Si reutilizas el repositorio `negocios-ata/Kraos`, la dirección será:
`https://negocios-ata.github.io/Kraos/`

## Cambiar textos
Abre `index.html` y busca el texto que quieras sustituir. No borres las etiquetas HTML que lo rodean.

## Cambiar fotografías
Sube tus fotografías a `images/` con estos nombres:
- `hero.jpg` — imagen principal.
- `accesorios.jpg` — sección de accesorios.
- `objetos.jpg` — sección de objetos.
- `personalizados.jpg` — sección de personalizados.

Puedes usar otros nombres, pero entonces debes cambiar también el atributo `src` correspondiente en `index.html`.

## Cambiar colores y tipografía
Abre `style.css`. Los colores principales están al inicio, en `:root`. La web usa negro, blanco roto y grises como base.

## Antes de publicar
- Sustituye el enlace de Instagram por el perfil real de KRAOS.
- Sustituye `hola@kraos.com` por un correo real o elimina ese enlace si no tienes correo.
- Reemplaza las imágenes de muestra por fotografías propias.
- Revisa todos los textos y datos de contacto.
