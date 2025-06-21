# 📦 SerialInsight

SerialInsight es una herramienta interna que permite consultar y exportar datos de prueba de producción (System ID, serial, tiempos y estatus) desde archivos almacenados en nuestro servidor, según modelo y fecha seleccionados. Genera un reporte ordenado en Excel con formato visual optimizado.

## 🎯 Características

- ✅ Interfaz gráfica simple e intuitiva
- 📁 Conexión automática a nuestro servidor
- 📌 Filtrado por modelo, System ID y fecha específica
- 🔍 Extracción de datos: PPID, System ID, status, hora de inicio y fin
- 📊 Exportación ordenada y automatica a Excel
- 📆 Cálculo de diferencia entre pruebas en minutos para optimizar procesos

## 📷 Interfaz

![image](https://github.com/user-attachments/assets/3129d155-a5a1-4ea2-9ef9-47f5eb8ed229)


## 🧰 Requisitos

- Windows con Microsoft Excel instalado
- Acceso a la red y permisos para montar la carpeta UNC

## 🗂️ Estructura

- `SerialInsight.ahk`: Script principal de la herramienta.
- `temporal/`: Carpeta temporal generada automáticamente para manejar los archivos intermedios.

## 📝 Licencia

Este proyecto está bajo la [Licencia MIT](LICENSE).

## 🙋 Autor

**Jose Alejandro**  
Foxconn México · Proyecto personal para portafolio
