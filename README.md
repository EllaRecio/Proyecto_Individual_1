<p align=center><img src=https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png><p>

# <h1 align=center> **PROYECTO INDIVIDUAL Nº1** </h1>

# <h1 align=center>**`Machine Learning Operations (MLOps)`**</h1>

<p align="center">
<img src="https://user-images.githubusercontent.com/67664604/217914153-1eb00e25-ac08-4dfa-aaf8-53c09038f082.png"  height=300>
</p>

En el escenario de Steam, una plataforma de videojuegos internacional, la tarea asignada es crear un modelo de ML capaz de recomendar 5 juegos afines a los usuarios y 5 funciones más. Sin embargo, se presenta un desafío importante: los datos disponibles se encuentran en un estado deficiente, lo que requiere la realización ágil de tareas de Ingeniería de Datos para preparar los datos y lograr una predicción precisa.



## Requisitos

Python 3.x instalado y las siguientes bibliotecas requeridas:

- pandas
- scikit-learn
- fastapi
- difflib


## Modo de uso

1. Clona este repositorio en tu sistema local.

2. Asegúrate de tener los siguientes archivos de datos disponibles en la carpeta `data/` en el directorio del proyecto:

3. Ejecuta el archivo `main.py` para iniciar el servidor FastAPI:

```
python main.py
```


4. Una vez que el servidor esté en funcionamiento, puedes acceder a las siguientes funciones::


* `/developer`: Ingresando una desarrolladora de videojuegos, se obtiene el porcentaje gratuito de juegos y la cantidad de juegos creados por año.
* `/developer`: Ingresando una desarrolladora de videojuegos, se obtiene la cantidad de valoraciones positivas y negativas para dicha desarrolladora.
* `/userid`: Ingresando un id de usuario, se obtiene la cantidad de dinero que ha gastado y el porcentaje de recomendación de dicho usuario.
* `/UserForGenre`: Ingresando un género, se obtiene el usuario que acumula más horas jugadas para el género dado y una lista de la acumulación de horas jugadas por año de lanzamiento.
* `/best_developer_year`: Ingresando el año, se obtiene los 3 de desarrolladores con juegos más recomendados en dicho año.
* `/prediccion`: Ingresando un id de juego, se obtiene una lista con 5 juegos recomendados, similares al juego ingresado.



