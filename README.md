# Gestión y Configuración del Sistema Operativo Windows

Este repositorio contiene material relacionado con la gestión y configuración de sistemas operativos Windows mediante comandos y herramientas gráficas. El objetivo es adquirir habilidades prácticas en la administración del sistema.

## 📌 Objetivo

Que los estudiantes desarrollen habilidades prácticas en la gestión y configuración de sistemas operativos Windows mediante comandos y herramientas gráficas.

## 📂 Entregables

Cada estudiante deberá entregar un informe detallado con capturas de pantalla y explicaciones de cada paso realizado en cada actividad.

## 📝 Actividades

### 🔹 Actividad 1: Comparación de Sistemas de Archivos

**Objetivo:** Identificar y comparar los sistemas de archivos en Windows y otros sistemas operativos.

#### 📌 Instrucciones:
- Investigar las diferencias entre NTFS, FAT32 y exFAT en cuanto a seguridad, tamaño de archivos y compatibilidad.
- Usar `diskmgmt.msc` (Administración de discos) para verificar qué sistema de archivos usan el disco local y las unidades externas conectadas.
- Formatear una memoria USB en los tres sistemas de archivos y anotar las diferencias en compatibilidad y funcionalidad.

#### 📄 Entregable:
- Informe con una tabla comparativa entre NTFS, FAT32 y exFAT.
- Capturas de pantalla de la administración de discos y pruebas realizadas con la memoria USB.

### 🔹 Actividad 2: Estructura y Función de Directorios del Sistema

**Objetivo:** Analizar y comprender la estructura de directorios en Windows.

#### 📌 Instrucciones:
- Explorar los directorios principales del sistema (`C:\Windows`, `C:\Program Files`, `C:\Users`) y documentar su función.
- Usar `cmd` para listar su contenido (`dir /s`).
- Identificar archivos de configuración del sistema (`.ini`, `.log`, `.dll`).

#### 📄 Entregable:
- Informe con la descripción de cada directorio principal y su función.
- Capturas de pantalla de la estructura de archivos.

### 🔹 Actividad 3: Localización de Información en el Sistema

**Objetivo:** Aprender a buscar información en el sistema operativo usando herramientas gráficas y comandos.

#### 📌 Instrucciones:
- Usar el Explorador de archivos para buscar un archivo específico y aplicar filtros de búsqueda.
- Usar los comandos `where` y `findstr` en `cmd` para encontrar archivos y contenido dentro de archivos de texto.
- Usar el Administrador de tareas (`Ctrl + Shift + Esc`) para identificar procesos en ejecución.

#### 📄 Entregable:
- Capturas de pantalla de las búsquedas realizadas y análisis sobre cuál método fue más eficiente.

### 🔹 Actividad 4: Creación de Particiones y Unidades Lógicas

**Objetivo:** Gestionar discos y particiones en Windows.

#### 📌 Instrucciones:
- Abrir `diskmgmt.msc` y crear una nueva partición en un disco con espacio no asignado.
- Formatear la partición en NTFS y asignarle una letra.
- Convertir un disco en volumen dinámico.

#### 📄 Entregable:
- Informe con capturas de pantalla del proceso de particionamiento y una reflexión sobre su utilidad.

### 🔹 Actividad 5: Realización y Restauración de Copias de Seguridad

**Objetivo:** Configurar copias de seguridad y restaurar archivos en Windows.

#### 📌 Instrucciones:
- Usar `Panel de Control > Copia de Seguridad y Restauración` para hacer una copia de seguridad en una unidad externa.
- Eliminar un archivo y restaurarlo desde la copia de seguridad.

#### 📄 Entregable:
- Capturas de pantalla del proceso de respaldo y restauración con una explicación de los pasos realizados.

### 🔹 Actividad 6: Planificación y Automatización de Tareas

**Objetivo:** Automatizar tareas en Windows.

#### 📌 Instrucciones:
- Usar `taskschd.msc` para crear una tarea programada que abra una aplicación a una hora específica.
- Programar el apagado automático del equipo con `shutdown /s /t 3600`.

#### 📄 Entregable:
- Capturas de pantalla de la configuración de tareas y descripción de su utilidad.

### 🔹 Actividad 7: Instalación y Evaluación de Utilidades de Gestión

**Objetivo:** Probar herramientas de gestión del sistema.

#### 📌 Instrucciones:
- Investigar y descargar una herramienta gratuita de monitoreo del sistema (Ej: `HWMonitor`, `CCleaner`).
- Analizar su funcionalidad y generar un reporte del estado del sistema.

#### 📄 Entregable:
- Capturas de pantalla de la herramienta en uso y una evaluación de sus funciones.

### 🔹 Actividad 8: Configuración de Cuentas y Seguridad

**Objetivo:** Gestionar usuarios y grupos en Windows.

#### 📌 Instrucciones:
- Crear una nueva cuenta de usuario con permisos estándar.
- Asignar una contraseña segura y configurar políticas de contraseña con `gpedit.msc`.
- Usar `net user` en `cmd` para modificar cuentas de usuario.

#### 📄 Entregable:
- Capturas de pantalla de la configuración de cuentas y explicación de la importancia de la seguridad de usuarios.

### 🔹 Actividad 9: Administración de Servicios y Procesos

**Objetivo:** Identificar y gestionar procesos y servicios en Windows.

#### 📌 Instrucciones:
- Usar `services.msc` para listar servicios en ejecución.
- Detener e iniciar un servicio (Ejemplo: Spooler de impresión).
- Usar `taskkill` en `cmd` para cerrar procesos específicos.

#### 📄 Entregable:
- Informe con capturas de pantalla y explicación de los cambios realizados.

### 🔹 Actividad 10: Protección y Monitorización del Sistema

**Objetivo:** Aplicar seguridad en accesos y monitorear el sistema.

#### 📌 Instrucciones:
- Configurar permisos en carpetas (`Propiedades > Seguridad`).
- Activar el Firewall de Windows y verificar sus reglas.
- Usar `eventvwr.msc` (Visor de eventos) para revisar logs del sistema.

#### 📄 Entregable:
- Capturas de pantalla y un análisis de los eventos detectados.

## 📬 Contacto

Si tienes alguna pregunta o sugerencia, puedes encontrarme en GitHub como [ceeciimg](https://github.com/ceeciimg).

