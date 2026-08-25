# Taller de Herramientas Computacionales

Sitio del curso: temario interactivo de Python & LaTeX intercalados (32 sesiones, 64 horas) y materiales descargables.

## Estructura

```
cursos/
|-- index.html                  # Temario interactivo (la página del sitio)
|-- pdfs/
|   |-- programa_sesiones.pdf   # Programa completo compilado desde LaTeX
|-- latex/
|   |-- main.tex                # Fuente LaTeX del programa
|-- README.md
```

## Cómo agregar materiales (PDFs u otros archivos)

1. Sube el archivo a la carpeta `pdfs/` (botón **Add file → Upload files** en GitHub).
2. Enlázalo desde `index.html` en la sección **Materiales**, agregando una línea como:

```html
<a href="pdfs/mi_archivo.pdf"><span class="ico">PDF</span> Nombre visible del archivo</a>
```

3. Haz *commit*. GitHub Pages actualiza el sitio en uno o dos minutos.

Cualquier tipo de archivo funciona (`.pdf`, `.ipynb`, `.tex`, `.zip`…), con límite de 100 MB por archivo.

## Publicación

El sitio se publica con GitHub Pages desde la rama `main`, carpeta raíz (`/`).
URL: `https://TUUSUARIO.github.io/cursos/`
