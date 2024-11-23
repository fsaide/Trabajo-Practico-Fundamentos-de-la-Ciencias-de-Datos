# Fundamentos de la Ciencia de Datos - Cursada 2024 - Práctico Especial

## Participantes 
- **Puggioni Bruno - bruno.puggioni@gmail.com - 44838933**
- **Saide Felipe - fsaide58@gmail.com - 44561355**

# Informe sobre el analisis y estudio realizado
[![Static Badge](https://img.shields.io/badge/Informe-blue?logo=google-docs&logoColor=white&labelColor=gray)](https://docs.google.com/document/d/1dGO9F_QgY6KRmonIJ7Fg_spIVwFiltMosjU8q06DXDY/edit?usp=sharing)

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


## Descarga del trabajo  
**Manualmente:**  

1. Nos dirigimos al siguiente repositorio:  
   [https://github.com/fsaide/Trabajo-Practico-Fundamentos-de-la-Ciencias-de-Datos.git](https://github.com/fsaide/Trabajo-Practico-Fundamentos-de-la-Ciencias-de-Datos.git)  

2. Apretamos en la barra de **`<> Code`** y seleccionamos la opción **Download ZIP**.  

**Usando Git:**  

1. Abrimos una terminal o consola.  

2. Nos dirigimos al directorio donde queremos clonar el proyecto utilizando el comando:  
   ```bash
   cd <ruta_del_directorio>
   ```  

3. Ejecutamos el siguiente comando para clonar el repositorio:  
   ```bash
   git clone https://github.com/fsaide/Trabajo-Practico-Fundamentos-de-la-Ciencias-de-Datos.git
   ```  

4. Una vez completado, nos movemos al directorio del proyecto:  
   ```bash
   cd Trabajo-Practico-Fundamentos-de-la-Ciencias-de-Datos
   ```  

## Ejecucion del trabajo practico

### Requisitos
   [![Python Version](https://img.shields.io/badge/python-3.12.5%2B-blue.svg)](https://www.python.org/downloads/)
[![Jupyter](https://img.shields.io/badge/Jupyter-%23F37626.svg?style=flat&logo=Jupyter&logoColor=white)](https://jupyter.org)

1. **Abrir Visual Studio Code o nuestro IDE favorito.**

2. **Abrir la carpeta donde están los archivos.**

3. **De no tener el ambiente configurado, se deberá crear uno ejecutando en la consola el siguiente código:**

   - **Windows:**
     ```bash
     python -m venv <nombre_del_ambiente>
     ```
   - **macOS/Linux:**
     ```bash
     python3 -m venv <nombre_del_ambiente>
     ```

4. **Luego, activar el ambiente:**

   - **Windows:**
     ```bash
     <nombre_del_ambiente>\Scripts\activate
     ```
   - **macOS/Linux:**
     ```bash
     source <nombre_del_ambiente>/bin/activate
     ```

5. **Instalar los requerimientos necesarios para poder correr el trabajo práctico:**
   ```bash
   pip install -r requirements.txt
   ```
   *(Si el archivo tiene un nombre diferente, deberá cambiarse en el comando).*

6. **Abrir la notebook de Jupyter:**
   ```bash
   jupyter notebook
   ```

7. **¡Eso es todo!**

  **Nota:** Todo lo que se encuentre dentro de los bloques de código se debe ejecutar en la consola de VS Code.