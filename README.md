<img width="1280" height="640" alt="WhatsApp Image 2026-11-17 at 3 00 46 PM (2)" src="https://github.com/user-attachments/assets/ef0a04cf-9d3c-4fa6-960e-fad33c41de07" />

# 🎧 Análisis de Hábitos de Consumo Musical (Springfield vs. Shelbyville)

## 📋 Descripción
Una plataforma de streaming musical buscaba comprender a profundidad el comportamiento de escucha de sus usuarios en las ciudades de **Springfield** y **Shelbyville**. El proyecto se enfocó en descubrir patrones de consumo, brechas de actividad entre ciudades y tendencias semanales que sirvan como base para optimizar los sistemas de recomendación y personalizar la experiencia del usuario.

## 🎯 Objetivos
- ✅ Evaluar la calidad e integridad de los registros disponibles.
- ✅ Depurar y preparar el conjunto de datos para el análisis exploratorio.
- ✅ Comparar los niveles de actividad y hábitos de escucha entre Springfield y Shelbyville.
- ✅ Identificar variaciones en el consumo musical según el día de la semana.
- ✅ Analizar la distribución y preferencia de géneros musicales en la plataforma.
- ✅ Generar hallazgos accionables que respalden decisiones estratégicas basadas en datos.

## 🛠️ Herramientas y Habilidades Utilizadas
* **Lenguaje:** Python
* **Librerías:** Pandas
* **Entorno:** Jupyter Notebook
* **Formato de datos:** Archivos CSV
* **Técnicas:** Limpieza de datos, Estandarización de categorías y Análisis Exploratorio de Datos (EDA).

## 📊 Fuente de Datos
El estudio se desarrolló a partir del archivo `music_project_en.csv`, el cual registra el historial de reproducciones de los usuarios en la plataforma.

**Variables analizadas:**
* `user_id`: Identificador único del usuario.
* `track`: Título de la canción reproducida.
* `artist`: Nombre del artista o banda.
* `genre`: Género musical asociado.
* `city`: Ciudad de origen del usuario (Springfield o Shelbyville).
* `time`: Hora exacta de la reproducción.
* `day`: Día de la semana en que ocurrió la actividad.

## ⚙️ Metodología
1. **Exploración inicial:** Inspección de la estructura general, tipos de datos y calidad de la información.
2. **Saneamiento de datos:** Identificación y tratamiento de valores ausentes, además de la eliminación de registros duplicados.
3. **Normalización:** Corrección de inconsistencias y duplicados implícitos en los nombres de los géneros musicales.
4. **Análisis comparativo:** Evaluación de la actividad de escucha cruzando ciudad y día de la semana.
5. **Validación:** Comprobación de hipótesis y consistencia de los resultados obtenidos.

## 💡 Principales Hallazgos
* **Saneamiento crítico:** Se detectaron y corrigieron valores faltantes en columnas clave (`artist`, `track`, `genre`) y se eliminaron duplicados que distorsionaban las métricas.
* **Liderazgo de Springfield:** Springfield registró un volumen de reproducciones significativamente mayor al de Shelbyville en todos los días evaluados.
* **Tendencia de fin de semana:** Ambas ciudades experimentaron un repunte moderado en la actividad de escucha durante los viernes.
* **Diversidad musical:** La plataforma alberga una amplia variedad de géneros, reflejando perfiles de consumo muy heterogéneos.
* **Impacto de la estandarización:** Unificar las etiquetas de géneros musicales permitió obtener métricas limpias y confiables.

## 📂 Archivos Principales
* `Gamma_music_consumption_analysis.ipynb`
* `music_project_en.csv`

## 🏁 Conclusión
Este análisis permitió trazar una radiografía precisa sobre cómo consumen música los usuarios de Springfield y Shelbyville. Tras limpiar y estandarizar el dataset, se confirmó que Springfield mantiene una actividad superior de forma constante y que el consumo tiende a subir hacia el cierre de la semana en ambas localidades. Estos resultados proporcionan una base sólida para afinar los algoritmos de recomendación y diseñar estrategias de contenido segmentadas por ubicación y día.
