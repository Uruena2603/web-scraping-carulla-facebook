# Web Scraping en Python: Análisis de Precios en Carulla y Publicaciones en Facebook

Este repositorio contiene dos ejercicios de **Web Scraping** realizados con Python en **Jupyter Notebook**. Se utilizaron diversas librerías y técnicas para la extracción, limpieza y análisis de datos obtenidos de páginas web.

## 📂 Contenido del Repositorio

El repositorio está organizado en las siguientes carpetas:

- **Pregunta1/** → Contiene el análisis de precios de pollo y pescado en Carulla.
  - `pregunta1.ipynb` → Notebook con el código y análisis.
  - **html/** → Carpeta con 3 archivos HTML descargados correspondientes a los precios en 3 días distintos.
- **Pregunta2/** → Contiene el análisis de interacciones en publicaciones de Facebook.
  - `pregunta2.ipynb` → Notebook con el código y análisis.
  - **txt/** → Carpeta con 11 archivos de texto.
    - 10 archivos con información extraída de publicaciones.
    - 1 archivo con URLs de las publicaciones analizadas.

## 🚀 Ejercicio 1: Scraping de Precios en Carulla

### 📌 Objetivo

Realizar **Web Scraping** sobre la página de **Carulla** para extraer precios de pollo y pescado durante 3 días diferentes y comparar sus variaciones.

📌 URL analizada: [Carulla - Pollo, Carnes y Pescado](https://www.carulla.com/pollo-carnes-y-pescado?order=OrderByTopSaleDESC)

### 🛠️ Herramientas y Librerías Utilizadas

- `requests` → Para realizar solicitudes HTTP y descargar el HTML.
- `BeautifulSoup` → Para parsear y extraer información de la estructura HTML.
- `pandas` → Para organizar, limpiar y comparar los datos obtenidos.
- `matplotlib` → Para visualizar la evolución de los precios.

### 📖 Proceso de Extracción y Análisis

1. **Descarga de los datos**: Se hizo scraping de la página y se guardaron 3 archivos HTML en la carpeta `html/`.
2. **Extracción de la información**: Se usó `BeautifulSoup` para encontrar los nombres y precios de los productos.
3. **Organización de los datos**: Los datos se guardaron en un diccionario con el formato `{producto: [precio_dia1, precio_dia2, precio_dia3]}`.
4. **Comparación de precios**: Se generaron gráficos y tablas para observar variaciones de precios en los días analizados.

📊 **Resultados esperados:**
- Identificar si hay fluctuaciones de precios en pollo y pescado en diferentes días.
- Determinar si hay productos con cambios significativos de precio.

---

## 🚀 Ejercicio 2: Scraping de Publicaciones en Facebook

### 📌 Objetivo

Realizar **Web Scraping** sobre una página o grupo público de **Facebook**, analizando 10 publicaciones con más de 100 reacciones.

📌 **Preguntas analizadas:**
1. ¿Qué seguidores comentaron en más publicaciones?
2. ¿Cuál es la hora promedio en la que los seguidores reaccionaron más?
3. ¿Qué tipo de publicación (según metadatos) genera más likes?

### 🛠️ Herramientas y Librerías Utilizadas

- `facebook-scraper` → Para extraer información de publicaciones.
- `pandas` → Para organizar y analizar los datos.
- `matplotlib` → Para visualizar patrones en reacciones y horarios.

### 📖 Proceso de Extracción y Análisis

1. **Extracción de publicaciones**: Se recolectaron publicaciones con más de 100 reacciones.
2. **Identificación de seguidores activos**: Se contó cuántas veces comentaron ciertos usuarios.
3. **Análisis de horarios**: Se revisó la hora de las interacciones para encontrar tendencias.
4. **Clasificación de publicaciones**: Se analizaron los metadatos de las publicaciones para determinar qué tipo genera más interacciones.

📊 **Resultados esperados:**
- Identificar a los seguidores más activos.
- Determinar las mejores horas para generar engagement.
- Conocer qué tipo de contenido es más popular en la plataforma.

---

## 💡 Importancia del Web Scraping en el Análisis de Datos

El **Web Scraping** es una herramienta poderosa que permite obtener información valiosa desde sitios web, lo que facilita la toma de decisiones basada en datos. Algunas aplicaciones clave incluyen:

- **Monitorización de precios**: Empresas pueden ajustar estrategias de pricing en función de la competencia.
- **Análisis de tendencias**: Determinar qué tipo de contenido genera más interacción en redes sociales.
- **Investigación de mercado**: Obtener datos en tiempo real sobre preferencias y comportamientos de los consumidores.

---

Si te gustó este análisis, ⭐ ¡Dale un star al repo! 🚀

