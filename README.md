<div id="top"></div>
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="Visualization/Images/75 logo.png" alt="Logo" width="80" height="80">
  </a>
  <h1 align="center">NBA CAPSTONE PROJECT</h1>
</div>

## Sobre el proyecto

El Draft de la NBA es un procedimiento de selección de jugadores por el cual las franquicias que forman parte de la liga incorporan a sus equipos jugadores menores de 23 años procedentes de las universidades estadounidenses o de ligas de otros países. 

El presente proyecto trata de desarrollar un modelo predictivo para poder clasificar a los jugadores que van a ser elegibles de cara a los futuros drafts en función de los datos históricos de los jugadores recopilados desde el año 1986. La idea es que los equipos de la NBA puedan usar nuestro proyecto para optimizar sus elecciones en las próximas ediciones del draft.

Para ello, se han scrappeado las estadísticas e informaciones de todos los jugadores a partir de 1986 a través de la página web https://www.basketball-reference.com/ y, tras un proceso de data cleaning y feature engineering, se han clusterizado los datos formando 10 grupos diferenciados de jugadores. Esta primera etapa del proyecto ha cubierto todas las fases hasta el clustering, no llegando a desarrollarse todavía el modelo predictivo

<p align="right">(<a href="#top">back to top</a>)</p>

## Sobre el repositorio

El repositorio refleja las cuatro etapas completadas en esta fase del proyecto: scrapping, data cleaning, feature engineering y clustering. Y queda de la siguiente manera:

· *1. Data Scraping* - Notebook con el código para el scraping de los datos

· *2. Data Cleaning* - Notebook con el código para la limpieza de los datos

· *3. Feature Engineering* - Notebook con el código para el tratamiento de las variables para el clustering

· *4. Data Modelling* - Notebook con el código para el clustering

· *Clean_data* - Archivos limpios que se generan en la limpieza de datos (notebook 2)

    · *Golden records* - Datasets generados en el feature engineering (notebook 3) para usarlos en el clustering

    · *OLD* - Archivos antiguos relativos al cleaning

 · *Models* - Modelos de clustering de generados en el clustering (notebook 4) & apuntes para la descripción de los clusters
  
    · *Clustering Board* - Datasets generados en el clustering (notebook 4)
    
    · *Statistics* - Datasets generados (notebook 4) para detectar las distinciones entre clusters

· *OLD* - Archivos antiguos de carácter general

· *Scraped data* - Archivos generados en el scraping (notebook 1)

    · *OLD* - Archivos antiguos relativos al scraping

· *Visualization* - REPASAR


<p align="right">(<a href="#top">back to top</a>)</p>

## Información útil

Es necesario ejecutar las primeras celdas de cada notebook para tener las instalaciones e importaciones para poder ejecutar todo el código.

El notebook referente a la fase de scrapping, en su ejecución incial, gasta mucho tiempo en generar muchos archivos. Para mejorarlo, hemos elaborado los archivos SCRAPPING_CHKPT.xlsx y SCRAPPING_CHKPT_college.xlsx, que hacen que la ejecución del notebook sea más rápida. 

<p align="right">(<a href="#top">back to top</a>)</p>

## Autores

Oriol Canudo Sánchez, Diego Santos Leite, Miquel Casellas Sulé, Pau Garcia Sanz y Adrià Hernández Capell

<p align="right">(<a href="#top">back to top</a>)</p>

## Contacto

Para plantear cualquier duda o cualquier colaboración, contactad con nbacapstoneproject@gmail.com (??)

<p align="right">(<a href="#top">back to top</a>)</p>
