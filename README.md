## Dashboard de Indicadores Urbanos, Económicos y Culturales — Guadalajara (Ene–Jun 2025)

## Descripción de proyectos

### 🔹 Descripción Breve
Reporte en **Power BI Desktop (.pbix)** para visualizar y analizar indicadores de tres ejes: **Urbano, Económico y Cultural**, con navegación por páginas y filtros temporales.

### 🔹 Tecnologías Utilizadas
- **Power BI Desktop** (reporte `.pbix`)
- **DAX** (medidas e indicadores)
- **Power Query (M)** (transformación y preparación de datos)
- **Modelo tabular** (DataModel embebido en PBIX)
- **Visualizaciones y segmentadores** (slicers, tarjetas, tablas, gráficos)
- **GitHub** (control de versiones y documentación)

### 🔹 Responsabilidades Clave
- Diseñé un reporte con estructura por páginas: **HOME, URBANO, ECONOMICO, CULTURAL**.
- Modelé y organicé entidades para análisis, incluyendo **Calendario** para filtrado por **Mes**.
- Construí medidas e indicadores para el eje **Urbano** (p. ej., pasajeros, kilómetros, ingresos y ratios como ingreso por km/pasajero).
- Implementé análisis del eje **Económico** (unidades, actividades, % acumulado y ranking por aportación).
- Implementé análisis del eje **Cultural** (espacios culturales, distribución por tipo, habitantes por indicador y porcentajes).
- Configuré segmentadores y navegación para explorar insights por tema y periodo.
- Documenté el proyecto para facilitar su uso y despliegue en repositorio.

### 🔹 Impacto / Logros
- Centralicé en un solo reporte el seguimiento de **tres ejes** (Urbano/Económico/Cultural), reduciendo la dispersión de información.
- Estandaricé el análisis temporal con una tabla **Calendario**, facilitando comparaciones por mes.
- Mejoré la lectura de indicadores con métricas derivadas (ratios) y navegación por secciones para exploración más rápida.
- Dejé el proyecto listo para versionado en GitHub con estructura simple y documentada.

# Diccionario de datos (resumen)

## Tablas principales
### Calendario
- **Propósito:** soporte de filtros temporales (por ejemplo, Mes).
- **Campos clave:** `Mes` (usado como segmentador).

### Eje Urbano
- **Tabla:** `eje_urbano_usuarios_transporte_urbano_guadalajara_enero_junio_2025`
- **Campos/medidas usados en visuales:** Pasajeros, Kilómetros, Ingresos, Transporte (categoría).
- **Indicadores derivados comunes:** ingresos por km, ingresos por pasajero, pasajeros por km.

### Eje Económico
- **Tabla:** `eje_economico`
- **Campos clave:** `Actividad`, `Unidades`
- **Indicadores comunes:** conteo de actividades, % acumulado, unidades por actividad.

### Eje Cultural
- **Tablas:** `eje_cultural_Espacios culturales` y `eje_culturalHabporBilbioteca,Librería, MyTe`
- **Campos clave:** `Tipo_Espacio`, `Cantidad`, indicadores de habitantes/porcentaje.
- **Indicadores comunes:** total de espacios culturales, distribución por tipo, habitantes por indicador.

## Notas
- Este documento resume lo visible desde el reporte. Si cambian las fuentes o el modelo, actualiza este diccionario.


## Vista del Dashboard

### HOME
![HOME](docs/screenshots/home.png)

### URBANO
![URBANO](docs/screenshots/urbano.png)

### ECONÓMICO
![ECONOMICO](docs/screenshots/economico.png)

### CULTURAL
![CULTURAL](docs/screenshots/cultural.png)

---
