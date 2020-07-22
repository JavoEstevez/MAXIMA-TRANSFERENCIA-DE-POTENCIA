# MAXIMA-TRANSFERENCIA-DE-POTENCIA

1. PLANTEAMIENTO DEL PROBLEMA 

En el siguiente informe de laboratorio se va a emplear los conocimientos aprendidos en la teoría de la materia de Fundamentos de Circuitos eléctricos. De este modo se podrá analizar y emplear el Teorema de MTP (Máxima Transferencia de Potencia), en donde se realizará las medidas correspondientes en el circuito implementado para poder obtener los resultados y realizar los análisis correspondientes aplicando el teorema de MTP.

2. OBJETIVOS

* Conocer los fundamentos básicos del teorema de MTP, y profundizar en los circuitos eléctricos para poder aplicar de manera directa lo estudiado.

* Determinar experimentalmente la condición necesaria para hallar la Máxima Transferencia de Potencia de un circuito eléctrico tomando en cuenta el circuito implementado.

* Analizar el comportamiento de un circuito mediante la aplicación del principio de la Máxima Transferencia de Potencia.

* Comparar las medidas de potencia entre las calculadas y las experimentales para encontrar el porcentaje de error. 

3. MARCO TEÓRICO 

En Ingeniería eléctrica y electrónica, el teorema de máxima transferencia de potencia establece que, dada una fuente, con una resistencia de fuente fijada de antemano, la resistencia de carga que maximiza la transferencia de potencia es aquella con un valor óhmico igual a la resistencia de fuente. También este ayuda a encontrar el teorema de Thevenin y Norton.

El teorema establece cómo escoger (para maximizar la transferencia de potencia) la resistencia de carga, una vez que la resistencia de fuente ha sido fijada, no lo contrario. No dice cómo escoger la resistencia de fuente, una vez que la resistencia de carga ha sido fijada. Dada una cierta resistencia de carga, la resistencia de fuente que maximiza la transferencia de potencia es siempre cero, independientemente del valor de la resistencia de carga.

Cualquier circuito o fuente de alimentación posee una resistencia interna. Si consideramos que el valor de la tensión y de la resistencia interna permanecen constantes, podemos calcular cuándo la potencia entregada a la carga es máxima. Esto ocurre cuando la resistencia de carga es igual a la resistencia interna de la fuente.

![](https://raw.githubusercontent.com/JavoEstevez/MAXIMA-TRANSFERENCIA-DE-POTENCIA/master/Img/transferencia.jpg)

Ri = Resistencia interna [Ω]

RL = Resistencia de carga [Ω]

Si la resistencia de carga es más baja que la interna, aumenta la corriente por el circuito pero la resistencia interna en serie disipa más potencia (al estar en la misma rama la corriente que pasa por ambas es la misma y por lo tanto la resistencia de mayor valor disipa mayor potencia).

Si la resistencia de carga es más alta, disipa mayor potencia que la resistencia interna, pero disminuye la corriente total de tal forma de ser menor a la que circula cuando ambas resistencias son del mismo valor y por lo tanto la potencia entregada a la carga es menor.

4. DIAGRAMAS

Circuito Eléctrico

![](https://github.com/JavoEstevez/MAXIMA-TRANSFERENCIA-DE-POTENCIA/blob/master/Img/Captura.JPG)

Fig 2. Circuito para comprobar el Teorema de la MTP

Descripción del circuito

* En el diagrama se observa una fuente independiente de voltaje.
* Además, dentro del circuito se aprecia 1 resistencia de 1.2KOhms y una Rl.


Circuito Eléctrico hecho en Tinkercad

![](https://github.com/JavoEstevez/MAXIMA-TRANSFERENCIA-DE-POTENCIA/blob/master/Img/CIRCUITO.jpg)

Fig 3. Implementación del circuito eléctrico en el simulador Tinkercad

5. LISTAS DE COMPONENTES

![](https://github.com/JavoEstevez/MAXIMA-TRANSFERENCIA-DE-POTENCIA/blob/master/Img/COMPONENTES.jpg)

Fig 7. Descripción de los componenetes usados en el simulador Tinkercad.

6. DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

* Abrimos el sitio web "tinkercad" y creamos una cuenta.

* Hacemos clic izquierdo en "Circuits" y comenzamos con la práctica.

* Seleccionamos una placa de pruebas pequeñas (Protoboard).

* Se selecciona y se conecta al protoboard el suministro de energía asignándole el valor de 15.

* Escogemos 10 resistencias y las conectamos siguiendo el diagrama del circuito.

* Haciendo clic izquierdo en los pines del protoboard conectamos con cables las resistencias y pasamos corriente a donde hace falta.

* Colocamos un multímetro y conectamos en paralelo con el circuito, el color negro es el negativo mientras que el color rojo es el positivo.

* Realizamos las mediciones de volatje y resistencia, aplicando el teorema de Máxima Transferencia de Potencia, pedidas en la guía.

* Anotamos los valores obtenidos en las tablas de la guía de laboratorio.

* Guardamos y salimos.

7. TABLAS DE MEDICIONES Y CÁLCULOS 

| RL()| Corriente medida (mA) | Voltaje Medido (V)| Potencia calculada experimentalmente(W)|Potencia calculada teóricamente(W)| 
| --    |                 ---- |-------------             |----------------      |--------|
| 220 |                   10.6| 2.32    |              | 0.024    |
|470  |                   8.98 |4.22    |              | 0.0389   |               
|680  |                   7.98   | 5.43 |              | 0.04347  |        
| 820  |                   7.43  | 6.09 |              | 0.0452   |
|1000|                     6.82| 6.82   |              | 0.0465   | 
|1500|                      5.56|8.33   |              | 0.0463   |
|1800|                       5| 9       |              | 0.045    |
|2200|                     4.41| 9.71   |              | 0.0428   | 
|3900|                      2.94| 11.5  |              | 0.0337   | 
|4700|                      2.54|11.9   |              | 0.0304   | 

8. PORCENTAJE DE ERROR.

![](https://github.com/PabloGualotuna7/TEOREMA-DE-THEVENIN/blob/master/img/Tabla_porcentaje_de_error.png)

Tabla 3. Porcentaje de error al momento de realizar la práctica.

9. PREGUNTAS

* ¿Se cumple el Teorema de la Máxima Transferencia de Potencia? Argumente su
respuesta



* ¿Cuál fue la potencia máxima en RL? 

0.0469 Watts

*  ¿Para qué valor de RL se obtiene la MTP? 

1200 Ω

10. CONCLUSIONES 

 
11. RECOMENDACIONES 


12. CRONOGRAMA

Actividades desarrolladas a lo largo de la practica de laboratorio.

![](https://github.com/PabloGualotuna7/TEOREMA-DE-THEVENIN/blob/master/img/Cronograma.png)

13. BIBLIOGRAFÍA 

Alexander, C, & Sadiku, M. (2006). Fundamentos de Circuitos Eléctricos. 3ra. Edición. Mc Graw Hill.

Boylestad, R. (2011). Introducción al Análisis de Circuitos.2da. Edición. Pearson.

Dorf, R., & Svoboda, J. (2011). Circuitos eléctricos. México: Alfaomega.
