# Instrucciones para Agregar Imágenes a la Galería

## Estructura Actual

La galería está configurada en [index.html](index.html#L1130) y ya tiene **6 espacios listos** para imágenes de tus trabajos.

## Cómo Agregar Tus Fotos

### Paso 1: Preparar las Imágenes
Prepara tus fotos en formato **JPG** o **PNG** con tamaños recomendados:
- **Ancho mínimo**: 400px
- **Ancho ideal**: 600-800px
- **Formato**: Cuadrado o rectángulo (la galería se ajustará automáticamente)

### Paso 2: Guardar las Fotos
Coloca tus imágenes en la carpeta `/images` con estos nombres:
- `trabajo-1.jpg` - Primera imagen
- `trabajo-2.jpg` - Segunda imagen
- `trabajo-3.jpg` - Tercera imagen
- `trabajo-4.jpg` - Cuarta imagen
- `trabajo-5.jpg` - Quinta imagen
- `trabajo-6.jpg` - Sexta imagen

**Ejemplo de ruta completa:**
```
d:\Proyectos GIT\retoquesada.github.io\images\trabajo-1.jpg
```

### Paso 3: Actualizar Textos (Opcional)
Si deseas cambiar los títulos de cada imagen, edita [index.html](index.html#L1138-L1151) en la sección de galería:

```html
<figure class="gallery-item">
    <img src="images/trabajo-1.jpg" alt="Tu descripción aquí">
    <figcaption>Título que aparecerá al pasar el ratón</figcaption>
</figure>
```

## Cambios Realizados

✅ **Estructura HTML mejorada:**
- Cambié de `<div>` simples a `<figure>` y `<figcaption>` (más semántico)
- Agregar imágenes es ahora tan simple como copiar archivos a `/images`

✅ **Estilos CSS actualizados:**
- Las imágenes se verán bonitas con un efecto hover
- El título aparece al pasar el ratón
- Responsive en móviles (se adapta automáticamente)

✅ **Atributos útiles:**
- `loading="lazy"` para cargar imágenes solo cuando se necesitan (más rápido)
- `alt` descriptivos para accesibilidad y SEO

## Cómo Agregar Más Imágenes

Si quieres **más de 6 imágenes**, simplemente:

1. Copia este código en [index.html](index.html#L1138) dentro de `<div class="gallery-grid">`:
```html
<figure class="gallery-item">
    <img src="images/trabajo-7.jpg" alt="Descripción de tu trabajo">
    <figcaption>Título del Trabajo</figcaption>
</figure>
```

2. Guarda la imagen como `trabajo-7.jpg` en `/images`

¡La galería se ajustará automáticamente con responsive design!

## Carpeta de Imágenes

La carpeta `/images` ya existe y contiene:
- `logo-retoques-ada.png` (logo actual)
- [Aquí irán tus trabajos]

## Notas

- Las imágenes deben estar en formato **JPG o PNG**
- Mantén nombres descriptivos y numerados (trabajo-1, trabajo-2, etc.)
- Las imágenes se optimizan automáticamente con `loading="lazy"`
- No es necesario editar código, solo copiar imágenes a la carpeta

---

¡Listo! Solo debes agregar tus fotos a la carpeta `/images` y tu galería se verá increíble! 📸
