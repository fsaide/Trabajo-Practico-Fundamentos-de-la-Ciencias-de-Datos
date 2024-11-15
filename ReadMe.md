
Apretar ctrl + shift + v para verlo como markdown !!! (solo vs code, igualmente se dejo un txt por si le es mas comodo)

# Fundamentos de la Ciencia de Datos - Cursada 2024 - Práctico Especial

## Participantes 
- **Puggioni Bruno - bruno.puggioni@gmail.com - 44838933**
- **Saide Felipe - fsaide58@gmail.com - 44561355**

## Detalles a tener en cuenta!
- Los graficos pueden estar mal cargados si cargamos todas las celdas de una sola vez, por lo que para que se vea bien todo van a tener que recargarlos una segunda vez! (solo los graficos, lo demas por lo que hemos suele cargar de manera correcta)
- Utilizamos la opción de Markdown que nos ofrece Jupyter para reunir todo el contenido en un único archivo, facilitando así la lectura y organización. Las secciones pueden plegarse y desplegarse a conveniencia, mejorando la navegación y proporcionando una experiencia más fluida. De no ser conveniente este tipo de formato les pedimos disculpas adelantadas!


# Introduccion a los datos

Este conjunto de datos contiene **997 canciones** de la decada de los 80', interpretadas por **478 artistas diferentes**. Incluye variables que describen características musicales como la **duración, energía, bailabilidad, tonalidad, y popularidad, entre otras**. Estas variables permiten un análisis detallado de las canciones y su desempeño comercial, proporcionando una base sólida para **explorar patrones y relaciones** dentro del conjunto. En este análisis, se visualizan gráficamente ciertos detalles del conjunto de datos, lo que facilita la **formulación de hipótesis**. Estas hipótesis deben corroborarse mediante **pruebas estadísticas, utilizando tanto tests paramétricos como no paramétricos**, según corresponda

<details>
  <summary>Informacion detallada del conjunto de datos</summary>

   - **Track**: El título de la canción.
   - **Artist**: El intérprete o grupo que grabó la canción.
   - **Duration**: La duración de la canción, medida en minutos y segundos.
   - **Time_Signature**: La métrica musical de la canción, indica el número de pulsaciones por compás.
   - **Danceability**: Una medida de qué tan adecuada es una pista para bailar, basada en el tempo, la estabilidad del ritmo, la fuerza del ritmo y la regularidad general.
   - **Energy**: Una medida de intensidad y actividad en la canción, donde los valores más altos indican una pista más enérgica.
   - **Key**: La tonalidad musical en la que está compuesta la canción, representada por un número entero.
   - **Loudness**: El volumen promedio de la canción, medido en decibelios (dB).
   - **Mode**: La modalidad de la pista, indica si la canción está en tono mayor o menor.
   - **Speechiness**: Una medida de la presencia de palabras habladas en una pista, valores más altos indican cualidades más parecidas al habla.
   - **Acousticness**: Una medida de la calidad acústica de la pista, valores más altos indican una mayor probabilidad de ser acústica.
   - **Instrumentalness**: Una medida que indica la presencia de voces, valores más altos representan pistas más instrumentales.
   - **Liveness**: Una medida de la probabilidad de que la pista se haya interpretado en vivo, valores más altos indican más ruido de audiencia.
   - **Valence**: Una medida de la positividad musical de la pista, valores más altos indican música más positiva o alegre.
   - **Tempo**: La velocidad o ritmo de la pista, medida en pulsaciones por minuto (BPM).
   - **Popularity**: Una puntuación que refleja la popularidad de la pista, generalmente basada en los recuentos de transmisiones y otras métricas.
   - **Year**: El año en que se lanzó la canción.

  
</details>

## Ejecucion del trabajo practico

<details>
  <summary>Pasos de Ejecución</summary>

  1. Abrir Visual Studio Code.

  2. De no tener el ambiente, se deberá ejecutar en la consola el siguiente código que lo creará:
     
     ```bash
     python -m venv <nombre del ambiente>
     ```

  3. Luego, se deberá activar el ambiente:
     
     ```bash
     <nombre del ambiente>\Scripts\activate
     ```

  4. Se deberán instalar los requerimientos necesarios para poder correr el trabajo práctico:
     
     ```bash
     pip install -r requirements.txt
     ```
     (En este caso, el archivo `txt` se llama de esta manera, si tiene otro nombre se deberá cambiarlo).

  5. Una vez instalado el paquete, se deberá abrir la notebook de Jupyter:
     
     ```bash
     jupyter notebook
     ```

  6. ¡Eso es todo!

  **Nota:** Todo lo que se encuentre dentro de los bloques de código se debe ejecutar en la consola de VS Code.

  **Versión de Python requerida:** 3.12.5
</details>
