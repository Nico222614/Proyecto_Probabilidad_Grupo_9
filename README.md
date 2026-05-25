# Análisis Estadístico Descriptivo del Mercado Laboral en la Provincia de Pichincha (2025)

Este repositorio contiene el desarrollo técnico del Proyecto Bimestral I para la asignatura de Probabilidad y Estadística Básica de la Escuela Politécnica Nacional. El estudio se centra en la caracterización y contraste de los ingresos laborales mensuales entre dos cohortes generacionales específicas mediante un enfoque estrictamente descriptivo.

## 1. Descripción del Proyecto

El objetivo de la investigación es determinar las diferencias estructurales en la distribución y variabilidad del ingreso laboral entre la población joven (18-29 años) y la población adulta (30-35 años) en la provincia de Pichincha. El análisis evalúa el impacto del nivel de instrucción alcanzado en relación con los umbrales de subsistencia económica vigentes en Ecuador para el año 2025, tales como el Salario Básico Unificado ($470) y la Canasta Familiar Básica (aprox. $780).

## 2. Metodología y Datos

El proyecto utiliza microdatos oficiales provenientes de la Encuesta Nacional de Empleo, Desempleo y Subempleo (ENEMDU) Anual 2025, administrada por el Instituto Nacional de Estadística y Censos (INEC).

### Procesamiento de Datos:
* Segmentación Geográfica: Filtrado exclusivo para la provincia de Pichincha (Código 17).
* Segmentación Etaria: Creación de subconjuntos independientes para jóvenes (18-29 años) y adultos (30-35 años).
* Normalización: Tratamiento de variables nulas y limpieza de la variable de ingresos (ingrl).
* Muestreo: Extracción de una muestra aleatoria balanceada de 1,000 registros por cada grupo para asegurar la simetría del análisis (N = 2,000).

## 3. Tecnologías Utilizadas

* Python: Procesamiento de datos y generación de gráficos descriptivos (Librerías: pandas, numpy, matplotlib, seaborn).
* LaTeX: Redacción y composición formal del informe técnico (Overleaf).
* GitHub: Control de versiones y almacenamiento de recursos digitales.

## 4. Estructura del Repositorio

* /Dataset_Jovenes_18_29.csv: Base de datos depurada del segmento joven.
* /Dataset_Adultos_30_35.csv: Base de datos depurada del segmento adulto.
* /analisis_descriptivo.ipynb: Script de procesamiento en Python (Google Colab).
* /Histograma_Comparativo.png: Distribución absoluta de frecuencias por grupo.
* /Ojiva_Relativa.png: Comparación de frecuencias relativas acumuladas.
* /Boxplot_Comparativo.png: Identificación de medidas de posición y detección de valores atípicos.

## 5. Hallazgos Principales

El estudio concluyó que existe una brecha salarial significativa del 19.3% en la mediana de ingresos a favor del segmento adulto. Se identificó una distribución leptocúrtica en la población joven, lo que evidencia una concentración masiva de salarios en torno al mínimo legal y una limitada movilidad económica. Las métricas de forma y dispersión ratifican que los ingresos en la provincia no siguen una distribución normal y están condicionados por la desigualdad estructural y la presencia de valores atípicos superiores.
