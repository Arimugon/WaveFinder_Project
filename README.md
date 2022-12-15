# WaveFinder_Project🏄‍♂️🏄🏽‍♀️

![surf-pipeline-1](https://user-images.githubusercontent.com/113017465/207929101-9597dd98-5058-4cf2-aba8-9214e949b24b.jpg)

Para mi proyecto final he decidido realizar un buscador de olas de España, "WaveFinder". Mi finalidad es crear un buscador que  permita tanto buscar una ola según tus preferencias (comunidad, playa ,hora, fecha, altura de la ola, intervalo, y viento), como facilitarte las mejores olas existentes por día en España mediante un fitro automático, para que el usuario simplemente tenga que coger su tabla y dirigirse a una playa!

## PASOS SEGUIDOS:

### 1. Extracción:

- Scrapeo con Selenium: La fuente de información utilizada para mi proyecto ha sido Winguru (https://www.windguru.cz), he tenido que realizarla por filas ya que solo me interesaban ciertos datos de las columnas.

- Excel con la latitud y longitud de las playas seleccionadas.

### 2. Transformación:

- Realización de una función "tirana" que me permitiese bajar todos los datos tan solo introduciendo las url.

- División de las playas de España en norte, sur , este y oeste.

- Limpieza, estandarización y unificación de los df.

### 3. Base de datos:

- Subida de datos a SQL.

### 4. Visualización:

- EL programa elegido para realizar la visualización ha sido PowerBi, en el he realizado tanto la introducción  de la presentación como el buscador.

![Captura de pantalla 2022-12-15 181224](https://user-images.githubusercontent.com/113017465/207933507-97e2bdbb-a1cd-461f-a1f7-63309b3334ee.png)


## HERRAMIENTAS UTILIZADAS:

- Lenguajes de programación:
  Python: numpy, pandas, selenium
  
- MySQL

- Power BI



