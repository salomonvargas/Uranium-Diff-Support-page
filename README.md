# Uranium Diff — Sitio de soporte

Contenido de la **página de soporte** de [Uranium Diff](https://apps.apple.com/) (app de comparación de archivos para macOS), pensado para publicarse en **GitHub Pages** como sitio estático. Cumple los requisitos de Apple: descripción, guía de uso, FAQ, solución de problemas, contacto/soporte, política de privacidad y compatibilidad.

> **Estado: FASE 1 — solo contenido.** Las páginas están en Markdown, bilingües (ES/EN). El estilo, el layout y la configuración de Jekyll son **FASE 2** (aún no implementados).

## Estructura del contenido

```
.
├── es/                          # Español
│   ├── index.md                 # Descripción + funcionalidades + compatibilidad + planes
│   ├── inicio-rapido.md         # Guía básica de uso + atajos de teclado
│   ├── preguntas-frecuentes.md  # FAQ
│   ├── solucion-de-problemas.md # Troubleshooting
│   ├── privacidad.md            # Política de privacidad
│   └── soporte.md               # Contacto + reporte de bugs + feedback
├── en/                          # English (espejo de es/)
│   ├── index.md
│   ├── quick-start.md
│   ├── faq.md
│   ├── troubleshooting.md
│   ├── privacy.md
│   └── support.md
└── README.md                    # este archivo
```

### Pendiente para FASE 2 (implementación)
- `_config.yml` (título, `url`/`baseurl`, colecciones `es`/`en`).
- `_layouts/default.html` y `_includes/` (nav, footer, selector de idioma).
- `assets/css/style.css` — estilo tipo documentación técnica (limpio, legible, responsive, claro/oscuro).
- `index.md` raíz que dirija al idioma (página de selección o redirección por defecto).
- `assets/img/` — ícono de la app y capturas de pantalla (copiar solo las imágenes finales; no incluir rutas ni archivos del proyecto de código).
- ✅ `.github/ISSUE_TEMPLATE/` — plantillas de *bug report* y *feature request* + `config.yml` (creadas).
- `CNAME` si se usa dominio propio.

## URLs a registrar en App Store Connect
URL base actual (GitHub Pages de proyecto): `https://salomonvargas.github.io/Uranium-Diff-Support-page/`
- **Support URL** → `https://salomonvargas.github.io/Uranium-Diff-Support-page/`
- **Privacy Policy URL** → `https://salomonvargas.github.io/Uranium-Diff-Support-page/es/privacidad` (y `/en/privacy`)

Si más adelante se configura un dominio propio (archivo `CNAME`), actualizar estas URLs y el enlace de `config.yml`.

## Notas a verificar antes de publicar
1. **Requisito de macOS:** el sitio indica **macOS 26 (Tahoe) o posterior · Apple Silicon** (las versiones que soportan Apple Intelligence, donde corre el motor de IA on-device de la app). ⚠️ El *deployment target* del build debe subirse a **macOS 26** para que coincida con lo publicado; hoy figura en 15.0. Ajustar `LSMinimumSystemVersion` / `MACOSX_DEPLOYMENT_TARGET` en el proyecto de código antes de enviar a revisión.
2. **Dominio/URL del sitio:** por defecto GitHub Pages de proyecto → `https://salomonvargas.github.io/Uranium-Diff-Support-page/`. Opcional: dominio propio (p. ej. `support.uraniumdiff.app`) con archivo `CNAME`. Si cambia, actualizar las URLs de App Store Connect y `config.yml`.
3. **Rastreador de Issues:** el repo de **código** sigue **privado**. Los reportes usan los **Issues de este mismo repo público**. Falta solo: verificar que *Settings ▸ Features ▸ Issues* esté activado y crear las etiquetas `app`, `web`, `bug`, `feature` (las plantillas ya las aplican). Enlaces y usuario (`salomonvargas`) ya rellenados en `es/soporte.md` y `en/support.md`.
4. **Correo de soporte:** confirmar que **uraniumdiff@outlook.com** está creado y monitoreado.
5. **Fecha de la política de privacidad:** hoy queda en **13/07/2026**; actualizar si el contenido cambia antes de publicar.

## Datos de la app (referencia)
- Nombre: **Uranium Diff** · Versión **1.0.0**
- Requiere **macOS 26 (Tahoe) o posterior** · **Apple Silicon** (M1 o posterior)
- Categoría: Developer Tools · Clasificación 4+ · Idiomas: Español, Inglés
- Privacidad: *Data Not Collected*, sin rastreo, IA on-device

> **Nota:** este repo es **público** (GitHub Pages). No incluir identificadores internos (Bundle ID, IDs de productos de compra, Team ID de Apple, `project.yml`/`Info.plist`/entitlements) ni rutas del repositorio de código privado.
