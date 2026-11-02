# Stock FLiiTS

Página de acceso a la app de control de stock de FLiiTS.
El enlace lleva a la aplicación web de Google Apps Script, que pide iniciar sesión con una cuenta @fliits.com
y comprueba los permisos en la pestaña Usuarios del Google Sheet. Esta página no contiene datos.

## Configuración
1. En `index.html`, `URL_APP` contiene la URL de la implementación de Apps Script (termina en `/exec`). Si se crea una implementación nueva, actualízala ahí.
2. Settings > Pages > Source: *Deploy from a branch*, rama `main`, carpeta `/ (root)`.
3. La URL quedará como `https://<usuario-u-organizacion>.github.io/<repositorio>/`.
