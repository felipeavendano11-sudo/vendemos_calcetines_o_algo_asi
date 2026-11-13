# Sockbuster Video & Socks

Prototipo web y documentación de arquitectura (paradigma 4+1) del caso de estudio **Sockbuster Video & Socks**.
Asignatura: Modelamiento de soluciones informáticas (TI3025), Evaluación 3. Autores: **Felipe Avendaño** y **María Cartagena**.

**Sitio publicado:** https://vendemoscalcetinesoalgoadospuntouve.netlify.app

## Páginas
- `index.html`: presentación de la marca y autor.
- `catalogo.html`: catálogo con filtros, carrito, checkout, reseñas y panel de administración (datos simulados en el navegador).
- `diagramas.html`: vistas Lógica, Desarrollo, Procesos, Física y Escenarios.

## Demo
- Cliente: `cliente@sockbuster.cl` / `1234`
- Administrador: `admin@sockbuster.cl` / `admin123`

## Estructura
```
index.html  catalogo.html  diagramas.html
css/styles.css   js/app.js
assets/diagramas/*.png   plantuml/*.puml
```

## Despliegue en Netlify
Sin build: publicar la carpeta raíz del repositorio (Publish directory: `.`).
