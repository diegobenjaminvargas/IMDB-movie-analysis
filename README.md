# Análisis de Datos de Películas de Hollywood

## Descripción del Proyecto

Este proyecto realiza un análisis exhaustivo de datos de películas de Hollywood utilizando un dataset de IMDB. Nuestro objetivo es descubrir tendencias y patrones interesantes en la industria cinematográfica, como las películas mejor calificadas, la correlación entre la duración de las películas y sus aspectos técnicos, y el éxito en taquilla en relación con su presupuesto de producción.

## Contenido del Dataset
El dataset utilizado en este proyecto proviene de [Kaggle] (https://www.kaggle.com/datasets/programmerrdai/imdb-movie-dataset/data) y está organizado en 7 carpetas, cada una conteniendo archivos en formato .csv y .json. Para este análisis, nos enfocaremos únicamente en los archivos .csv debido a su estructura adecuada para la iteración e inserción en MongoDB.

### Archivos Utilizados

- **FAQScraper**: Contiene preguntas y respuestas relacionadas con las películas.
  - `movieID`: Identificador único de cada película.
  - `faqTitle`: Preguntas sobre la película, como duración, director, presupuesto, y género.
  - `faqContent`: Respuestas a las preguntas.

- **MoviesBasicDetailsScraper**: Contiene detalles básicos de las películas.
  - `movieID`: Identificador único de cada película.
  - `movieImg`: URL del póster de la película.
  - `movieMoreUrl`: URL para más información en IMDB.
  - `movieTitle`: Título de la película.
  - `movieYear`: Año de estreno.
  - `movieTime`: Duración de la película.
  - `movieAvgRating`: Calificación promedio en IMDB.
  - `movieRatingCount`: Número de usuarios que calificaron la película.

## Requisitos
Para realizar este análisis, es necesario contar con las siguientes herramientas y librerías:

- [Python 3.6 o superior](https://www.python.org/)
- [MongoDB](https://www.mongodb.com/)
- [Jupyter Notebook](https://jupyter.org/) o [Anaconda](https://www.anaconda.com/download) con Jupyter instalado.

## Librerías utilizadas
- pymongo
- pandas
- numpy
- matplotlib

## Configuración del Entorno
Sigue estos pasos para configurar el entorno y las librerías necesarias:

1. Crear un entorno virtual:
   ```bash
   python -m venv movie_mongo_env

2. Activar el entorno virtual:
  - En Windows: 
    ```bash
    movie_mongo_env\Scripts\activate
  - En macOS/Linux:
    ```bash
    source movie_mongo_env/bin/activate

3. Instalar librerías necesarias:
   ```bash
   pip install pymongo pandas numpy matplotlib jupyter ipykernel

4. Crear un kernel para Jupyter Notebook:
   ```bash
   python -m ipykernel install --user --name=movie_mongo_env --display-name "Python (movie_mongo_env)"

## Uso del Proyecto

1. Clona este repositorio:
   ```bash
   git clone <URL-del-repositorio>
    cd <nombre-del-repositorio>

2. Activa el entorno virtual:
  - En Windows:
    ```bash
    movie_mongo_env\Scripts\activate
  - En macOS/Linux:
    ```bash
    source movie_mongo_env/bin/activate

3. Inicia Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

4. Selecciona el kernel "Python (movie_mongo_env)" y abre el notebook del proyecto para comenzar el análisis.

## Contribuciones

Las contribuciones son bienvenidas.

  
