# Sistemas de Gestión - Landing Page

Sitio web profesional para Sistemas de Gestión, especialistas en soluciones de pesaje y TPV para comercio y hostelería, con cumplimiento de la normativa VERIFACTU.

## 🚀 Tecnologías Utilizadas

- **Astro** - Framework web moderno y rápido
- **Tailwind CSS** - Framework de CSS utility-first
- **TypeScript** - Tipado estático para JavaScript

## 📋 Características

- ✅ Diseño responsivo para todos los dispositivos
- ✅ Optimización SEO completa
- ✅ Carrusel de productos interactivo con modal de detalles
- ✅ Sección informativa sobre VERIFACTU
- ✅ Preguntas frecuentes (FAQ) con acordeón
- ✅ Formulario de contacto funcional
- ✅ Sitemap automático
- ✅ Optimización de imágenes
- ✅ Accesibilidad web

## 🏗️ Estructura del Proyecto

```
/
├── public/
│   ├── images/          # Imágenes de productos
│   ├── favicon.svg      # Icono del sitio
│   ├── robots.txt       # Configuración para bots
│   └── Folleto_VERIFACTU_es_es.pdf
├── src/
│   ├── components/      # Componentes reutilizables
│   ├── layouts/         # Layouts de página
│   ├── pages/           # Páginas del sitio
│   └── styles/          # Estilos globales
├── astro.config.mjs     # Configuración de Astro
├── tailwind.config.mjs  # Configuración de Tailwind
└── package.json
```

## 🚀 Comandos

| Comando                | Acción                                          |
| :--------------------- | :---------------------------------------------- |
| `npm install`          | Instala las dependencias                       |
| `npm run dev`          | Inicia el servidor de desarrollo en `localhost:4321` |
| `npm run build`        | Construye el sitio para producción en `./dist/` |
| `npm run preview`      | Previsualiza la construcción localmente        |

## 📱 Secciones de la Página

1. **Header** - Navegación principal con menú responsive
2. **Hero** - Sección principal con llamada a la acción
3. **Productos** - Carrusel de productos con filtros por categoría
4. **Sobre Nosotros** - Información de la empresa y experiencia
5. **VERIFACTU** - Información sobre la nueva normativa
6. **FAQ** - Preguntas frecuentes con acordeón interactivo
7. **Contacto** - Formulario de contacto y información
8. **Footer** - Enlaces adicionales e información de contacto

## 🎨 Personalización

### Colores
Los colores principales se pueden modificar en `tailwind.config.mjs`:

```javascript
colors: {
  primary: {
    50: '#f0f9ff',
    500: '#0ea5e9',
    600: '#0284c7',
    // ...
  }
}
```

### Contenido
- **Productos**: Editar el array en `src/components/ProductCarousel.astro`
- **FAQ**: Modificar el array en `src/components/FAQSection.astro`
- **Información de empresa**: Actualizar en `src/components/AboutSection.astro`

## 📊 SEO

El sitio incluye optimizaciones SEO completas:
- Meta títulos y descripciones optimizados
- Open Graph tags para redes sociales
- Twitter Cards
- Sitemap automático
- Robots.txt
- Schema markup estructurado

## 🌐 Despliegue

El sitio está configurado para desplegarse automáticamente en GitHub Pages. Cada push a la rama main construirá y desplegará el sitio.

## 📞 Contacto

Para más información sobre Sistemas de Gestión:
- Email: info@sistemasdegestion.es
- Web: https://sdgestion.github.io