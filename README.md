# Capacitación Python UBPD

![Python](https://img.shields.io/badge/Python-3.10-blue)
![pandas](https://img.shields.io/badge/pandas-2.2.3-orange)
![openai](https://img.shields.io/badge/openai-1.54.4-blueviolet)
![faker](https://img.shields.io/badge/faker-32.1.0-yellowgreen)
![tqdm](https://img.shields.io/badge/tqdm-4.67.0-lightgrey)
![nltk](https://img.shields.io/badge/nltk-3.9.1-brightgreen)

**Versión:** 0.0.1   
**Autor:** [Analitica Subdirección de Gestión de información](mailto:czaineam@unidadbusqueda.gov.co)  

## Descripción
Este proyecto forma parte de una **masterclass de Python** diseñada para la **Unidad de Búsqueda de Personas Dadas por Desaparecidas (UBPD)**. La capacitación muestra cómo usar Python para realizar consultas y analizar un dataset de testimonios sintéticos en el contexto de investigaciones sensibles y de valor social.

## Contenido de la Capacitación

La capacitación se centra en enseñar el uso de Python para el análisis y preprocesamiento de datos textuales. A continuación, se detallan las secciones principales incluidas en el proyecto:

1. **Exploración de Datos Inicial**:
   - Conocer la estructura y las características básicas del dataset.
   - Identificar valores faltantes, tipos de datos y estadísticas generales.

2. **Consultas Útiles para Analistas**:
   - Búsquedas de datos específicos, como cédulas, categorías y palabras clave.
   - Filtrado de testimonios por ciudad y análisis de frecuencias en categorías y ciudades.

3. **Limpieza y Preprocesamiento de Texto**:
   - Transformación de textos a minúsculas, eliminación de caracteres especiales, y manejo de espacios en exceso.
   - Eliminación de **stopwords** en español y aplicación de **stemming** para mejorar la calidad del análisis textual.

4. **Análisis de Frecuencia y Visualización**:
   - Identificación de términos comunes en los testimonios.
   - Visualización de frecuencias para encontrar patrones significativos.

5. **Reconocimiento de Entidades Nombradas (NER)**:
   - Implementación de un modelo básico de NER para extraer entidades clave, como nombres de personas, lugares y eventos.

## Requisitos

- **Python** 3.10+
- **Dependencias**: Instalar las dependencias usando `poetry install` basado en el archivo `pyproject.toml`.

## Uso

1. Clona el repositorio e instala las dependencias:
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   cd capacitación
   poetry install
   ```

2. Abre el cuaderno Jupyter y sigue los pasos de la capacitación:
   ```bash
   jupyter notebook
   ```

## Ejecución de Ejemplos

Cada sección del cuaderno está estructurada en formato de preguntas y respuestas. Esto facilita el seguimiento de los pasos y ayuda a los analistas a aplicar las técnicas de Python directamente al dataset.

## Contribuciones

Si deseas contribuir, asegúrate de seguir los estándares de estilo y documentar cualquier cambio realizado. Puedes enviar tus sugerencias a través de pull requests.

---

## Contacto
Para dudas o comentarios, puedes contactar al autor principal en [izainea](mailto:czaineam@unidadbusqueda.gov.co).
