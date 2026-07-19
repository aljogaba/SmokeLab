# Smoke Lab

**Barbecue · ciencia · fuego lento**

Sitio estático y bitácora pública de experimentos de barbecue.

## Estructura

```text
SmokeLab/
├── index.html
├── experiments/
│   ├── index.html
│   ├── exp-001-pulled-pork.html
│   └── experiment-template.html
├── protocols/
├── science/
├── about/
├── assets/
│   ├── css/
│   ├── js/
│   └── img/
└── lab/
    ├── experiments/
    └── templates/
```

## Abrir en Visual Studio Code

1. Abre la carpeta `C:\GitHub\SmokeLab`.
2. Abre `index.html`.
3. Haz clic derecho.
4. Selecciona `Open with Live Server`.

También puedes abrir `index.html` directamente porque los enlaces son relativos.

## Crear un experimento nuevo

1. Copia `experiments/experiment-template.html`.
2. Renombra la copia, por ejemplo `exp-002-costillas.html`.
3. Sustituye código, título, datos y secciones.
4. Copia una entrada dentro de `experiments/index.html`.
5. Crea una carpeta para imágenes:
   `assets/img/experiments/exp-002/`.
6. Crea su registro de laboratorio en `lab/experiments/`.

## Publicar con GitHub Pages

Configura la publicación desde:

- rama: `main`
- carpeta: `/(root)`

El archivo `.nojekyll` evita procesamiento innecesario de Jekyll.
