# 📊 Análisis de Focalización del Programa de Becas Benito Juárez 

## 💡 Resumen del Proyecto

Este repositorio contiene el código fuente, los resultados y las visualizaciones generadas a partir del análisis de los microdatos de la **Encuesta Nacional de Ingresos y Gastos de los Hogares (ENIGH) 2022** de INEGI.

El objetivo principal de este proyecto es evaluar la **focalización** y la **cobertura** del programa de Becas Benito Juárez para Estudiantes de Educación Media Superior.

---

## 🎯 Preguntas Clave del Análisis

El proyecto aborda las siguientes preguntas analíticas, esenciales para evaluar la eficiencia del programa:

1.  **Perfil del Beneficiario:** ¿Cómo se distribuye el acceso a la beca por género, condición de discapacidad y pertenencia a pueblos indígenas?
2.  **Focalización Geográfica:** ¿Cuál es la tasa de penetración de las becas por entidad federativa (estado)?
3.  **Focalización Socioeconómica:** ¿Existe una correlación entre el ingreso trimestral del hogar y el acceso a la beca? (Mediana de ingreso de beneficiarios vs. no beneficiarios).

---

## 📈 Resultados Destacados

Los hallazgos clave del análisis de focalización fueron:

* **Focalización de Ingreso:** La mediana de ingreso trimestral del hogar de los beneficiarios ($\mathbf{\$1,643.47}$) fue **menor** que la mediana del total de estudiantes ($\mathbf{\$1,907.60}$), lo que sugiere una **correcta tendencia a la focalización** en hogares de bajos ingresos.
* **Inclusión Indígena:** Se observó una mayor tasa de acceso a la beca en la población que habla alguna lengua indígena.
* **Disparidad Regional:** El análisis identificó una alta heterogeneidad en la tasa de penetración de la beca entre los estados, destacando la necesidad de revisar los mecanismos de difusión en las entidades con menor cobertura.

---

## 💻 Estructura del Repositorio

| Archivo / Carpeta | Descripción |
| :--- | :--- |
| `analisis_becas.ipynb` | **El código principal.** Contiene todo el proceso de ETL, limpieza de datos, el cálculo de indicadores (ratios, medianas) y la generación de las visualizaciones (gráficos de barras y rankings). |
| `data/` | **(No incluido en el push)** Carpeta que contiene los microdatos originales de la ENIGH (archivos CSV, no subidos a GitHub por su tamaño). |
| `images/` | Contiene las visualizaciones de los resultados (ranking estatal, distribución por género, etc.). |
| `.gitignore` | Reglas para ignorar archivos grandes de datos (`.csv`, `.xlsx`), entornos virtuales (`venv/`) y archivos de caché. |

---

## 🛠️ Requisitos del Proyecto

Para replicar este análisis, necesitas tener instalados los siguientes paquetes en tu entorno Python:

pandas numpy matplotlib seaborn jupyter (o Visual Studio Code)
