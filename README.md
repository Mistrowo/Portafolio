# 🚀 Portafolio de Alex Parada

Un portafolio profesional y moderno construido con [Astro](https://astro.build), diseñado para mostrar proyectos, habilidades y experiencia de manera elegante.

## ✨ Características

- 🎨 **Diseño Moderno** - Estética cyber/tech con gradientes, animaciones y efectos visuales
- 📱 **Responsive** - Optimizado para todos los dispositivos
- ⚡ **Rendimiento** - Construido con Astro para máxima velocidad
- 🌙 **Tema Oscuro** - Diseño dark mode elegante
- ♿ **Accesible** - Siguiendo las mejores prácticas de accesibilidad
- 🔍 **SEO Optimizado** - Meta tags y estructura semántica
- 🚀 **Listo para Deploy** - Configurado para Vercel y Netlify

## 📁 Estructura del Proyecto

```
portfolio/
├── public/
│   ├── favicon.svg
│   └── robots.txt
├── src/
│   ├── components/
│   │   ├── Header.astro
│   │   ├── Hero.astro
│   │   ├── About.astro
│   │   ├── Skills.astro
│   │   ├── Projects.astro
│   │   ├── Contact.astro
│   │   └── Footer.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css
├── astro.config.mjs
├── package.json
├── tsconfig.json
├── vercel.json
└── netlify.toml
```

## 🛠️ Instalación

1. **Crea la carpeta del proyecto**
   ```bash
   mkdir portfolio
   cd portfolio
   ```

2. **Crea la estructura de carpetas**
   ```bash
   mkdir -p src/components src/layouts src/pages src/styles public
   ```

3. **Copia los archivos a sus ubicaciones**
   - `package.json` → raíz del proyecto
   - `astro.config.mjs` → raíz del proyecto
   - `tsconfig.json` → raíz del proyecto
   - `vercel.json` → raíz del proyecto
   - `netlify.toml` → raíz del proyecto
   - `gitignore.txt` → renombrar a `.gitignore` en raíz
   - `favicon.svg` → `public/`
   - `robots.txt` → `public/`
   - `global.css` → `src/styles/`
   - `Layout.astro` → `src/layouts/`
   - `index.astro` → `src/pages/`
   - Todos los componentes `.astro` → `src/components/`

4. **Instala las dependencias**
   ```bash
   npm install
   ```

5. **Inicia el servidor de desarrollo**
   ```bash
   npm run dev
   ```

6. **Abre el navegador**
   
   Visita `http://localhost:4321` para ver el sitio

## 📦 Comandos Disponibles

| Comando | Acción |
|---------|--------|
| `npm run dev` | Inicia el servidor de desarrollo en `localhost:4321` |
| `npm run build` | Construye el sitio para producción en `./dist/` |
| `npm run preview` | Vista previa del build localmente |

## 🚀 Despliegue

### Vercel (Recomendado)

1. Sube tu proyecto a GitHub
2. Importa tu repositorio en [Vercel](https://vercel.com)
3. El framework se detectará automáticamente
4. ¡Listo! Tu sitio estará en línea

### Netlify

1. Sube tu proyecto a GitHub
2. Importa tu repositorio en [Netlify](https://netlify.com)
3. La configuración ya está lista en `netlify.toml`
4. ¡Desplegado!

## 🎨 Personalización

### Colores
Edita las variables CSS en `src/styles/global.css`:

```css
:root {
  --color-accent-primary: #00d4ff;
  --color-accent-secondary: #7c3aed;
  --color-accent-tertiary: #10b981;
}
```

### Contenido
- **Información personal**: Edita `Hero.astro` y `About.astro`
- **Habilidades**: Modifica el array `skills` en `Skills.astro`
- **Proyectos**: Actualiza el array `projects` en `Projects.astro`
- **Contacto**: Actualiza los enlaces en `Contact.astro`

## 👤 Autor

**Alex Parada**
- GitHub: [@Mistrowo](https://github.com/Mistrowo)
- LinkedIn: [Alex Parada](https://www.linkedin.com/in/alex-parada-0a4069213/)

---

⭐ Si te gustó este proyecto, ¡no olvides darle una estrella!   