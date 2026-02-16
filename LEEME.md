# 🚀 Servicio Técnico Web - Guía Rápida

## Servidor de Desarrollo

El servidor está corriendo en: **http://localhost:4322/** 🎉

Abre tu navegador y visita esa URL para ver tu sitio web.

---

## 📝 Personalizar Contenido

### 1. Cambiar Número de Teléfono

Busca y reemplaza `644259979` o `+34912345678` en:

- `src/components/Navbar.astro`
- `src/components/Hero.astro`
- `src/components/ServicesGrid.astro`
- `src/pages/index.astro`

### 2. Cambiar Nombre de Empresa

Reemplaza "TecniHouse" por el nombre de tu empresa en:

- `src/components/Navbar.astro`
- `src/layouts/Layout.astro`
- `src/pages/index.astro`

### 3. Actualizar Imágenes

Lee el archivo [IMAGENES.md](file:///c:/Users/EQUIPO/Desktop/rep/servicio-tecnico/IMAGENES.md) para reemplazar las imágenes placeholder.

---

## 🎨 Cambiar Colores

El color morado (#7c3aed) se usa en todo el sitio. Para cambiarlo:

1. Busca `purple-600` en los archivos
2. Reemplázalo con otro color de Tailwind (ej: `blue-600`, `green-600`)

Colores Tailwind disponibles:

- `blue-600` - Azul
- `red-600` - Rojo
- `green-600` - Verde
- `indigo-600` - Índigo
- `pink-600` - Rosa

---

## 🌐 Desplegar el Sitio

### Opción 1: Vercel (Recomendado)

```bash
npm install -g vercel
vercel
```

### Opción 2: Netlify

```bash
npm run build
# Sube la carpeta 'dist' a Netlify
```

### Opción 3: Cloudflare Pages

1. Crea un repositorio en GitHub
2. Conecta Cloudflare Pages a tu repositorio
3. Configura build: `npm run build`
4. Carpeta de salida: `dist`

---

## 📞 Información de Contacto a Actualizar

En `src/pages/index.astro` (sección footer), actualiza:

- 📞 Teléfono
- 📧 Email
- 📍 Ubicación
- 🕐 Horario

---

## ❓ ¿Necesitas Ayuda?

- Revisa la [documentación de Astro](https://docs.astro.build)
- Revisa la [documentación de Tailwind CSS](https://tailwindcss.com/docs)
- Lee el archivo [walkthrough.md](file:///C:/Users/EQUIPO/.gemini/antigravity/brain/edeaa85e-ec59-4d2f-a49c-239c683bb04d/walkthrough.md) completo
