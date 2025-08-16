# classify-downloads

Este proyecto proporciona instaladores para la aplicación Classify en diferentes plataformas (Windows, Linux DEB, Linux RPM). El repositorio contiene los archivos necesarios para descargar e instalar la aplicación fácilmente.

## Estructura del proyecto

- `index.html`: Página principal para la descarga de instaladores.
- `latest.json`: Archivo JSON que contiene información sobre la última versión disponible.
- `windows/`: Carpeta con el instalador para Windows (`ClassifyInstaller-1.0.2-win32.exe`).
- `linux-deb/`: Carpeta con el instalador para distribuciones Linux basadas en DEB (`ClassifyInstaller-1.0.2-linux.deb`).
- `linux-rpm/`: Carpeta con el instalador para distribuciones Linux basadas en RPM (`ClassifyInstaller-1.0.2-linux.rpm`).

## Cómo usar

1. Accede a la página `index.html` para ver las opciones de descarga.
2. Descarga el instalador correspondiente a tu sistema operativo.
3. Sigue las instrucciones de instalación específicas para tu plataforma.

## Actualización de instaladores

- Para actualizar los instaladores, reemplaza los archivos en las carpetas correspondientes y actualiza `latest.json` con la información de la nueva versión.

## Licencia

Este proyecto está bajo la licencia que determine el propietario. Consulta con el autor para más detalles.
