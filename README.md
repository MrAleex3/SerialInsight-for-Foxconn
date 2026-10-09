# SerialInsight (AutoHotkey)

Herramienta interna que permite consultar y exportar datos de prueba de producción (System ID, serial, tiempos y estatus) desde los archivos almacenados en el servidor, según el modelo y la fecha seleccionados. Genera un reporte ordenado en Excel con formato.

![Interfaz](https://github.com/user-attachments/assets/3129d155-a5a1-4ea2-9ef9-47f5eb8ed229)

## Características

- Interfaz gráfica simple.
- Conexión automática al servidor.
- Filtrado por modelo, System ID y fecha específica.
- Extracción de PPID, System ID, status, hora de inicio y fin.
- Exportación ordenada y automática a Excel.
- Cálculo de la diferencia entre pruebas en minutos.

## Requisitos

- Windows con Microsoft Excel instalado.
- Acceso a la red y permisos para montar la carpeta UNC.

## Estructura

- `SerialInsight.ahk`: script principal de la herramienta.
- `temporal/`: carpeta temporal que se genera automáticamente para los archivos intermedios.

## Licencia

Copyright (c) 2026 Jose Espinoza. Todos los derechos reservados. Este proyecto es propietario y confidencial; consulta el archivo [LICENSE](LICENSE) para los términos de uso.

## Autor

Alejandro Espinoza
Foxconn México
