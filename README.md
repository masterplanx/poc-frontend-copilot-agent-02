# Microsoft Certifications 2026 - Frontend

Este proyecto es una página web frontend que muestra las últimas certificaciones de Microsoft para 2026, incluyendo certificaciones de Azure, GitHub, y Microsoft 365.

## Características

- ✨ **Diseño Moderno y Responsive**: Adaptado para dispositivos móviles, tablets y escritorio
- 🌓 **Modo Oscuro/Claro**: Alternador de temas con persistencia en localStorage
- 📱 **Totalmente Responsive**: Diseñado con CSS Grid y Flexbox
- 🎨 **Animaciones Suaves**: Transiciones y efectos de hover
- ♿ **Accesible**: Etiquetas ARIA y soporte para lectores de pantalla
- 📊 **Información Actualizada**: Datos obtenidos usando microsoft_docs_search

## Certificaciones Incluidas

### GitHub Certifications
- GitHub Foundations (Beginner)
- GitHub Actions (Intermediate)
- GitHub Copilot (Intermediate)
- GitHub Administration Beta (Intermediate)
- GitHub Advanced Security (Intermediate)

### Azure Certifications
- Azure Administrator Associate (Intermediate)
- Azure Solutions Architect Expert (Expert)
- Cloud and AI Security Engineer Associate SC-500 (NEW - Beta Mayo 2026)
- Security, Compliance, and Identity Fundamentals (Beginner)

### Microsoft 365 Certifications
- Collaboration Communications Systems Engineer Associate (NEW)
- Copilot and Agent Administration Fundamentals (NEW)

## Uso

Simplemente abre el archivo `index.html` en tu navegador web preferido.

```bash
# Si tienes Python instalado, puedes usar un servidor local:
python -m http.server 8000

# O con Node.js:
npx serve
```

Luego abre tu navegador en `http://localhost:8000`

## Estructura del Proyecto

```
.
├── index.html      # Página principal con el contenido
├── styles.css      # Estilos CSS con soporte para temas
├── script.js       # JavaScript para funcionalidad interactiva
└── README.md       # Este archivo
```

## Tecnologías Utilizadas

- HTML5
- CSS3 (Variables CSS, Grid, Flexbox, Media Queries)
- JavaScript ES6+ (Vanilla JS)
- LocalStorage API
- Intersection Observer API

## Características de Diseño

- **Color Palette**: Basada en colores oficiales de Microsoft
- **Typography**: Segoe UI (fuente oficial de Microsoft)
- **Responsive Breakpoints**: 480px, 768px, 1200px
- **Animations**: Fade-in, hover effects, smooth scrolling
- **Accessibility**: ARIA labels, keyboard navigation, screen reader support

## Información de las Certificaciones

Todos los datos de certificaciones fueron obtenidos de la documentación oficial de Microsoft Learn usando la herramienta `microsoft_docs_search`, asegurando información precisa y actualizada para el año 2026.

## Fuentes

- [Microsoft Learn - Certifications](https://learn.microsoft.com/credentials/certifications/)
- [Microsoft Partner Center Announcements 2026](https://learn.microsoft.com/partner-center/announcements/)
- [GitHub Certifications](https://learn.microsoft.com/credentials/browse/?products=github)

## Licencia

Este proyecto es una prueba de concepto (POC) creado con fines educativos.
