# Unicode Landing Page

Una página de aterrizaje moderna y responsiva para **Unicode**, una comunidad estudiantil enfocada en la innovación y tecnología.

## 🚀 Tecnologías

- **[Astro](https://astro.build/)**: Framework web para sitios rápidos y orientados al contenido.
- **[Tailwind CSS](https://tailwindcss.com/)**: Framework CSS de utilidad primero para un diseño rápido.
- **[Astro Icon](https://www.astroicon.dev/)**: Iconos optimizados para Astro (usando iconos SVG directos).
- **Google Fonts**: Tipografía 'Inter'.

## 📂 Estructura del Proyecto

```text
unicode-landing/
├── public/                 # Assets estáticos
├── src/
│   ├── components/         # Componentes reutilizables
│   │   ├── ui/             # Botones, Badges
│   │   ├── cards/          # Tarjetas de proyectos/áreas
│   │   ├── shared/         # Navbar, Footer
│   │   └── sections/       # Secciones (Hero, Nosotros)
│   ├── layouts/            # Layout principal
│   ├── pages/              # Rutas y páginas
│   │   ├── areas/          # Páginas dinámicas de áreas
│   │   ├── proyectos/      # Páginas dinámicas de proyectos
│   │   └── index.astro     # Página de inicio
│   ├── lib/                # Configuración (Supabase)
│   └── styles/             # Estilos globales
└── .env                    # Variables de entorno
```

## 🧞 Comandos

Todos los comandos se ejecutan desde la raíz del proyecto:

| Comando                   | Acción                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Instala las dependencias                         |
| `npm run dev`             | Inicia el servidor de desarrollo en `localhost:4321` |
| `npm run build`           | Compila el sitio para producción en `./dist/`    |
| `npm run preview`         | Previsualiza la compilación localmente           |

## 🎨 Características de Diseño

- **Modo Oscuro**: Fondo negro (`#0a0a0a`) con acentos en verde Unicode (`#22c55e`).
- **Glassmorphism**: Efectos de transparencia y desenfoque en tarjetas y navegación.
- **Animaciones**: Transiciones suaves y efectos de carga.
- **Responsivo**: Adaptado para móviles, tablets y escritorio.

## 🛠 Configuración

Copia el archivo `.env.example` a `.env` y configura tus variables de entorno si es necesario (por ejemplo, para Supabase).

```bash
cp .env.example .env
```
