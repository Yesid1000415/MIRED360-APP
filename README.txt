# MIRED360 APP — versión lista para publicar/probar

Contenido:
- `index.html`: pantalla principal de la app.
- `styles.css`: diseño responsive móvil.
- `app.js`: catálogo, filtros y mensajes de WhatsApp.
- `manifest.webmanifest` + `sw.js`: instalación como PWA.
- `assets/plans/`: 12 piezas optimizadas del catálogo.

## Flujo comercial
Cliente → elige plan → VALIDAR COBERTURA → WhatsApp 322 943 2085 → mensaje con plan + Ciudad + Barrio + Dirección.

## Regla comercial aplicada
El plan de $65.900 está incluido, pero no está marcado como recomendado ni destacado.

## Para Google Play
Esta carpeta es la app web/PWA lista para alojarse. Google Play requiere empaquetarla como Android App Bundle (AAB). La forma más limpia es publicar primero esta versión en HTTPS y luego crear el contenedor Android/TWA o Capacitor con el mismo diseño. El AAB debe firmarse con la clave de publicación de tu cuenta de Play Console; por seguridad esa clave no se incluye en este paquete.

## Importante
La app se identifica como MIRED360 y presenta Claro como operador comercializado. Incluye una aclaración de que no es la aplicación oficial de Claro. Antes de publicar, confirma que el uso de marca/logotipo corresponde a las autorizaciones de tu relación comercial.
