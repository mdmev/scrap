# Upwork Data Science Job Scraper & Analyzer

## Descripción
Este repositorio contiene un script de Python diseñado para realizar web scraping y analizar datos de trabajos relacionados con la ciencia de datos publicados en la plataforma de freelancers Upwork. El proyecto automatiza la extracción de información clave de los anuncios de trabajo, la procesa y analiza para obtener insights útiles.

## Características
- **Web Scraping Automatizado**: Utiliza Selenium para navegar y extraer datos de Upwork.
- **Extracción de Datos Diversos**: Recopila información como título, descripción, nivel de habilidad requerido, precio, categoría y fecha de publicación.
- **Análisis de Datos**: Incluye la limpieza, estructuración y análisis estadístico de los datos.
- **Visualización de Datos**: Utiliza Plotly para generar visualizaciones interactivas de los datos.
- **Actualización de Base de Datos**: Integra los datos scrapeados en una base de datos MySQL para almacenamiento y análisis posteriores.

## Estructura del Proyecto
El proyecto consta de varias fases clave:
1. **Configuración Inicial**: Establecimiento del entorno y configuración del webdriver de Selenium.
2. **Proceso de Scraping**: Navegación y extracción de datos de la página web de Upwork.
3. **Limpieza y Creación de DataFrame**: Procesamiento de los datos scrapeados usando Pandas.
4. **Actualización de Base de Datos**: Integración de los datos en una base de datos MySQL.
5. **Análisis de Datos**: Análisis y visualización de los datos recopilados.

## Tecnologías Utilizadas
- Python
- Selenium
- Pandas
- Plotly
- MySQL

## Instalación
Para ejecutar este proyecto, asegúrese de tener instaladas las dependencias necesarias listadas en `requirements.txt`.

```bash
pip install -r requirements.txt
