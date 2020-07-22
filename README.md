# MAXIMA-TRANSFERENCIA-DE-POTENCIA

1. PLANTEAMIENTO DEL PROBLEMA 

En el siguiente informe de laboratorio se va a emplear los conocimientos aprendidos en la teoría de la materia de Fundamentos de Circuitos eléctricos. De este modo utilizaremos el teorema de Thévenin el cual nos permite nos facilita resolver un circuito eléctrico complejo a un sencillo, obteniendo el voltaje y la resistencia del teorema.

2. OBJETIVOS

* Determinar experimentalmente la condición necesaria para hallar la Máxima Transferencia de Potencia de un circuito eléctrico.

* Conocer los fundamentos básicos de este teorema.

* Analizar el comportamiento de un circuito DC mediante la aplicación del principio de la Máxima Transferencia de Potencia.


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

| RL(Ω)| Corriente medida (mA) | Voltaje Medido (V)| Potencia calculada experimentalmente(W)|Potencia calculada teóricamente(W)| 
| --    |                 ---- |-------------             |----------------      |--------|
| 220 |                   10.6| 2.32                   | 0.025             |    |
|470  |                   8.98 |4.22                    | 0.039             |    |             
|680  |                   7.98   | 5.43                  |0.043                 |     |        
| 820  |                   7.43  | 6.09            | 0.045    |             |
|1000|                     6.82| 6.82           |0.047       |           |
|1500|                      5.56|8.33       |0.046      |         |
|1800|                       5| 9 |  0.045|        | 
|2200|                     4.41| 9.71       | 0.043|     | 
|3900|                      2.94| 11.5       |   0.034|     | 
|4700|                      2.54|11.9|       | 0.030|       | 

8. PORCENTAJE DE ERROR.

![](https://github.com/PabloGualotuna7/TEOREMA-DE-THEVENIN/blob/master/img/Tabla_porcentaje_de_error.png)

Tabla 3. Porcentaje de error al momento de realizar la práctica.

9. CONCLUSIONES 

 
10. RECOMENDACIONES 


11. CRONOGRAMA

Actividades desarrolladas a lo largo de la practica de laboratorio.

![](https://github.com/PabloGualotuna7/TEOREMA-DE-THEVENIN/blob/master/img/Cronograma.png)

12. BIBLIOGRAFÍA 

Alexander, C, & Sadiku, M. (2006). Fundamentos de Circuitos Eléctricos. 3ra. Edición. Mc Graw Hill.

Boylestad, R. (2011). Introducción al Análisis de Circuitos.2da. Edición. Pearson.

Dorf, R., & Svoboda, J. (2011). Circuitos eléctricos. México: Alfaomega.
