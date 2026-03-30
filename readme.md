# Taller Módulo 1 — Salud Mundial

**Autora:** Laura Camila Parra Martínez  
**Máster:** IA & Data Science — DevSeniorCode  
**Fecha de entrega:** 29 de marzo de 2024

---

## Descripción

Este proyecto analiza indicadores de salud de 159 países usando Python y Pandas. El objetivo es explorar, limpiar y extraer conclusiones a partir de datos reales de salud mundial, aplicando las herramientas vistas en el Módulo 1: Python, Pandas, Git & GitHub y documentación.

---

## Dataset

El archivo `salud_mundial.csv` contiene **159 países** con **13 columnas** de indicadores de salud:

| Columna | Descripción |
|---|---|
| `pais` | Nombre del país |
| `region` | Continente o región geográfica |
| `nivel_ingresos` | Nivel económico: Low, Medium, High, Very High |
| `esperanza_vida` | Esperanza de vida al nacer (años) |
| `gasto_salud_usd` | Gasto per cápita en salud (USD/año) |
| `mortalidad_infantil` | Muertes por cada 1,000 nacidos vivos |
| `medicos_por_1000` | Médicos por cada 1,000 habitantes |
| `poblacion_urbana_pct` | % de población en zonas urbanas |
| `obesidad_pct` | % de la población con obesidad |
| `diabetes_pct` | % de la población con diabetes |
| `tabaquismo_pct` | % de fumadores |
| `camas_hospital_por_1000` | Camas hospitalarias por 1,000 hab. |
| `vacunacion_pct` | % de cobertura de vacunación |

> El dataset presenta valores nulos en algunas columnas (por ejemplo, 10 en `mortalidad_infantil` y 9 en `medicos_por_1000`), los cuales fueron tratados durante el análisis.

---

## Cómo ejecutar

1. Clona el repositorio:
   ```bash
   git clone https://github.com/parramlaurac/Taller-final-M-dulo-1---Salud-Mundial.git
   ```
2. Entra a la carpeta del proyecto:
   ```bash
   cd Taller-final-M-dulo-1---Salud-Mundial
   ```
3. Instala las dependencias:
   ```bash
   pip install pandas jupyter
   ```
4. Ejecuta el notebook:
   ```bash
   jupyter notebook taller_modulo1.ipynb
   ```

---

## Hallazgos principales

- **Hallazgo 1:** Los países con gasto en salud alto (≥ $1,000 USD) tienen una esperanza de vida promedio de **$4,646.9 USD**, más de 22 veces superior al gasto de los países con esperanza de vida baja ($207.0 USD), lo que confirma una relación directa entre inversión en salud y años de vida.

- **Hallazgo 2:** Europa es la región con mayor esperanza de vida promedio (**79.5 años**), mientras que África tiene la menor (**63.2 años**), una diferencia de más de 16 años entre regiones.

- **Hallazgo 3:** El dataset tiene valores nulos en columnas clave como `mortalidad_infantil` (10 nulos) y `medicos_por_1000` (9 nulos), lo que indica que los datos de salud en países de bajos ingresos suelen estar incompletos.

---

## Tecnologías

Python · Pandas · Jupyter Notebook · Git · GitHub
