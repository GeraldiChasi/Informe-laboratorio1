PRÁCTICA No. 1	LEYES DE KIRCHHOFF

OBJETIVO DE LA PRÁCTICA

OBJETIVO GENERAL:

Determinar las características y mediciones  experimentales de  la Ley de Kirchhoff de Voltajes y la Ley de Kirchhoff de Corrientes, en un circuito, y comparar sus valores mediante tablas y simuladores.

OBJETIVOS ESPECÍFICOS:

Verificar el cumplimiento de la regla de kirchhoff de voltajes.
Verificar el cumplimiento de la regla de kirchhoff de corriente.
 Realizar el procedimiento en un simulador llamado Tinkercad.


REQUISITOS PREVIOS.

Se requiere el análisis analítico del circuito mostrado en la figura 1.1. Anote los resultados obtenidos en las tablas 1.1, 1.2. y 1.3.

INFORMACIÓN GENERAL

Uno de los métodos ampliamente utilizados en el análisis de circuitos eléctricos son las Leyes de Kirchhoff del voltaje y corriente, ya que con ellas se puede determinar el valor de voltaje o corriente en cualquier elemento que forme parte del circuito. Las Leyes de Kirchhoff se enuncian a continuación:


Ley de Kirchhoff de Corrientes: La suma de las corrientes que entran a un nodo es igual a la suma de las corrientes que salen del mismo.

En el análisis de circuitos eléctricos no suele ser suficiente con emplear la ley de Ohm, para ello se acude a las leyes de Kirchhoff que complementan el análisis de circuitos como una herramienta eficaz para analizar y resolver una gran variedad de circuitos eléctricos. Las leyes de Kirchhoff se llaman así en honor al físico alemán Gustav Robert Kirchhoff quien introdujo la ley de corriente (o primera ley de Kirchhoff) y ley de tensión (o segunda ley de Kirchhoff).

![image](https://user-images.githubusercontent.com/84427371/120763826-38852b00-c4dd-11eb-8cef-6c42871f8601.png)


Nodo: Es la unión entre dos o más elementos  dentro de un circuito eléctrico.  En cuanto a los nodos pueden estar a simple vista o distribuidos a lo largo de un mismo cable pero a fin de cuentas todos están unidos al mismo cable.

![image](https://user-images.githubusercontent.com/84427371/120763875-45098380-c4dd-11eb-982b-14f2a65dcfa5.png)

Corriente eléctrica: es un flujo de electrones que circula a través de materiales conductores en un circuito cerrado.

![image](https://user-images.githubusercontent.com/84427371/120763991-60748e80-c4dd-11eb-9660-8de732d4a8c7.png)

La ley de corriente de Kirchhoff: Está basada en la ley de la conservación de la carga, lo cual implica que la suma algebraica de las cargas dentro de un sistema no puede cambiar.

![image](https://user-images.githubusercontent.com/84427371/120764064-72563180-c4dd-11eb-8d5e-bfc68faad785.png)

N = Número de ramas conectadas al nodo.
in = n-ésima corriente que entra o sale del nodo.

De acuerdo a la ley de corriente de Kirchhoff (LCK), se pueden considerar positivas o negativas las corrientes que entran a un nodo, siempre y cuando las corrientes que salen de ese nodo se tomen con el signo opuesto a las corrientes que entran al mismo nodo.

![image](https://user-images.githubusercontent.com/84427371/120764186-89951f00-c4dd-11eb-8121-bd9a2727f9a8.png)

La polaridad que deben de tener las corrientes se puede observar en la Figura que I1 entra al nodo mientras que I2 e I3 salen del nodo.

Ley de Kirchhoff de Voltajes: La suma de las caídas de voltaje en una trayectoria cerrada es igual a la suma de las elevaciones de voltaje en la misma.
La aplicación de la segunda Ley de Kirchhoff (Gustav Kirchhoff 1824-1887) se utiliza cuando un circuito posee más de una batería y varios resistores de carga. En este caso, ya no resulta tan claro como se establece la corriente por el mismo. En ese caso es de aplicación de esta ley la que nos permite resolver el circuito con una gran claridad.
Ley de mallas:
En un circuito cerrado:“La suma de las tensiones de batería que se encuentran al recorrerlo siempre serán iguales a la sumatoria de las caídas de tensión existente sobre los resistores”.

![image](https://user-images.githubusercontent.com/84427371/120764260-9d408580-c4dd-11eb-9c24-ccbd99e7151a.png)

Depende de la polaridad que se le asigne a cada tensión y del sentido de la corriente en cada malla, ya sea en sentido de las manecillas del reloj o en sentido contrario, se pueden considerar positivas o negativas las tensiones presentes en una malla.


MATERIAL Y EQUIPO REQUERIDO


![image](https://user-images.githubusercontent.com/84427371/120764365-b0ebec00-c4dd-11eb-91f3-3473686c9a4b.png)


PROCEDIMIENTO

Arme el circuito que se muestra en la figura 1.1.

![image](https://user-images.githubusercontent.com/84427371/120764436-c234f880-c4dd-11eb-850c-e343c858e4a9.png)


Mida el voltaje y la corriente en cada uno de los elementos del circuito. Anote los resultados de las mediciones en la tabla 1.1.



Tabla 1.1. Resultados obtenidos de voltaje y corriente, en cada elemento del circuito.

VARIABLE
VALOR CALCULADO
VALOR MEDIDO
VR1 (V)


1.85
IR1 (mA)
9m
8.99m
VR2 (V)


3.82
IR2 (mA)
2.3m
2.31m
VR3 (V)


1.91
IR3 (mA)
4.09m
4.09m
VR4 (V)


1.91
IR4 (mA)
4.09m
4.04m
VR5 (V)


3.33
IR5 (mA)
5m
5m



Verifique si se cumple la Ley de Kirchhoff de Voltajes en cada trayectoria cerrada, considerando las elevaciones de voltaje con signo positivo y las caídas de voltaje con signo negativo. Anote los resultados en la tabla 1.2.







Tabla 1.2. Verificación de la LVK.

VOLTAJE
Trayectoria 1
Trayectoria 2
Trayectoria 3
Calculado
Medido
Calculado
Medido
Calculado
Medido
VT (V)












VR1 (V)












VR2 (V)












VR3 (V)












VR4 (V)












VR5 (V)












∑ V














Verifique si se cumple la Ley de Kirchhoff de Corrientes en cada nodo, tomando con signo positivo las corrientes que entran al nodo y con signo negativo las que salen del nodo. Anote los resultados en la tabla 1.3.

Tabla 1.3. Verificación de la LCK.

 
 
CORRIENTE
Nodo 1
Nodo 2
Nodo 3
Nodo 4
Nodo 5
Calculado
Medido
Calculado
Medido
Calculado
Medido
Calculado
Medido
Calculado
Medido
IT(mA)
 
 
 
 
 
 
 
 
 
 
IR1(mA)
 
 
 
 
 
 
 
 
 
 
IR2(mA)
 
 
 
 
 
 
 
 
 
 
IR3(mA)
 
 
 
 
 
 
 
 
 
 
IR4(mA)
 
 
 
 
 
 
 
 
 
 
I5(mA)
 
 
 
 
 
 
 
 
 
 
∑I
 
 
 
 
 
 
 
 
 
 




Compare los resultados medidos con los valores obtenidos al analizar el circuito analíticamente y concluya al respecto.
Bibliografía
MecatrónicaLATAM. (26 de Abril de 2021). MecatrónicaLATAM. Obtenido de Leyes de Kirchhoff: https://www.mecatronicalatam.com/es/tutoriales/teoria/leyes-de-kirchhoff/
Electricasas. (s.f.). electricasas.com. Obtenido de Leyes de Kirchhoff. Primera y segunda ley, concepto, fórmulas y ejemplos: https://www.electricasas.com/leyes-de-kirchhoff-primera-y-segunda-ley-concepto-formulas-y-ejemplos/#:~:text=Ahora%20que%20sabemos%20cual%20es,es%20igual%20a%20ER2%20%3D%20R2%20.
Ingeniería Mecafenix. (26 de Octubre de 2018). Ingeniería Mecafenix. La enciclopedia de la ingeniería. Obtenido de Ley de corriente de Kirchhoff: https://www.ingmecafenix.com/electronica/ley-de-corriente-de-kirchhoff/
 

