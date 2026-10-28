# Taller Multimedia: probando Primer CSS

La tarea era elegir una librería de CSS y conectarla a una página web desde GitHub Codespaces. Yo escogí **Primer**, la librería que usa GitHub en su propia página.

La elegí porque me parecía curioso usar el mismo estilo de la plataforma donde estoy guardando el trabajo. Además, sus clases son fáciles de entender: con `btn btn-primary` ya tienes un botón verde y con `Box` una tarjeta, sin escribir nada de CSS.

## Cómo la conecté

No descargué nada, usé un CDN. Solo pegué esta línea en el `<head>` de mi `index.html`:

```html
<link href="https://unpkg.com/@primer/css@^20.2.4/dist/primer.css" rel="stylesheet" />
```

## Qué usé en la página

Un contenedor para centrar el contenido, un botón, una tarjeta y algunas clases de espaciado (`p-4`, `mt-4`, `mb-2`) para acomodar todo.

## Cómo verla

Abre el repositorio en Codespaces, instala la extensión Live Server y dale clic derecho a `index.html` → *Open with Live Server*.

## Qué aprendí

Que una librería de CSS te ahorra mucho trabajo, y que conectarla es tan simple como agregar un enlace. También practiqué subir cambios a GitHub con `git add`, `git commit` y `git push`.

Más info de la librería: https://primer.style/css
