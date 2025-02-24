# Herramienta de Archivo de Registros

Esta es una herramienta CLI para comprimir y archivar registros en un sistema Unix. La herramienta toma un archivo o directorio de registros como argumento, lo comprime en un archivo `.tar.gz`, y lo almacena en un directorio de archivos con la fecha y hora en el nombre del archivo.

---

## Tabla de Contenidos

1. [Requisitos](#requisitos)
2. [Instalación](#instalación)
3. [Uso](#uso)
4. [Ejemplos](#ejemplos)


---

## Requisitos

- Un sistema operativo basado en Unix (Linux, macOS, etc.).
- Bash (v4.0 o superior).
- Permisos de lectura en el directorio o archivo de registros.

---

## Instalación

1. Clona este repositorio o descarga el script `log-archive`:
   ```bash
   git clone [https://github.com/borizsam/Archivar-registros.git](https://github.com/borizSam/Archivar-registros.git)

2. Navega al directorio del proyecto:

    ```bash
    cd log-archive-tool
3. Haz que el script sea ejecutable:

    ```bash
    chmod +x log-archive
## Uso

4. Ejecuta la herramienta proporcionando un archivo o directorio de registros como argumento:

    ```bash
    ./log-archive <archivo-o-directorio>
## Argumentos

- `<archivo-o-directorio>`: Ruta al archivo o directorio de registros que deseas comprimir.

## Ejemplos

### Comprimir un archivo de registro:

    ./log-archive /var/log/auth.log

### Comprimir un directorio de registros:

    ./log-archive /var/log

## Verificar el archivo comprimido

Después de ejecutar el script, el archivo comprimido se almacenará en el directorio `logs_archive`. Puedes listar los archivos con:

    ls logs_archive/



