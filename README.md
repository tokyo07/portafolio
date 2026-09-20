# Portafolio — Douglas Macías

Sitio personal. HTML y CSS estáticos, sin build y sin dependencias:
un solo `index.html` que se puede abrir directo en el navegador.

## Por qué estático

No hay framework porque no hace falta. Un portafolio son cuatro secciones
de texto: meter Next.js aquí añadiría un build, un `node_modules` y una
superficie de mantenimiento a cambio de nada. Carga instantánea, se
despliega en cualquier sitio y dentro de un año seguirá funcionando sin
tocar una sola dependencia.

Si más adelante le agregas un blog con varias entradas, ahí sí vale la
pena migrar a Astro o Next.

## Verlo en local

```bash
python3 -m http.server 4321
```

Luego abre http://localhost:4321

## Desplegarlo

Con el repo ya en GitHub, cualquiera de las dos opciones:

- **Vercel** — importas el repo, framework preset "Other", sin build command.
- **Cloudflare Pages** — igual, build command vacío, output directory `/`.

Las dos dan HTTPS y dominio gratis, y redespliegan solos en cada push.

## Pendiente

- [ ] Reemplazar los dos párrafos de "Sobre mí" con tu voz
- [ ] Poner la URL real de LinkedIn en el enlace del footer
- [ ] Completar o borrar la tarjeta "Infraestructura y monitoreo"
- [ ] Añadir capturas de los proyectos
- [ ] Dominio propio
