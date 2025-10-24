# 🚀 Portfolio Profesional - Armando Ochoa# 🚀 Portfolio Profesional - Armando Ochoa



Portfolio profesional dual construido con Astro, presentando dos perfiles especializados: **Analista de Datos** y **Desarrollador Web**.Portfolio profesional dual construido con Astro, presentando dos perfiles especializados: **Analista de Datos** y **Desarrollador Web**.



## ✨ Características Principales## ✨ Características Principales



- 🎭 **Dual Portfolio**: Dos portafolios completos en uno (Data Analyst & Web Developer)- 🎭 **Dual Portfolio**: Dos portafolios completos en uno (Data Analyst & Web Developer)

- 🌐 **Multilenguaje (i18n)**: Soporte completo para Español e Inglés- 🌐 **Multilenguaje (i18n)**: Soporte completo para Español e Inglés

- 🎨 **Diseño Responsivo**: Experiencia optimizada para todos los dispositivos- 🎨 **Diseño Responsivo**: Experiencia optimizada para todos los dispositivos

- ⚡ **Rendimiento Óptimo**: Construido con Astro para máxima velocidad- ⚡ **Rendimiento Óptimo**: Construido con Astro para máxima velocidad

- 📊 **Iconos Dinámicos**: Sistema de iconos con Iconify para tecnologías- 📊 **Iconos Dinámicos**: Sistema de iconos con Iconify para tecnologías

- 📧 **Formulario de Contacto**: Integrado con Formspree- 📧 **Formulario de Contacto**: Integrado con Formspree

- 🎯 **SEO-friendly**: Meta tags optimizados y URLs canónicas- 🎯 **SEO-friendly**: Meta tags optimizados y URLs canónicas

- 📱 **Galería de Proyectos**: Múltiples estilos de presentación- 📱 **Galería de Proyectos**: Múltiples estilos de presentación

- 🔄 **Sitemap**: Generación automática de sitemap- 🔄 **Sitemap**: Generación automática de sitemap

- 📰 **RSS Feed**: Soporte para feeds RSS- 📰 **RSS Feed**: Soporte para feeds RSS

- 📝 **Blog**: Sistema de blog con Markdown y MDX- 📝 **Blog**: Sistema de blog con Markdown y MDX



## 🏗️ Estructura del Proyecto## 🚀 Project Structure



```textInside of your Astro project, you'll see the following folders and files:

as-portfolio-dev-ad-ui/

├── public/```text

│   ├── assets/├── public/

│   │   ├── jpeg/          # Imágenes de proyectos├── src/

│   │   ├── png/           # Iconos sociales│   ├── components/

│   │   └── svg/           # Recursos SVG│   ├── content/

│   ├── fonts/             # Fuentes personalizadas│   ├── layouts/

│   ├── styles/│   └── pages/

│   │   └── style.css      # Estilos principales├── astro.config.mjs

│   └── index.js           # Scripts del lado cliente├── README.md

├── src/├── package.json

│   ├── components/└── tsconfig.json

│   │   ├── BaseHead.astro          # Meta tags```

│   │   ├── Header.astro            # Navegación

│   │   ├── Footer.astro            # Pie de páginaAstro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

│   │   ├── LanguageSwitcher.astro  # Selector de idioma

│   │   ├── SkillIcon.astro         # Iconos de habilidadesThere's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

│   │   ├── ProjectCard.astro       # Card de proyecto blog

│   │   ├── ProjectDevCard.astro    # Card estilo desarrolloThe `src/content/` directory contains "collections" of related Markdown and MDX documents. Use `getCollection()` to retrieve posts from `src/content/blog/`, and type-check your frontmatter using an optional schema. See [Astro's Content Collections docs](https://docs.astro.build/en/guides/content-collections/) to learn more.

│   │   └── ProjectGalleryCard.astro # Card estilo galería

│   ├── content/Any static assets, like images, can be placed in the `public/` directory.

│   │   └── blog/          # Posts del blog (Markdown/MDX)

│   ├── i18n/## 🧞 Commands

│   │   └── translations.ts # Sistema de traducciones

│   ├── layouts/All commands are run from the root of the project, from a terminal:

│   │   ├── Layout.astro   # Layout principal

│   │   └── BlogPost.astro # Layout para posts| Command                   | Action                                           |

│   ├── pages/| :------------------------ | :----------------------------------------------- |

│   │   ├── index.astro              # Landing page| `npm install`             | Installs dependencies                            |

│   │   ├── data-analyst/| `npm run dev`             | Starts local dev server at `localhost:4321`      |

│   │   │   └── index.astro          # Portfolio Data Analyst (ES)| `npm run build`           | Build your production site to `./dist/`          |

│   │   ├── web-developer/| `npm run preview`         | Preview your build locally, before deploying     |

│   │   │   └── index.astro          # Portfolio Web Developer (ES)| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |

│   │   ├── en/| `npm run astro -- --help` | Get help using the Astro CLI                     |

│   │   │   ├── index.astro          # Landing page (EN)

│   │   │   ├── data-analyst/## 👀 Want to learn more?

│   │   │   │   └── index.astro      # Portfolio Data Analyst (EN)

│   │   │   └── web-developer/Check out [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).

│   │   │       └── index.astro      # Portfolio Web Developer (EN)

│   │   ├── blog/## Credit

│   │   │   ├── index.astro

│   │   │   └── [...slug].astroThis theme is based off of the lovely [Bear Blog](https://github.com/HermanMartinus/bearblog/).

│   │   └── rss.xml.js     # Feed RSS
│   ├── styles/
│   │   └── global.css     # Estilos globales
│   ├── consts.ts          # Constantes
│   └── content.config.ts  # Configuración de contenido
├── astro.config.mjs       # Configuración de Astro
├── tsconfig.json          # Configuración TypeScript
└── package.json
```

### 📁 Descripción de Directorios

- **`public/`**: Archivos estáticos (imágenes, fuentes, estilos CSS personalizados)
- **`src/components/`**: Componentes Astro reutilizables
- **`src/content/`**: Colecciones de contenido (blog posts en Markdown/MDX)
- **`src/i18n/`**: Sistema de internacionalización con traducciones ES/EN
- **`src/layouts/`**: Layouts base para diferentes tipos de páginas
- **`src/pages/`**: Páginas del sitio (rutas basadas en archivos)
  - Rutas en español en la raíz
  - Rutas en inglés bajo `/en/`
  - Dos portafolios: `/data-analyst/` y `/web-developer/`

## 🧞 Comandos

Todos los comandos se ejecutan desde la raíz del proyecto, en una terminal:

| Comando                   | Acción                                              |
| :------------------------ | :-------------------------------------------------- |
| `npm install`             | Instala las dependencias                            |
| `npm run dev`             | Inicia servidor de desarrollo en `localhost:4321`   |
| `npm run build`           | Construye el sitio de producción en `./dist/`       |
| `npm run preview`         | Previsualiza la build localmente antes de desplegar |
| `npm run astro ...`       | Ejecuta comandos CLI como `astro add`, `astro check`|
| `npm run astro -- --help` | Obtén ayuda usando el Astro CLI                     |

## 🛠️ Tecnologías Utilizadas

### Core
- **[Astro](https://astro.build)** - Framework web moderno
- **TypeScript** - Tipado estático
- **CSS** - Estilos personalizados

### Integraciones
- **[@astrojs/mdx](https://docs.astro.build/en/guides/integrations-guide/mdx/)** - Soporte para MDX
- **[@astrojs/rss](https://docs.astro.build/en/guides/rss/)** - Generación de feeds RSS
- **[@astrojs/sitemap](https://docs.astro.build/en/guides/integrations-guide/sitemap/)** - Generación de sitemap

### Librerías Externas
- **[Iconify](https://iconify.design/)** - Biblioteca de iconos
- **[Formspree](https://formspree.io/)** - Gestión de formularios de contacto
- **[Sharp](https://sharp.pixelplumbing.com/)** - Optimización de imágenes

## 🌍 Rutas del Sitio

### Español (Raíz)
- `/` - Landing page
- `/data-analyst` - Portfolio de Analista de Datos
- `/web-developer` - Portfolio de Desarrollador Web
- `/blog` - Blog
- `/about` - Sobre mí

### English
- `/en` - Landing page
- `/en/data-analyst` - Data Analyst Portfolio
- `/en/web-developer` - Web Developer Portfolio

## 📊 Portafolios Incluidos

### 1. Data Analyst Portfolio
- **Habilidades**: Python, Pandas, NumPy, Tableau, SQL, Excel, Jupyter, Plotly, Matplotlib, Seaborn, Scikit-learn
- **Proyectos**: Dashboards interactivos con Tableau Public
- **Enfoque Analítico**: Sección destacada con 3 pilares (Manipulación de Datos, Visualización, Machine Learning)
- **Estilo**: Galería visual con hover overlay y cards informativos

### 2. Web Developer Portfolio
- **Habilidades**: Angular, React, Astro, Next.js, JavaScript, TypeScript, Node.js, Java, Spring, PostgreSQL
- **Proyectos**: Aplicaciones web y sistemas
- **Estilo**: Cards con tags de tecnologías

## 🎨 Componentes Personalizados

### SkillIcon
Muestra iconos de habilidades técnicas con tooltips y efectos hover.
```astro
<SkillIcon name="Python" icon="simple-icons:python" />
<SkillIcon name="React" icon="simple-icons:react" />
```

### ProjectGalleryCard
Card estilo galería para proyectos de Data Analyst.
```astro
<ProjectGalleryCard
  title="Dashboard de Ventas"
  description="Análisis de ventas por región"
  image="/assets/jpeg/project.jpeg"
  tableauUrl="https://public.tableau.com/views/Project"
/>
```

### ProjectDevCard
Card estilo moderno para proyectos de Web Developer.
```astro
<ProjectDevCard
  title="E-commerce Platform"
  description="Plataforma completa de comercio electrónico"
  link="https://github.com/user/project"
  tags={["React", "Node.js", "PostgreSQL"]}
/>
```

### LanguageSwitcher
Selector de idioma con banderas.
```astro
<LanguageSwitcher />
```

## 🌐 Sistema i18n

El proyecto utiliza un sistema de traducciones personalizado ubicado en `src/i18n/translations.ts`:

```typescript
import { useTranslations } from "../i18n/translations";

const t = useTranslations('es'); // o 'en'
```

## 📧 Formulario de Contacto

Integrado con Formspree para gestión de mensajes sin backend:
- Validación de campos
- Respuesta automática
- Protección anti-spam

## 🚀 Despliegue

El sitio puede desplegarse en:
- **Vercel** (recomendado)
- **Netlify**
- **GitHub Pages**
- **Cloudflare Pages**

```bash
npm run build
```

El sitio estático se generará en la carpeta `./dist/`.

## 📝 Agregar Contenido

### Nuevo Post del Blog
1. Crear archivo en `src/content/blog/`
2. Usar formato Markdown (.md) o MDX (.mdx)
3. Incluir frontmatter:

```markdown
---
title: 'Título del Post'
description: 'Descripción breve'
pubDate: 'Jan 01 2024'
heroImage: '/assets/jpeg/hero.jpg'
---

Contenido del post...
```

### Nuevo Proyecto
Editar los archivos de página correspondientes:
- `src/pages/data-analyst/index.astro` (Data Analyst)
- `src/pages/web-developer/index.astro` (Web Developer)

Agregar componente `ProjectGalleryCard` o `ProjectDevCard` según corresponda.

## 🎯 Personalización

### Colores del Tema
Los colores principales se encuentran en:
- `public/styles/style.css` (variables CSS)
- `src/components/SkillIcon.astro` (color de iconos: `#0062b9`)

### Fuentes
Las fuentes se cargan desde Google Fonts en `src/layouts/Layout.astro`:
- **Source Sans Pro** (400, 600, 700, 900)

### Iconos Sociales
Editar enlaces en `src/components/Footer.astro`:
- LinkedIn
- GitHub
- Twitter
- YouTube
- Instagram

## 📄 Licencia

Este proyecto está bajo licencia MIT.

## 👨‍💻 Autor

**Armando Ochoa**
- LinkedIn: [armando-ochoa-data-analyst](https://www.linkedin.com/in/armando-ochoa-data-analyst)
- GitHub: [Armando8a-dev](https://github.com/Armando8a-dev)

## 🙏 Agradecimientos

- Framework [Astro](https://astro.build)
- Iconos de [Iconify](https://iconify.design/)

---

⭐ Si este proyecto te fue útil, ¡considera darle una estrella!
