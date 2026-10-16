# Costos 3D — PWA

Calculadora gratuita y sin backend para presupuestos de impresión 3D. Todos los cálculos se ejecutan en el navegador. Los ajustes y el historial se guardan localmente (localStorage) en cada dispositivo.

## Publicar en GitHub Pages

1. Creá un repositorio público en GitHub, por ejemplo `costos-3d`.
2. Subí **los archivos que están dentro de esta carpeta**, no el ZIP ni la carpeta contenedora, a la raíz del repositorio. Podés usar `Add file` → `Upload files`.
3. Entrá a `Settings` → `Pages` → `Build and deployment` → `Deploy from a branch` → `main` → `/ (root)` → `Save`.
4. Esperá a que GitHub Pages publique la URL `https://TU-USUARIO.github.io/costos-3d/`.
5. En iPhone abrí esa URL con Safari → Compartir → `Agregar a pantalla de inicio` → `Agregar`.

## PDF

El botón `Guardar como PDF` abre el diálogo de impresión. En iOS, expandí la miniatura de vista previa con dos dedos y usá Compartir → Guardar en Archivos. En computadoras elegí `Guardar como PDF` como impresora.

## Notas

- No requiere claves, hosting pago ni servidor.
- Para instalar la PWA y activar el modo sin conexión necesitás servirla por HTTPS (GitHub Pages lo hace).
- No sincroniza historial entre dispositivos; borrar los datos del sitio elimina el historial.
- La potencia configurada es una estimación de consumo promedio, no una medición real.
