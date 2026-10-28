# Taller Multimedia: probando Primer CSS

La tarea era elegir una librería de CSS y conectarla a una página web desde GitHub Codespaces. Yo escogí **Primer**, la librería que usa GitHub en su propia página.

La elegí porque me parecía curioso usar el mismo estilo de la plataforma donde estoy guardando el trabajo. Además, sus clases son fáciles de entender: con `btn btn-primary` ya tienes un botón verde y con `Box` una tarjeta, sin escribir nada de CSS.

## Cómo la conecté

No descargué nada, usé un CDN. Solo pegué esta línea en el `<head>` de mi `index.html`:

```html
<link href="https://unpkg.com/@primer/css@^20.2.4/dist/primer.css" rel="stylesheet" />
```

## Cómo verla

Abre el repositorio en Codespaces, instala la extensión Live Server y dale clic derecho a `index.html` → *Open with Live Server*.


Más info de la librería: https://primer.style/css