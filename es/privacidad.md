---
title: "Política de privacidad"
lang: es
---

# Política de privacidad

**Última actualización:** 13 de julio de 2026 · **Aplica a:** Uranium Diff para macOS v1.0.0

**Resumen:** Uranium Diff **no recopila datos personales**, **no rastrea** y **no usa analítica**. El contenido de tus archivos se procesa **en tu Mac** y **nunca** se envía a nuestros servidores (de hecho, no tenemos servidores que reciban tu contenido).

### Datos que recopilamos
**Ninguno.** No creamos cuentas, no pedimos registro y no recopilamos datos personales, de uso ni identificadores. Esto coincide con la etiqueta "Datos no recopilados" (*Data Not Collected*) de la ficha de App Store y con el manifiesto de privacidad de la app.

### Tratamiento de tus archivos
El contenido de los archivos que comparas se procesa **localmente** en tu dispositivo para calcular y mostrar las diferencias. No se transmite a nosotros ni a terceros.

### Apple Intelligence (IA on-device)
Las funciones de IA (resúmenes, explicaciones, análisis de ramas) usan los **modelos locales de Apple (Foundation Models)** y se ejecutan **en tu Mac**. El contenido de tus archivos **no** sale del dispositivo para estas funciones.

### Uso de red
La app solo realiza conexiones salientes cuando **tú** lo inicias:
- **Descarga desde una URL** que tecleas (HTTP/HTTPS): el archivo se obtiene directamente de ese servidor.
- **Conexiones SSH** a los servidores que **tú** configuras: la comunicación es directa con ese host.

No hay servidor propio, ni telemetría, ni "llamadas a casa".

### Credenciales y almacenamiento local
- Las **credenciales SSH** se guardan exclusivamente en el **Llavero (Keychain)** de macOS.
- El acceso a carpetas se conserva mediante *security-scoped bookmarks* de macOS.
- Los archivos descargados de una URL o por SSH se guardan en una **caché temporal** que se borra al salir de la app.

### Sandbox y permisos
La app se ejecuta en el **App Sandbox** de macOS con permisos mínimos: lectura/escritura de archivos que **tú** seleccionas, acceso a la carpeta **Descargas** y cliente de **red saliente**. Solo accede a lo que autorizas explícitamente.

### Compras
Las suscripciones Pro se procesan a través de **Apple (App Store / StoreKit)**. **No** recibimos ni almacenamos datos de pago; la gestión de la suscripción ocurre con tu **Apple ID**. Consulta la [Política de privacidad de Apple](https://www.apple.com/legal/privacy/).

### Componentes de terceros
Uranium Diff incluye bibliotecas de código abierto (p. ej. resaltado de sintaxis y utilidades de archivo) que se ejecutan **localmente** y **no** transmiten datos.

### Menores
La app está clasificada **4+** y no recopila datos de ninguna persona, incluidos los menores.

### Cambios en esta política
Si actualizamos esta política, publicaremos la nueva versión en esta página con su fecha. Los cambios relevantes se reflejarán en las notas de la versión.

### Contacto
¿Dudas sobre privacidad? Escríbenos a **uraniumdiff@outlook.com**.
