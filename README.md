UNIVERSIDAD DE LAS FUERZAS ARMADAS - ESPE

![](https://github.com/BraddJCJ/Informe5_Jerez_Sangoquiza_Zambrano/blob/master/img/Logo_ESPE.png)

¨Práctica de Laboratorio N°5 Teorema de Thévenin¨  
¨Fundamentos de Circuitos Eléctricos¨  
Integrantes: Jerez Bradd; Sangoquiza Andrés; Flores de Valgas Jonathan.  
NRC: 8702   
Fecha: 2020 - 07 - 15  

1.- PLANTEAMIENTO DEL PROBLEMA:

¿Existe una relación entre al análisis normal de un circuito eléctrico con el análisis Thévenin? ¿Los valores obtenidos de ambos se asemejarán o variarán drásticamente? ¿Es factible realizar el uso de un circuito Thévenin para facilitar la resolución del problema?

2.- OBJETIVOS:

* General: 

Comprobar experimentalmente el Teorema de Thévenin en un circuito resistivo.

* Específico:

Identificar la importancia en la implementación de un circuito equivalente de Thévenin.

Rediseñar el circuito, planteado aplicando el teorema de Thévenin.

Determinar el comportamiento del circuito al implementar un elemento variable.


3.- MARCO TEORICO:

El Teorema de Thévenin, es una forma en la que se puede ¨reducir¨ un circuito el cual consta de dos terminales, por uno equivalente. Este cambio en el diseño del circuito ayuda a que el análisis realizado no tenga que recalcularse luego de conectar un elemento variable en las dos terminales del circuito. El teorema de Thévenin reemplaza al circuito lineal por una fuente de tensión (V_Th) y una resistencia (R_Th).

![](https://github.com/BraddJCJ/Informe5_Jerez_Sangoquiza_Zambrano/blob/master/img/Fig.1.png)

La carga (elemento variable del circuito) puede ser representado por la adaptación de un dispositivo móvil, un radio, un computador, etc... Para hallar a implementar este diseño de circuito, se debe obtener un voltaje Vo, el cual se encontrará entre las terminales del circuito abierto (a) y (b). Este voltaje Vo será representado por el voltaje de Thévenin (V_Th), mientras que, para hallar la resistencia de Thévenin, se hará una sumatoria de todas las resistencias de igual forma que con el método de “superposición”, en otras palabras, se apagarán todas las fuentes independientes del circuito. Cabe mencionar que se aplica el mismo concepto de que “fuentes dependientes” no se apagan. 

![](https://github.com/BraddJCJ/Informe5_Jerez_Sangoquiza_Zambrano/blob/master/img/Sadiku%203%20Ed.pdf%20-%20Adobe%20Acrobat%20Reader%20DC%2014_07_2020%2019_43_00.png)


4.- DIAGRAMAS:

Circuito designado:

![](https://github.com/BraddJCJ/Informe5_Jerez_Sangoquiza_Zambrano/blob/master/img/Diagrama%20P5.png)

Voltaje de Thévenin:
 
 ![](https://github.com/BraddJCJ/Informe5_Jerez_Sangoquiza_Zambrano/blob/master/img/Pr%C3%A1cticaN5%20VTh.png)

Resistencia de Thévenin:
 
 ![](https://github.com/BraddJCJ/Informe5_Jerez_Sangoquiza_Zambrano/blob/master/img/Pr%C3%A1cticaN5%20RTh.png)

Circuito de Thevenin:

![](https://github.com/BraddJCJ/Informe5_Jerez_Sangoquiza_Zambrano/blob/master/img/DiagramaCTh.png)


5.- LISTA DE COMPONENTES:

![](https://github.com/BraddJCJ/Informe5_Jerez_Sangoquiza_Zambrano/blob/master/img/Componentes.png)
 
6.- CONCLUSIONES:

-	La implementación de un elemento variable en un circuito llega a alterar los valores calculados de todo el circuito.
-	Es muy importante rediseñar un circuito, el cual es expuesto a un elemento variable, puesto que existirá una variación en los cálculos una vez realizados, por lo que este ¨fallo en los análisis¨ puede perjudicar al elemento conectado, por ejemplo, un celular y en el peor de los casos ¨quemarlo¨. 
-	En el análisis analítico es preferible mantener las unidades decimales como fracción, de esta forma evitamos caer en errores de cifras notables y por consiguiente un mayor valor para el error porcentual.
-	El cálculo de los errores se mantiene bajo el valor máximo permitido, por lo cual podemos asegurar que los valores obtenidos son correctos para su uso en diferentes apartados del informe u otros.
-	Los valores del circuito original con el circuito Thévenin son extremadamente parecidos, así que podemos asegurar que, por el método de Thévenin, obtendremos valores reales del circuito.

7.- RECOMENDACIONES:

-	Siempre es necesario realizar las medidas correctas antes de ensamblar un circuito, debido a que, si este es expuesto a un elemento de carga variable, existirán grandes complicaciones que afectarán directamente a al dispositivo conectado.
-	Se debe tener cuidado especialmente al realizar las conexiones en el simulador, puesto que, al fallar en un nodo, podemos caer en un fallo que no nos permita apreciar el valor real de la simulación.
-	Al analizar el cualquier circuito eléctrico, nosotros debemos saber diferenciar cual será el método más eficiente y rápido para resolverlo. Dado esto, conocemos el análisis de un circuito Thévenin.


8.- CRONOGRAMA:
![](https://github.com/BraddJCJ/Informe5_Jerez_Sangoquiza_Zambrano/blob/master/img/Cronograma0.png)
 
9.- BIBLIOGRAFIA
 
 - Sadiku Matthew N. (2006). Fundamentos de Circuitos Eléctricos. McGraw-Hill Interamericana. México D. F.
-  Richard C. Dorf y James A. Svoboda. (2006). Introduccion Circuitos Electronicos. 6ta Ed. John Willey & Sons, Inc. Mexico D.F.

 10.-ANEXOS:
 
 Link acceso al análisis de datos realizados en LaTeX
 
(https://www.overleaf.com/3347165426hjzftvdfhgvf)

![](https://github.com/BraddJCJ/Informe5_Jerez_Sangoquiza_Zambrano/blob/master/img/0001%20(1).jpg)

![](https://github.com/BraddJCJ/Informe5_Jerez_Sangoquiza_Zambrano/blob/master/img/0002.jpg)

![](https://github.com/BraddJCJ/Informe5_Jerez_Sangoquiza_Zambrano/blob/master/img/0003.jpg)

![](https://github.com/BraddJCJ/Informe5_Jerez_Sangoquiza_Zambrano/blob/master/img/0004.jpg)
 
 Analisis de los errores:
 
 ![](https://github.com/BraddJCJ/Informe5_Jerez_Sangoquiza_Zambrano/blob/master/img/error1.png)
 
 ![](https://github.com/BraddJCJ/Informe5_Jerez_Sangoquiza_Zambrano/blob/master/img/error2.png)
