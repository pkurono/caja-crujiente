# Caja Crujiente (PWA)

App de ventas para papitas, maní y tostones. Funciona sin internet y guarda los datos **en el teléfono**. No depende de ninguna cuenta.

## Archivos
- `index.html`: la app
- `manifest.webmanifest`: nombre, ícono y colores para instalarla
- `sw.js`: permite usarla sin internet
- `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`: íconos

## Publicarla gratis

### Opción A: Netlify Drop (2 minutos)
1. Entra a https://app.netlify.com/drop desde la computadora.
2. Arrastra la carpeta `caja-crujiente-pwa` completa.
3. Te da un enlace `https://algo.netlify.app`. Crea una cuenta gratis para que no se borre y para cambiarle el nombre.

### Opción B: GitHub Pages
1. Crea un repositorio público, por ejemplo `caja-crujiente`.
2. Sube estos archivos a la raíz del repositorio.
3. Ve a Settings → Pages → Source: rama `main`, carpeta `/ (root)` → Save.
4. En un minuto queda en `https://TU-USUARIO.github.io/caja-crujiente/`.

## Instalarla en el teléfono
- **Android (Chrome):** abre el enlace, toca el botón **Instalar** de la app o ⋮ → *Instalar app*.
- **iPhone (Safari):** botón Compartir → *Agregar a pantalla de inicio*.

Después de abrirla una vez con internet, funciona sin conexión.

## Respaldo (importante)
Los datos viven solo en ese teléfono. En **Reportes → Respaldo → Crear respaldo** se genera un archivo `.json`. Mándalo a WhatsApp, Drive o tu correo. Con **Restaurar** lo cargas en otro teléfono. Hazlo al menos una vez por semana.

## Actualizar la app
Si cambias `index.html`, sube también `sw.js` con la versión aumentada (`cc-v1` → `cc-v2`). La próxima vez que abras la app con internet, toma la nueva versión. Tus datos se mantienen.

## Convertirla en APK (opcional)
Con la app ya publicada, entra a https://www.pwabuilder.com, pega el enlace y descarga el paquete de Android.
