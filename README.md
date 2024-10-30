# Análisis  de Éxito de Videojuegos para Campañas de Marketing

Ice es una tienda online que vende videojuegos a nivel mundial. Este proyecto se centra en el análisis de datos históricos para identificar patrones de éxito en videojuegos, utilizando reseñas de usuarios y expertos, géneros, plataformas (como Xbox o PlayStation), y datos de ventas. El objetivo es determinar las características y factores clave que indican si un juego será exitoso, permitiendo así detectar proyectos prometedores y planificar campañas publicitarias efectivas.

Nos encontramos en diciembre de 2016 y estamos planificando una campaña publicitaria para el año 2017. Para ello, analizaremos los datos hasta 2016, pero el proyecto se puede adaptar a cualquier periodo de tiempo futuro.

Una de las variables clave en el dataset es la clasificación ESRB ("rating") de cada juego. El Entertainment Software Rating Board clasifica el contenido de los videojuegos en función de la edad recomendada, asignando categorías como "Adolescente" o "Adulto". Esta variable será crucial para segmentar y personalizar las campañas de marketing de acuerdo con el público objetivo.

<span style="color: red;">archivo principal: **games.ipynb**

# Insights

## Periodo de estudio
![image](https://github.com/user-attachments/assets/690a6569-4a05-4680-8d59-495054c2f33b)


## El 60% de las ventas fueron a través del top 6 de plataformas

![image](https://github.com/user-attachments/assets/d8588f5a-e678-4137-a734-8b1d46bb3cad)

## Correlación negativa baja, la valoración de usuario no es directamente proporcional con las ventas de PS4.

![image](https://github.com/user-attachments/assets/2ea383ff-e128-4914-b096-552d88712f69)

## Los géneros con más ventas son Action, Shooter, y Sports, representan más del 80% de las ventas del periodo 2011-2016.

![image](https://github.com/user-attachments/assets/0836090f-726a-4c3b-852f-1177d6066c43)


# Conclusión general
El objetivo del proyecto fue analizar el comportamiento de los clientes y encontrar patrones de consumo. De la muestra se pudo observar lo siguiente: El número de juegos lanzados desde 1995 hasta alrededor del 2008 fue aumentando, y empezó a decrecer alrededor del 2009 hasta el 2016. La cantidad de juegos por año fue entre 200 a más de 1400 juegos. Más del 60% de las ventas fueron a través del top 6 de plataformas : PS2, X360, PS3, Wii, DS y PS. Las plataformas tardar alrededor de 10 años para desaparecer, la plataforma que más duro fue DS. Aparece una plataforma nueva entre 1 a 5 años. Todas las plataformas en un inicio ascienden hasta su punto màximo y luego empiezan a descender hasta desaparecer. Las plataformas con más ventas son PS3, X360, PS4 y 3DS, además las plataformas que se ven más prometedoras son PS4 XONE y 3DS y plataformas nuevas que puedan lanzarse, del periodo 2011-2016. El promedio de las ventas de los juegos están por encima de la mediana, hay muchos valores superiores. Las ventas más significativas son en las plataformas PS3 X360 PS4 XONE, y las más bajas DS Y PS2. Los géneros con más ventas son Action, Shooter, y Sports, representan más del 80% de las ventas del periodo 2011-2016. Los géneros con menos ventas con Puzzle, simulation , strategy,adventure. X360, PS3 , PS4, Xone, 3DS son las plataformas top 5 que representas el 80% de las ventas en Na. X360, PS3 , PS4, PC , 3DS son las plataformas top 5 que representas el 80% de las ventas en eu. 3DS PS3 PSP PSV PS4 Son las plataformas top 5 que representan más del 80% de las ventas en jp. Las plataformas en común PS3, PS4 y 3DS. Action, shooter, sport, role playing y misc representan más del 80% de las ventas en na. Action, shooter, sport, role playing y racin representan casi el 80% de las ventas en eu. Role-playing, action, misc, fighting, y platform representan alrededor del 75% de las ventas en jp.

El género Action es uno de los géneros más representativos en las tres regiones. Los gustos por los géneros en na y eu son similares y claramente diferentes en jp.

Se comprueba una correlación positiva en la valoración de profesionales en las regiones na y eu, una correlación positiva menor en jp.

Se comprueba una correlación positiva muy baja en la valoración de usuarios en na y eu, y ligeramente mayor en jp.

Se eliminó duplicados, se mantuvo la data de ventas con información faltante del año, para revisar las ventas por plataforma. Respecto a user_score y critic_score se manejo la data por separado para la eliminación de valores nulos para no afectar la data entre ellos al eliminar información.

Através del análisis se pudo reconocer géneros y plataformas con mayores ventas, así como plataformas en prometedoras para el siguiente año. Se evidenció diferencia entre el comportamiento de las regiones y el impacto del critic_store en cada región.

Finalmente se realizó prueba de hipótesis donde se pudo afirmar que las calificaciones promedio de los usuarios para los géneros de Acción y Deportes son diferentes.
