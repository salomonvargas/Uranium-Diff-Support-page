---
layout: default
title: "Inicio rápido"
lang: es
ref: quick-start
permalink: /es/inicio-rapido/
---

# Inicio rápido

### 1. Cada comparación vive en su propia pestaña
Con los botones de la barra de pestañas creas sesiones de **archivos**, **carpetas** o **ramas de Git**. Cierra cada una con su ✕.

### 2. Elige los dos lados
En una sesión vacía, elige el archivo **izquierdo** y el **derecho** desde tu Mac, desde una **URL** o desde un **servidor SSH**. También puedes **arrastrar archivos desde el Finder**: si sueltas dos a la vez, se colocan automáticamente a izquierda y derecha. Usa el botón central para intercambiar los lados.

### 3. Compara
Pulsa **«Comparar ahora»** (o Intro). El cálculo corre en segundo plano; si el archivo es muy grande puedes cancelarlo con **⌘.**

### 4. Explora las diferencias
- Cambia entre **Lado a lado**, **Inline** y **Árbol** (este último para JSON/YAML/XML/plist) con el selector de la barra de herramientas.
- Salta entre cambios con **▲/▼** o **⌘↑ / ⌘↓**.
- El **minimapa** de la derecha resume todo el archivo (verde = añadido, rojo = eliminado, amarillo = modificado); haz clic para saltar.
- Los botones de color muestran u ocultan líneas añadidas, eliminadas o modificadas.

### Comparar carpetas
Crea una sesión de **carpetas** y elige dos carpetas locales o remotas (SSH). El resultado clasifica los archivos en **añadidos, eliminados, modificados e idénticos**. Haz **doble clic** en un archivo modificado para abrir su comparación detallada en una pestaña nueva. Puedes copiar archivos de un lado al otro con política de conflictos (reemplazar / conservar ambos / cancelar).

### Comparar ramas de Git
Con **«Fusión ▸ Comparar ramas Git…» (⇧⌘B)** eliges un repositorio local y dos ramas o commits. Verás la lista de archivos cambiados con sus estadísticas y podrás abrir el detalle de cada uno.

### Usar Uranium Diff como herramienta de Git
En **«Fusión ▸ Integración con Git…»** instala el helper `uraniumdiff` y registra la app como `difftool`/`mergetool`. La configuración automática solo pide autorizar tu carpeta de inicio una vez; también verás los comandos para hacerlo manualmente desde la Terminal. Después, ejecuta `git difftool` en cualquier repositorio y las diferencias se abrirán como pestañas de Uranium Diff.

### Apple Intelligence
El botón **«IA»** de la barra de herramientas abre un panel que puede resumir el diff y explicar el cambio enfocado. Todo el procesamiento ocurre en tu Mac. *Verifica siempre la información generada.*

### Exportar resultados
En el menú **«Más» (…)** de una comparación puedes copiar el diff unificado al portapapeles o exportar el resultado como **HTML** o **PDF**, conservando colores y estadísticas.

### Atajos de teclado
| Atajo | Acción |
|---|---|
| ⌘N | Nueva sesión de archivos |
| ⌘O | Abrir archivo izquierdo |
| ⇧⌘O | Abrir archivo derecho |
| ⌘W | Cerrar la sesión activa |
| ⇧⌘B | Comparar ramas de Git |
| ⌘↑ | Cambio anterior |
| ⌘↓ | Cambio siguiente |
| ⌘+ / ⌘− | Aumentar / reducir el tamaño de letra |
| ⌘. | Cancelar la comparación en curso |
| ⌘C | Copiar la selección |
| ⌘? | Abrir la ayuda de la app |
