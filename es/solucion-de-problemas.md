---
layout: default
title: "Solución de problemas"
lang: es
ref: troubleshooting
permalink: /es/solucion-de-problemas/
---

# Solución de problemas

**La comparación tarda mucho o parece congelada.**
El cálculo corre en segundo plano. Con archivos muy grandes puede tardar; cancela con **⌘.** e inténtalo con archivos más pequeños o con los filtros de líneas activados.

**No puedo conectar por SSH.**
1. Verifica **host, puerto, usuario** y credenciales.
2. Si usas **clave**, recuerda que solo se admiten **Ed25519/ECDSA**; para servidores **solo-RSA**, cambia a **contraseña**.
3. Las credenciales se guardan en el **Llavero**; si cambiaste la contraseña del servidor, actualiza la conexión guardada.

**El botón/panel de Apple Intelligence está deshabilitado o no aparece.**
Confirma que usas **macOS 26 (Tahoe) o posterior** en un Mac con **Apple Silicon** y que **Apple Intelligence** está **activado** en Ajustes del Sistema. Si Apple Intelligence no está disponible, estas funciones se ocultan (el resto de la app sigue funcionando).

**`git difftool` no abre Uranium Diff.**
Reinstala el helper desde **«Fusión ▸ Integración con Git…»** y verifica que `uraniumdiff` esté en tu **PATH**. Esa pantalla también incluye los comandos para configurarlo manualmente desde la Terminal.

**La app no puede abrir una carpeta o un archivo.**
Uranium Diff funciona dentro del **sandbox** de macOS y solo accede a lo que tú autorizas. Vuelve a seleccionar (autorizar) la carpeta o el archivo desde la app.

**Veo caracteres extraños o "mojibake".**
Probablemente el archivo no está en **UTF-8** (codificación aún no soportada).

**La descarga desde una URL falla.**
La URL debe ser **HTTP/HTTPS** y el archivo accesible públicamente; hay un límite de **50 MB**.

**Mi prueba de 14 días terminó.**
La app sigue funcionando en el **plan Free**. Para recuperar las funciones Pro, suscríbete desde la pantalla de Uranium Diff Pro.

**¿Sigue sin resolverse?**
Escríbenos: [Soporte y reporte de errores]({{ '/es/soporte/' | relative_url }}).
