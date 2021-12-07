================
Observaciones
================

En la plataforma Dewetra es posible la consultación de datos en tiempo real sobre diferentes tipo de eventos, productos y/o variables:

  - sequía
  - incendios
  - sentinel
  - lluvia
  - humedad del suelo
  - nubes 


.. figure:: img/img_obs_dewBOL.png
    :height: 400px
    :width: 800px
    :scale: 50 %
    :alt: Dewetra Bolivia Observaciones
    :align: center
    
    Datos de observaciones en la Plataforma


Entre cada categoria se pueden encontrar las siguientes capas informativas:

**Sequia**

  - SPEI para 1 mese
  - SPEI para 3 meses
  - SPEI para 6 meses
  - SPEI para 9 meses
  - SPEI para 12 meses
  - SPEI para 24 meses

**Incendios**

  - Hotspot Modis
  - Sentinel Color Verdadero
  - Sentinel Falso Color
  - Sentinel Falso Color Urbano
  - Sentinel Onda Corta Infraroja
  - Sentinel Indice de Humedad Relativa (HR)

**Sentinel**

  - Sentinel Color Verdadero
  - Sentinel Falso Color
  - Sentinel Falso Color Urbano
  - Sentinel Onda Corta Infraroja
  - Sentinel Indice de Humedad Relativa (HR)

**Lluvia**

  - GSMAP
  - IMERG (acumulación de 24 horas)
  - IMERG (acumulación de 30 minutos)
  - IMERG (3 horas)
  - Estaciones al suelo

  El producto GSMAP es un producto JAXA de observaciones satelitales de la lluvia. 
  Ese producto esta disponible con un retraso de algunas horas pero permite una 
  visualización de la mapa de lluvia sobre todo el territorio nacional.
  

.. figure:: img/img_GSMAP_dewBOL.png
    :height: 400px
    :width: 800px
    :scale: 50 %
    :alt: Dewetra Bolivia Producto GSMAP
    :align: center
    
    Tasa de lluvia por hora (producto GSMAP)


Los productos IMERG son productos NASA de observaciones satelitales de la lluvia. 
Ese producto esta disponible a diferentes escalas de agregación temporal: acumulación de 24 horas, acumulación de 30 minutos y 3 horas.

El otro producto de observación de la lluvia es la mapa de estaciones al suelo. 
Al cargar de la mapa se pueden visualizar los pluviómetros telemétricos de la red nacional.

.. figure:: img/img_estaciones_dewBOL.png
    :height: 400px
    :width: 800px
    :scale: 50 %
    :alt: Dewetra Bolivia estaciones al suelo
    :align: center
    
    Estaciones al suelo telemétricas en Bolivia


Las estaciones pueden tener tres colores diferentes:
 
  - blanco, en caso de transmisión activa y ausencia de precipitación
  - verde, en caso de transmisión activa y presencia de precipitación
  - gris en caso de transmisión retrasada.
  
  Haciendo el click sobre la estación que se quiere consultar se puede visualizar el grafico de lluvia registrada por la estación entre la fecha de inicio y la fecha de fine seleccionadas. 
  En el eje izquierdo se puede leer la altura de lluvia y en el derecho se encuentra la acumulación total. Dicha imagen y los datos respectivos se pueden también descargar en el escritorio a través del pulsante en alto a la derecha.

.. figure:: img/img_serie_lluvia_dewBOL.png
    :height: 400px
    :width: 800px
    :scale: 50 %
    :alt: Dewetra Bolivia Datos de lluvia estación al suelo
    :align: center
    
    Ejemplo de dato de lluvia estación al suelo


**Humedad del suelo**
  
  - Producto Copernicus SWI (Soil Water Index - Indice de Agua en el Suelo)


**Nubes** 

  - GOES: producto satelitales para la observación de la cobertura de nubes. 

.. figure:: img/img_GOES_dewBOL.png
    :height: 400px
    :width: 800px
    :scale: 50 %
    :alt: Dewetra Bolivia GOES
    :align: center
    
    Producto GOES
