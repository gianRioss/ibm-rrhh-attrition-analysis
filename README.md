# 🧠 Employee Attrition Analysis - IBM HR Analytics (Synthetic Dataset)

Este proyecto implementa un análisis exploratorio y predictivo sobre un conjunto de datos sintéticos provisto por IBM, enfocado en la comprensión de los factores asociados a la deserción voluntaria de empleados.

---

## 🎯 Objetivos del Proyecto

- Analizar variables personales y laborales asociadas a la deserción (edad, departamento, satisfacción, viajes, etc.).
- Visualizar patrones relevantes mediante gráficos estadísticos.
- Preprocesar datos categóricos para su uso en modelos predictivos.
- Entrenar y evaluar un modelo de clasificación (árbol de decisión) para predecir la probabilidad de renuncia.
- Generar un informe automático en HTML para entender la distribución y calidad de los datos.

---

## 📁 Contenido del Repositorio

| Archivo                         | Descripción                                                        |
|--------------------------------|--------------------------------------------------------------------|
| `RRHH_Proyecto_Completo.ipynb` | Notebook completo con análisis, visualizaciones y modelado.        |
| `RR-HH.xlsx`                   | Dataset original de IBM con datos sintéticos.                      |
| `reporte.html`                | Informe exploratorio automático generado con YData Profiling.     |

---

## ⚙️ Tecnologías y Herramientas

- **Python**: análisis de datos y machine learning.
- **pandas / numpy**: manipulación y limpieza de datos.
- **matplotlib / seaborn**: visualización de datos.
- **scikit-learn**: entrenamiento y evaluación de modelos.
- **ydata-profiling**: generación automática de informes HTML.
- **Google Colab**: entorno de desarrollo basado en la nube.
- **GitHub**: versionado y publicación del proyecto.

---

## 🚀 Cómo Ejecutar el Proyecto

1. Abrir el archivo `RRHH_Proyecto_Completo.ipynb` desde Google Colab o Jupyter Notebook.
2. Subir el archivo `RR-HH.xlsx` al entorno si no está cargado.
3. Ejecutar todas las celdas para reproducir análisis, gráficos y modelo.
4. Para visualizar el informe, abrir `reporte.html` en un navegador web.

---

## 📊 Visualizaciones Generadas

- Boxplot de edad por estado de deserción (`Attrition`).
- Distribución por género, departamento, viajes y satisfacción.
- Matriz de correlación entre variables numéricas.
- Reporte interactivo en HTML generado automáticamente.

---

## 🧠 Resultados y Conclusiones

- Se identificaron factores clave vinculados a la deserción laboral como la frecuencia de viajes, rol dentro de la empresa y balance vida-trabajo.
- El modelo de árbol de decisión entrenado alcanza métricas adecuadas para tareas iniciales de clasificación.
- El informe `reporte.html` evidenció correlaciones altas entre variables como edad, años de experiencia, ingresos y niveles jerárquicos.
- Este análisis puede ayudar a equipos de RRHH a tomar decisiones informadas basadas en datos.

---

## 📌 Fuente del Dataset

- IBM HR Analytics Employee Attrition & Performance Dataset (disponible públicamente para fines educativos).

---

> 📍 Proyecto desarrollado por **Gianmarco Ríos** como parte de su portfolio profesional en Ciencia de Datos e Inteligencia Artificial.
