# Instrucciones de ejecución para el proyecto Docker-Compose

## Descripción

Este proyecto utiliza `docker-compose` para orquestar múltiples servicios, incluyendo una aplicación web, una base de datos PostgreSQL, un servicio Redis, un procesador por lotes y un worker.

## Pre-requisitos

- Tener instalado Docker y Docker-Compose en tu máquina.
- Clonar este repositorio o asegurarte de tener el archivo `docker-compose.yml` en tu directorio de trabajo.

## Pasos para ejecutar

1. **Configura tus variables de entorno**: Antes de iniciar los servicios, asegúrate de que las rutas en los volúmenes, como `"$HOME/file_conversor/uploaded/"`, existan y tengan los permisos adecuados.

2. **Levanta los servicios con Docker-Compose**:
   ```bash
     docker-compose up -d
   ```

3. **Verifica el estado de los servicios**:

   ```bash
     docker-compose ps
   ```


