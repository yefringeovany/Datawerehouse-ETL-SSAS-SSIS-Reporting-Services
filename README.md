# Proyecto de Data Warehouse con SSIS, SSAS, Reporting Services

Este proyecto consiste en la creación de un Data Warehouse utilizando **Microsoft Visual Studio** con la herramienta **SQL Server Integration Services (SSIS)**. El objetivo principal es integrar, transformar y cargar datos desde diversas fuentes hacia un entorno de almacenamiento optimizado para análisis.

## 📁 Descripción del Proyecto

El Data Warehouse fue desarrollado en dos fases principales:

1. **Control Flow (Flujo de Control):** Orquesta la ejecución de tareas secuenciales y paralelas como scripts, ejecuciones SQL y tareas de flujo de datos.
2. **Data Flow (Flujo de Datos):** Se encarga de la extracción, transformación y carga (ETL) de los datos desde distintas fuentes hacia destinos estructurados.

## 🛠 Tecnologías y Herramientas Utilizadas

- **Microsoft Visual Studio**
- **SQL Server Data Tools (SSDT)**
- **SSIS (SQL Server Integration Services)**
- **SQL Server Management Studio (SSMS)**
- **OLE DB Source/Destination**
- **Flat File Source**
- **Lookup, Sort, Conditional Split, Multicast, Union All**
- **Derived Column, Data Conversion**
- **Database Oracle**

## 📊 Flujo del Proyecto

### Flujo de Control:
- Tareas de script y SQL para preparación previa.
- Cargas condicionales y secuenciales de flujos de datos.
- Validaciones y controles de errores.

### Flujo de Datos:
- Integración de datos desde archivos planos y bases de datos.
- Conversión de tipos de datos con `Data Conversion`.
- Validaciones con `Lookup`, `Sort`, y `Conditional Split`.
- Envío de datos a múltiples destinos OLE DB, categorizados por condiciones.
- Manejo de errores y salidas no coincidentes para asegurar calidad de datos.

## 📷 Ejemplos Visuales

### Control Flow:
![Control Flow](./47a387b1-1118-4200-a2ec-28058d833c14.png)

### Data Flow:
![Data Flow](./0a7308d9-c888-4389-a516-b416e8bab62d.png)

## ✅ Objetivos Alcanzados

- Automatización del flujo ETL.
- Integración de múltiples fuentes de datos.
- Limpieza y transformación de datos de entrada.
- Consolidación en destinos estructurados para análisis futuro.

## 📌 Consideraciones

- Asegurarse de tener configuradas las conexiones OLE DB correctamente.
- Validar las rutas de los archivos planos si se utiliza un entorno diferente.
- Revisión de los logs de error para manejar salidas de error desde los `Lookup`.

## 📂 Estructura del Proyecto

