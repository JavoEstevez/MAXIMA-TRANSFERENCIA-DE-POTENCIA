# MAXIMA-TRANSFERENCIA-DE-POTENCIA

1. PLANTEAMIENTO DEL PROBLEMA 

En el siguiente informe de laboratorio se va a emplear los conocimientos aprendidos en la teoría de la materia de Fundamentos de Circuitos eléctricos. De este modo utilizaremos el teorema de Thévenin el cual nos permite nos facilita resolver un circuito eléctrico complejo a un sencillo, obteniendo el voltaje y la resistencia del teorema.

2. OBJETIVOS

* Aplicar los conceptos teóricos del teorema Thévenin, mediante la realización de la practica en el simulador TINKERCAD, para la resolución o análisis de los circuitos con el fin de encontrar los valores la fuente y la resistencias llamadas como (Thévenin).

* Encontrar un circuito equivalente de manera simple y rápida aun en circuitos de naturaleza complicados, tomando en cuenta que al menos se debe tener una fuente independiente.

* Comprobar que los resultados de voltaje y corriente calculados son iguales a los medidos en nuestra simulación

* Comparar los porcentajes de error entre el valor calculado y el medido en el simulador TINKERCAD.

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

![](https://github.com/JavoEstevez/MAXIMA-TRANSFERENCIA-DE-POTENCIA/blob/master/Img/DIAGRAMA.jpg)

Fig 2. Diagrama del circuito eléctrico a realizar.

Descripción del circuito

* En el diagrama se observa dos fuentes independientes de voltaje.
* Además, dentro del circuito se aprecia 5 resistencias medidas en KOhms y Ohms.
* Al momento de unir dos elementos eléctricos, se forman nodos que para el caso del circuito de la práctica reconocemos 3 nodos principales.
* Se tiene que la resistencia de 0.56 KOhm forma nodo con la resistencia de 4.7 KOhm y la fuente de 2V. La resistencia de 0.33 KOhm forma un nodo con la resistencia de 0.1 KOhm y con la fuente de voltaje de 2V. La resistenica de 0.1 KOhm forma un nodo con la de 1KOhm. Como nodo de referencia o tierra es toda la sección de abajo del circuito eléctrico.
* Además se puede identificar 3 mallas, que para el análisis se denotará como I1, I2, I3 todas en sentido de las manecillas del reloj(Anexos).

Circuito Eléctrico hecho en Tinkercad

![](https://github.com/PabloGualotuna7/TEOREMA-DE-THEVENIN/blob/master/img/Circuito_TINKERCAD.png)

Fig 3. Implementación del circuito eléctrico en el simulador Tinkercad

Circuito Eléctrico hecho en Tinkercad

![](https://github.com/PabloGualotuna7/TEOREMA-DE-THEVENIN/blob/master/img/Medicion_voltaje.png)

Fig 4. Implementación del circuito eléctrico en el simulador Tinkercad. Medición de voltaje en el resitor de carga

Circuito Eléctrico hecho en Tinkercad 

![](https://github.com/PabloGualotuna7/TEOREMA-DE-THEVENIN/blob/master/img/Medicion_corriente.png)

Fig 5. Implementación del circuito eléctrico en el simulador Tinkercad. Medición de corriente en el resitor de carga

Circuito Eléctrico hecho en Tinkercad 

![](https://github.com/PabloGualotuna7/TEOREMA-DE-THEVENIN/blob/master/img/Medicion_voltaje_sin_R5.png)

Fig 6. Implementación del circuito eléctrico en el simulador Tinkercad. Medición de voltaje en el circuito abierto

Circuito Eléctrico hecho en Tinkercad 

![](https://github.com/PabloGualotuna7/TEOREMA-DE-THEVENIN/blob/master/img/Medicion_resistencia_sin_R5.png)

Fig 7. Implementación del circuito eléctrico en el simulador Tinkercad. Medición de la resistencia equivalente

Circuito equivalente de Thévenin hecho en Tinkercad 

![](https://github.com/PabloGualotuna7/TEOREMA-DE-THEVENIN/blob/master/img/Circuito_Thevenin_voltaje.png)

Fig 8. Implementación del circuito eléctrico en el simulador Tinkercad. Medición de voltaje en el circuito equivalente de Thévenin

Circuito equivalente de Thévenin hecho en Tinkercad 

![](https://github.com/PabloGualotuna7/TEOREMA-DE-THEVENIN/blob/master/img/Circuito_Thevenin_corriente.png)

Fig 9. Implementación del circuito eléctrico en el simulador Tinkercad. Medición de corriente en el circuito equivalente de Thévenin

5. LISTAS DE COMPONENTES

![](https://github.com/PabloGualotuna7/TEOREMA-DE-THEVENIN/blob/master/img/Lista_componentes.png)

Fig 7. Descripción de los componenetes usados en el simulador Tinkercad.

6. DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

* Abrimos el sitio web "tinkercad" y creamos una cuenta.

* Hacemos clic izquierdo en "Circuits" y comenzamos con la práctica.

* Seleccionamos una placa de pruebas pequeñas (Protoboard).

* Se selecciona y se conecta al protoboard los suministros de energía asignándole el valor de 12 y 2 V.

* Escogemos cinco resistencias y las conectamos siguiendo el diagrama visto en el archivo de la práctica, que en este caso son 5 de valores de 0.56 KOhm, 4.7 KOhm, .33 KOhm, 0.1 KOhm y 1 KOhm.

* Haciendo clic izquierdo en los pines del protoboard conectamos con cables las resistencias y pasamos corriente a donde hace falta.

* Colocamos un multímetro y conectamos en paralelo con el circuito, el color negro es el negativo mientras que el color rojo es el positivo.

* Realizamos las mediciones de volatje y resistencia, aplicando el teorema de Thévenin, pedidas en la guía.

* Anotamos los valores obtenidos en las tablas de la guía de laboratorio.

* Guardamos y salimos.

7. TABLAS DE MEDICIONES Y CÁLCULOS 

![](https://github.com/PabloGualotuna7/TEOREMA-DE-THEVENIN/blob/master/img/Tabla_Mediciones_generales.png)

Tabla 1. Comprobación del Teorema de Thévenin.

![](https://github.com/PabloGualotuna7/TEOREMA-DE-THEVENIN/blob/master/img/Tabla_circuito_Th%C3%A9venin.png)

Tabla 2. Valores del circuito equivalente de Thévenin.              

8. PORCENTAJE DE ERROR.

![](https://github.com/PabloGualotuna7/TEOREMA-DE-THEVENIN/blob/master/img/Tabla_porcentaje_de_error.png)

Tabla 3. Porcentaje de error al momento de realizar la práctica.

9. CONCLUSIONES 

* Se concluye que este teorema se puede aplicar a cualquier circuito lineal el cual posea por lo menos una fuente independiente, ya sea de corriente o de voltaje, para reemplazarlo con un circuito equivalente de THÉVENIN mucho más sencillo. 

* En nuestro circuito equivalente los valores de voltaje y corriente en nuestra resistencia R5 van a tener un pequeño error a comparación del circuito original de dos fuentes, debido a los cálculos que requieren una fuente de 5.055V y una resistencia de 298Ohm, que no se pueden colocar en el simulador. Los valores mas cercanos a ingresar fueron de 5V y 300Ohms, provocando este error de medida. 

* Con este teorema podemos representar circuitos un poco largo de una manera facil y con un cirucito muy sencillo, aprendiendo que los circuitos pueden tener los mismos valores pero con una divercidad de elementos. Los cálculos se hacen con la finalidad de poder sustituir todas las fuentes de corrientes o voltajes del circuito por única fuente con el valor de Thévenin en serie con la rsistencia calculada de Thévenin, aparte se vuelven mas didácticos 

* El porcentaje error nos demuestra que el informe se ha desarrollado de manera correcta y este caso nos da un porcentaje de error entre 0 y 1.04 de error entre el calculado y el medido, el cual es un porcentaje bajo y no afecta a los resultados, esto debido también a que no sabemos con cuantos decimales trabaja el simulador TINKERCAD.
 
10. RECOMENDACIONES 

* Se recomienda revisar la teoría del teorema de Thévenin para así desarrollar de una manera más rápida el ejercicio propuesto.

* Se recomienda cambiar el color de los cables a rojo y negro para de esta manera identificar cuáles son positivos o negativos, y no crear una confusión al momento de conectar el circuito.

* Tener en cuenta y verificar los valores de la fuente así como también el valor de las resistencias ya que muchas veces se equivoca al poner KOhm o Ohm.

* Recomendamos una vez obtenido el sistema de ecuaciones en cada caso del analisis, utilizar el método de determinantes, ya que es una forma mas dinámica y rapida para poder resolver este tipo ejercicios.

11. CRONOGRAMA

Actividades desarrolladas a lo largo de la practica de laboratorio.

![](https://github.com/PabloGualotuna7/TEOREMA-DE-THEVENIN/blob/master/img/Cronograma.png)

12. BIBLIOGRAFÍA 

Alexander, C, & Sadiku, M. (2006). Fundamentos de Circuitos Eléctricos. 3ra. Edición. Mc Graw Hill.

Boylestad, R. (2011). Introducción al Análisis de Circuitos.2da. Edición. Pearson.

Dorf, R., & Svoboda, J. (2011). Circuitos eléctricos. México: Alfaomega.
