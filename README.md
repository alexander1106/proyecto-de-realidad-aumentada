# AR SQL Lab

Laboratorio de bases de datos en **realidad aumentada**. Aprende SQL manipulando tablas en 3D, viendo sus relaciones y resolviendo retos, todo desde el navegador.

## Características

- **Tablas 3D**: visualiza las tablas y sus registros como objetos en el espacio.
- **Relaciones PK–FK**: inspecciona claves primarias y foráneas entre tablas.
- **Consultas SQL**: practica `SELECT`, `JOIN` y `GROUP BY` con sugerencias mientras escribes.
- **Retos**: ejercicios guiados paso a paso con puntaje.
- **Modo cámara**: coloca el laboratorio sobre tu entorno usando la cámara trasera y el giroscopio del móvil.

## Tecnología

Aplicación estática de un solo archivo (`index.html`): HTML, CSS y JavaScript puro. No requiere instalación, dependencias ni build.

## Uso local

Abre `index.html` en el navegador. Para el modo cámara necesitas un contexto seguro (`https://` o `localhost`):

```bash
# opción con Python
python -m http.server 8000
# luego visita http://localhost:8000
```

## Despliegue en Vercel

1. Importa este repositorio en [vercel.com/new](https://vercel.com/new).
2. Framework Preset: **Other**. Sin build command ni output directory.
3. Despliega. Vercel sirve el sitio con HTTPS, necesario para acceder a la cámara.

## Requisitos del dispositivo

- Navegador moderno con WebGL.
- Para el modo cámara: permiso de cámara y, en móviles, acceso a los sensores de movimiento.

## Autor

Alexander
