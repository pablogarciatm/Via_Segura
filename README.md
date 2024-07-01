# Vía Segura: Análisis de datos para la seguridad vial en Barcelona

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar los accidentes de tráfico en la ciudad de Barcelona utilizando técnicas de analítica de datos y machine learning. El propósito es identificar patrones y factores de riesgo, predecir la gravedad de los accidentes y realizar una segmentación de los datos para obtener una comprensión más detallada del problema. 

## Estructura del Repositorio

La estructura del repositorio es la siguiente:

- **Carpetas**:
  - **Main**:
    - `Análisis de variables.ipynb`: Contiene el análisis exploratorio de los datos de accidentes, incluyendo visualizaciones y estadísticas descriptivas.
    - `Clustering.ipynb`: Realiza un análisis de segmentación (clustering) para identificar grupos de accidentes con características similares.
    - `Machine Learning.ipynb`: Desarrolla modelos de clasificación supervisada para predecir la gravedad de los accidentes.
  - **data**:
    - `clean.zip`: Archivos CSV preprocesados listos para el análisis.
    - `origen.zip`: Archivos CSV sin procesar descargados de [datos.gob.es](https://datos.gob.es).
    - `Limpieza de datos.ipynb`: Proceso de limpieza y preprocesamiento de los datos antes de su análisis.
  - **subsidiary**:
      Contiene notebooks secundarios en los que se realizan análisis específicos adicionales.
- **Informe**:
  - `Vía Segura. Análisis de datos para la seguridad vial en Barcelona.pdf`
    
## Propósito

El propósito de este proyecto es doble:

1. **Mejorar la Seguridad Vial**: Al identificar patrones y factores que contribuyen a los accidentes, se pueden proponer medidas preventivas y mejoras en la infraestructura urbana para reducir la incidencia y gravedad de los accidentes.
2. **Promover el Uso de Datos Abiertos**: Este proyecto muestra el valor de utilizar datos abiertos para realizar análisis que beneficien a la comunidad, demostrando cómo las iniciativas de datos abiertos pueden contribuir al desarrollo de soluciones innovadoras.

## Librerías Utilizadas

Este proyecto hace uso de diversas librerías de Python para el análisis y modelado de datos:

- **Pandas** y **NumPy**: Para la manipulación y análisis de datos.
- **Matplotlib**, **Seaborn** y **Folium**: Para la visualización de datos.
- **Scikit-learn**: Para la implementación de algoritmos de machine learning.
- **TensorFlow**: Para la construcción de redes neuronales.
- **XGBoost** y **LightGBM**: Para modelos de boosting.

## Consideraciones Éticas y Legales

Se ha tenido especial cuidado en la gestión ética y legal de los datos utilizados en este proyecto. Los datos provienen de fuentes abiertas y han sido anonimizados para cumplir con las normativas de privacidad y protección de datos, como el Reglamento General de Protección de Datos (RGPD) de la Unión Europea.

## Impacto Social

Este proyecto contribuye a varios Objetivos de Desarrollo Sostenible (ODS):

- **Salud y Bienestar (ODS 3)**: Mejora la seguridad vial y reduce la mortalidad y lesiones por accidentes de tráfico.
- **Ciudades y Comunidades Sostenibles (ODS 11)**: Ayuda en la planificación y mejora de la infraestructura urbana.
- **Acción por el Clima (ODS 13)**: Reduce la congestión y las emisiones al mejorar la fluidez del tráfico.
- **Alianzas para Lograr los Objetivos (ODS 17)**: Fomenta la colaboración entre entidades públicas, privadas y académicas para el uso de datos abiertos.

## Contribución

Se invita a la comunidad a contribuir con mejoras, correcciones y nuevas ideas para el proyecto. Se agradece cualquier feedback y sugerencia a través de los issues y pull requests en este repositorio.

---

Para más detalles sobre cada uno de los notebooks y su propósito específico, por favor revisa los archivos individuales y sus comentarios internos.

¡Gracias por tu interés en el proyecto!
