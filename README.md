# CV — Nicolas Gutierrez

Hoja de vida en línea de **Nicolas Steven Gutierrez Castiyejo**, Ingeniero de Sistemas enfocado en Ingeniería de Datos (Medellín, Colombia).

Sitio estático: solo HTML, CSS y JavaScript. No requiere dependencias ni proceso de build.

## Estructura del proyecto

```
cv_nicolas_gutierrez/
├── index.html        # Estructura y contenido de la página
├── css/
│   └── styles.css    # Estilos (variables, tipografía, secciones, responsive)
├── js/
│   └── main.js       # Animación de aparición al hacer scroll (IntersectionObserver)
└── README.md
```

### Secciones de la página

- Hero (nombre, rol y presentación)
- Experiencia
- Habilidades
- Educación
- Certificaciones
- Idiomas
- Contacto

## Cómo verla en local

Basta con abrir `index.html` en el navegador. Si prefieres un servidor local:

```bash
python -m http.server 8000
```

Luego visita `http://localhost:8000`.

## Tecnologías

- HTML5 semántico
- CSS3 con variables personalizadas (`:root`) y media queries
- JavaScript vanilla
- Tipografías de Google Fonts: Fraunces, JetBrains Mono, Inter Tight

## Personalización

- **Colores y tipografía:** edita las variables al inicio de `css/styles.css`.
- **Contenido:** modifica las secciones directamente en `index.html`.
- **Animaciones:** los elementos con la clase `reveal` se animan al entrar en pantalla; la lógica está en `js/main.js`.

## Despliegue

Al ser un sitio estático puede publicarse en GitHub Pages, Netlify o Vercel sin configuración adicional.
