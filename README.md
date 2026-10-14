# Portafolio personal

Portafolio de una sola página recreado como una aplicación Angular. La interfaz está inspirada en la plantilla visual de referencia, pero la página se renderiza con componentes y estilos propios de Angular.

## Ejecutar el proyecto

```bash
npm install
npm start
```

Abre `http://localhost:4200/` en el navegador. Para compilar la versión de producción:

```bash
npm run build
```

Para ejecutar las pruebas:

```bash
npm test
```

## Datos y contenido

Los datos personales y el contenido editable están separados de la vista en `src/app/portfolio-content.ts`:

- `profile`: nombre, edad, carrera, universidad y semestre.
- `skills`: habilidades que quieras mostrar.
- `education` y `experience`: entradas para las columnas de trayectoria.
- `projects`: título, categoría, descripción, imagen y enlace de cada proyecto.
- `socialLinks`: enlaces a tus redes.

El perfil incluye desarrollo backend, desarrollo frontend, IoT y experiencia de trabajo junto a tiendas locales. El acceso a proyectos enlaza al perfil de GitHub indicado. La estructura y los datos actuales están documentados en [PORTAFOLIO.md](./PORTAFOLIO.md).

## Diseño

El portafolio usa una paleta cyberpunk oscura con acentos rojos, tipografías Orbitron y Rajdhani, un fondo de portada con rejilla y aros decorativos de bajo contraste, tamaños de letra pensados para leerse en móvil y escritorio, animaciones de entrada al desplazarse, efecto de escritura en la portada y un glitch breve en intervalos aleatorios. El efecto respeta la preferencia de movimiento reducido del sistema. Consulta [PORTAFOLIO.md](./PORTAFOLIO.md) para ver la estructura y el contenido actual.

## Imágenes

Las imágenes que usa la página están organizadas en `public/images/`:

- `profile.jpeg`: foto de perfil.
- `hero-background.jpg`: imagen panorámica de portada.

Los estilos y animaciones están en `src/app/app.scss`, y la estructura de la página en `src/app/app.html`. Las animaciones de entrada al desplazarse y el efecto de escritura están implementados en Angular sin depender de los scripts de la plantilla.
"# portafolio" 
