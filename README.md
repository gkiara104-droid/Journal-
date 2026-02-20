# Feel Good Journal

Una app web progresiva (PWA) de journaling personal inspirada en los diarios guiados de **It's OK Generation**.

## Funcionalidades

- **Reflexión** — 365 prompts guiados, uno por día del año
- **Emociones** — Registro emocional diario con intensidad y notas
- **Gratitud** — Lista de momentos de gratitud del día
- **Metas** — Seguimiento de intenciones con barra de progreso
- **Mi día** — Diario libre con estado del día y historial

## Instalar como app

Al abrirla en el navegador, aparecerá un aviso para **"Añadir a pantalla de inicio"** (iOS/Android) o **"Instalar app"** (Chrome/Edge en escritorio). Una vez instalada, funciona sin conexión.

## Desplegar en GitHub Pages

1. Haz fork o sube este repositorio a GitHub
2. Ve a **Settings → Pages**
3. En *Source*, selecciona la rama `main` y carpeta `/` (root)
4. Guarda — en unos segundos tendrás tu URL pública

```
https://tu-usuario.github.io/feel-good-journal/
```

Una vez desplegada, la app es **instalable desde esa URL** en cualquier dispositivo.

## Estructura

```
├── index.html       # App completa (HTML + CSS + JS en un solo archivo)
├── manifest.json    # Configuración PWA
├── sw.js            # Service Worker (caché offline)
└── icons/
    ├── icon.svg     # Icono vectorial
    ├── icon-192.png # Icono para Android / Chrome
    └── icon-512.png # Icono splash screen
```

## Tecnologías

- HTML / CSS / JS vanilla — sin dependencias ni frameworks
- Google Fonts (Cormorant Garamond + Jost)
- PWA con Service Worker para uso offline
- Paleta basada en atardecer marino: Delft Blue, Earth Yellow, Persian Orange

---

Hecho con amor propio ✦
