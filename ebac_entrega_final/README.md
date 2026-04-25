# Proyecto: Reckitt
## Alumno Daniel Gálvez Vidal
---

Exploraremos los "insights" sobre como se han comportado las ventas de la empresa reckitt, el análisis es importante porqué así podemos conocer más a fondo el rendimiento de la empresa, esto nos ayudará a enteder mejor, el desempeño de los productos en cuanto a ventas, así como el comportamiento de las diferentes zonas en las que se encuentra la empresa. Además haremos un pronóstico del rendimiento para con esto poder ayudar a la empresa a que tenga una idea un poco más clara de sus ventas a futuro y así poder adelantase en la toma de decisiones que ayuden a un mejor desempeño.
---
## Datos utilizados:

Los datos a utilizarse son: TOTAL_UNIT_SALES,TOTAL_VALUE_SALES,TOTAL_UNIT_AVG_WEEKLY_SALES,REGION, BRAND,PRODUCT todo esto correspondiente al 2022 y un poco de el 2023.

## Técnicas que aplicadas:

- Visualización de datos usando diferentes librerías, como: matplotlib y seaborn

- Se utilizaron gráficos de barras, gráficos de línea (plot) y gráficos tipo scatter

- Segmentación con ayuda de KMeans, segmentación por "clusters"

- Para conocer el número de "clusters" ideal se utilizó el método del "codo de Jambú"

- Se creo una base de datos con la herraminta SQL Server Management Studio para poder hacer consultas y filtrado

- Regresión lineal y serie de tiempo ('time series') con un modelo ARIMA 

- Se utilizó el método de Dickey-Fuller para comprobar que nuestra serie no es estacionaria

- Machine learning, con ayuda de nuestros datos separamos los mismos en un grupo de entrenamiento y otro de pueba 'train' y 'test'

utilizamos nuestros datos de 2022 y 2023 para poder entrenar a la máquina y así poder predecir valores del 2023 y con esto crear una serie de tiempo que nos ilustré

el comportmamiento de la empresa. Además de obtener los pronóstico obtuvimos sus interevalos de confianza.

- Por útimo se creo un "Dashboard" con ayuda de la herramineda PowerBi para poder, interactuar con los datos, filtrarlos en tiempo real dependiendo de lo que se necesita
 así también como visualizaciones en tiempo real que nos ayudan a describir a describir y a entender mejor el comportamiento de la empresa. 
------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Conclusiones y hallazgos importantes

El líder en ventas por región es 'Total Auto Scanning México. Está muy por encima de las demás regiones que están casi al mismo nivel en ellas. Se recomienda revisar cuales son los factores que hacen que está diferencia tan grande. Revisar sus procesos y tomar medidas para incrementar las ventas. 

Tanto en el 2022 como en 2023, hay un pico en cuandto a las ventas en la semana dos (su punto más alto). ¿Qué es lo que nos lleva a esta alza en ventas? ¿por qué a la semana que sigue empieza a bajar, hay que poner especial atención en este comportamiento y como se puede crear una estrategía de ser posible las vantas continuen en ese nivel o no bajen tan drasticamente. 

En cuanto a marcas, Vanish 02, Vanish Cristal White y La Japonesa entre otras, no tienen ventas como se puede observar en gráfico azul
Se recomienda reforzar las campañas de mercadotécnia para impulsar las diferentes marcas, mientras que Blancatel y Clorales son las 
Marcas que más se venden.

En cuanto a la serie de tiempo podemos ver en mayo un credimiento y de ahí baja, y después aunque sube y baja se mantiene más o menos al mismo nivel 
se tiene que revisar este comportamiento y ver cuales pueden ser los factores que nos llevan a este pico y después bajan las ventas, más adelante hay un pico en semtiembre la idea es que para los próximos meses lleguen a 160,000 como en semptiembre y se mantengan ahí la mayor parte del tiempo. Más adelante podemos pensar en continuar creciendo. 
