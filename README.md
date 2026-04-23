
# Trabajo Final Integrador
# Curso Herramientas Basicas para el Analisis de datos
# Universidad Tecnológica Nacional

## Alumna
Mariana Barone

## Comision y fecha
Comisión 999201624
Abril 2026

## Repositorio de GitHub del Proyecto
https://github.com/marianalbh/herramientasbasicas_barone-mariana

## Titulo del proyecto
Analisis de Datos de Dengue en Argentina

## Descripcion del Proyecto
Este proyecto explora la vigilancia de casos de dengue y Zika en Argentina, utilizando datos epidemiologicos de 2024, 2025 y principios de 2026. El objetivo principal es identificar patrones temporales, grupos de edad de riesgo y las provincias/departamentos con mayor cantidad de casos para informar estrategias de prevencion y control.
A partir de un dataset con más de 38000 registros, se aplicaron técnicas de limpieza, análisis exploratorio y visualización en Python, y se elaboró un dashboard en Power BI.

## Conjuntos de datos utilizados
Los datos son dos archivos .csv provienentes del Portal de Datos Argentina y el Sistema Nacional de Vigilancia de la Salud 2.0 (SISA). 
- [Vigilancia de Dengue y Zika (SE 1-52, 2024-2025)](https://datos.salud.gob.ar/dataset/vigilancia-de-dengue-y-zika/archivo/e57edd84-096d-4348-9137-2f5dae9c8f55)
- [Vigilancia de Dengue y Zika (SE 1-52, 2025 y SE 1-12, 2026)](https://datos.salud.gob.ar/dataset/vigilancia-de-dengue-y-zika/archivo/33e12e9f-1d14-4bc7-b34c-a1f88ab7b990)

Contienen 7 variables principales: departamento y provincia de residencia, anio de registro, semana epidemiologica del registro, grupo etario y cantidad de casos.

## Objetivos del proyecto
* Explorar la evolucion temporal de casos totales de dengue en Argentina a lo largo de las semanas epidemiologicas de los anios 2024 a 2026.
* Entender que grupo/s de edad son potencialmente mas propensos al contagio, independientemente de la informacion geografica, segun los anios registrados
* Identificar cuales provincias argentinas tuvieron una mayor cantidad de casos en los anios registrados. Analizar la distribucion de casos a lo largo de los departamentos de la provincia con mayor cantidad de casos.

## Conclusiones Clave
*  Los picos de casos de dengue en 2024 y 2025 ocurrieron entre las semanas epidemiologicas 12 y 14. Se recomienda reforzar medidas de prevencion antes de la semana 1, y aun antes en regiones como Chaco.
*  Los grupos etarios entre 25 y 65 anios muestran mayor propension al contagio, siendo el rango de 45 a 65 anios el de mayor incidencia. Se sugiere considerar programas de vacunacion para estos grupos.
*  Buenos Aires, Cordoba, Tucuman y Santa Fe son las provincias con mayor cantidad de casos. Dentro de Buenos Aires, los departamentos de La Matanza y Jose C. Paz presentan los numeros mas altos, requiriendo atencion especial.
*  Un analisis de prevalencia por provincia/departamento, incorporando datos demograficos, podria ofrecer una vision mas precisa de la carga de la enfermedad.

## Herramientas utilizadas
* Python (pandas, matplotlib, seaborn)
* Google Colab
* Power BI
* GitHub

## Dashboard
<img width="875" height="499" alt="image" src="https://github.com/user-attachments/assets/d7ac0612-6b40-4b94-9954-72fcd376fde8" />

## Archivos Generados
*   `dengue_data_procesada_2024.csv`: Dataset limpio y procesado de los casos de dengue de 2024.
*   `requirements.txt`: Archivo con las librerias de Python utilizadas en el proyecto.
*   `distribucion_casos_dengue.png`: Grafico de distribucion de la cantidad de casos.
*   `distribucion_casos_dengue_detalle.png`: Grafico de distribucion detallada para casos de alta cantidad.
*   `distribucion_temporal_dengue.png`: Grafico de evolucion temporal de casos por anio.
*   `distribucion_temporal_dengue_grupo-etario.png`: Grafico de casos por semana y grupo etario para 2024.
*   `distribucion_temporal_dengue_provincia.png`: Grafico de casos por semana y provincia para 2024.
*   `dengue_top10_BsAs.png`: Grafico de los 10 departamentos de Buenos Aires con mas casos.
*   `distribucion_temporal_dengue_departamentos-BsAs.png`: Grafico de casos por semana para los top 10 departamentos de Buenos Aires.

## Licencias
Este proyecto utiliza una base de datos bajo la licencia **Creative Commons Attribution 4.0 International (CC BY 4.0)**. Revisar archivo LICENSE.

## Autoria
(C) 2025 - Proyecto académico realizado por Mariana Barone
