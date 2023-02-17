# Informe-Laboratorio-8

## Integrantes:

  * Alomoto Pilamunga Oscar Alexander
  * Ordóñez Quiroz Fernando Gabriel
  * Pilataxi Constante Luis Jairo

### 1. OBJETIVOS

***General***

*Determinar experimentalmente las características de señales senoidales, mediante un simulador, para verificar si se cumple con las 
características de forma teórica**

***Especificos*** 

*Conocer, estudiar e investigar las características de las Ondas Senoidales.*

*Investigar los tipos de fuentes de energía eléctrica de CA.*

*Investigar la representación de la onda senoidal, tanto en su forma gráfica como
en su forma matemática.*

### 2. MARCO TEÓRICO

![image](https://user-images.githubusercontent.com/104925648/219509366-bca36d49-fd49-49e4-be45-04392521d79e.png)

![image](https://user-images.githubusercontent.com/104925648/219542130-3608fc30-2e06-436e-b98f-42357b913604.png)

![image](https://user-images.githubusercontent.com/104925648/219542158-011b82a1-14c2-4644-b602-71c0c4a2e2a0.png)

![image](https://user-images.githubusercontent.com/104925648/219540581-f57b3595-d985-414d-986a-e1421c3e57cd.png)

![image](https://user-images.githubusercontent.com/104925648/219540614-762eb18e-1495-400f-8bce-dc4968abea80.png)

![image](https://user-images.githubusercontent.com/104925648/219540647-c578356a-96f1-473d-9b64-c9679f65f9ed.png)

![image](https://user-images.githubusercontent.com/104925648/219540755-e8993115-8700-4253-a452-a48317b15cbe.png)

![image](https://user-images.githubusercontent.com/104925648/219540799-9beb0afa-7866-409f-8213-67788bdb9a16.png)

![image](https://user-images.githubusercontent.com/104925648/219540838-6c1531cf-9359-478e-a3f2-4b3464f9601f.png)

![image](https://user-images.githubusercontent.com/104925648/219540863-11b09fbb-e0f7-4ef6-b0cc-d0cbf206d2d1.png)

### 3. EXPLICACIÓN DEL PROCEDIMIENTO

***3.1 Implemente el circuito que se presenta en la figura 7.1***

![image](https://user-images.githubusercontent.com/116774906/219546996-62bb3cf5-e184-4d74-8ba0-36e5f22b6383.png)

*Circuito simulado*

![image](https://user-images.githubusercontent.com/116774906/219546500-8e72b7d1-0c5f-47b2-842e-2620919d6567.png)

Voltaje pico.

![image](https://user-images.githubusercontent.com/116774906/219546899-ee8bcc98-0ba0-4a7e-84f0-92e7eab58aaf.png)

Voltaje RMS

![image](https://user-images.githubusercontent.com/116774906/219546432-68c090a7-539a-4a6c-86a8-cdf61c1fa152.png)


### 4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

#### ¿Cuántas divisiones por cuadro abarca la amplitud pico de la señal de salida?

* 7 cuadros

#### ¿En qué valor está posicionada la perilla VOLTS/DIV?

* 1V por división

#### ¿Cuántas divisiones por cuadro abarca un ciclo completo de la señal de salida?

* 4 divisiones

#### ¿En qué valor está posicionada la perilla TIME/DIV?

* 0.1m segundos

#### 8.5.5.¿Cuál es la amplitud de voltaje y el periodo de la señal que aparece en la pantalla del osciloscopio?
Amplitud = 6.85V 

* Periodo= 0.4ms

#### 8.5.6. Determine la frecuencia natural (Hz) y la frecuencia angular (rad/s) de la señal de salida.

* Frecuencia Natural= 2500Hz 
* Frecuencia Angular= 15707.963 (rad/s)

#### 8.5.7. Con el multímetro digital mida el voltaje de salida en RL: 4.85V
#### 8.5.8. Compare el voltaje medido en el punto 8.5.5. y el obtenido en el punto 8.5.7.
* ¿Coinciden?
 - R: No coinciden, tienen una diferencia cercana al 30% el mayor valor y al menor. 
* ¿Por qué?
 - R: El valor medido en el osciloscopio representa el valor máximo proporcionado por la fuente de voltaje alterna, pero el valor medido por la fuente representa el voltaje rms o eficaz que utilizara cualquier dispositivo eléctrico que se conecte de forma directa a la fuente, este valor rms representa el valor del voltaje de la fuente como si fuera continua, para hallar la se debe tener en cuenta que el valor negativo del voltaje es igual de utilizable que el voltaje positivo, se puede representar esta función como: 

* f(t)=|A*sin(t)|

 - t= tiempo en segundos.
 - A= Amplitud de la onda= Voltaje pico de la fuente. 
 
- Entonces el valor del osciloscopio representa el valor máximo de voltaje que pasa por el cable en un instante determinado, mientras que el voltaje obtenido por el multímetro representa el voltaje funcional para un dispositivo eléctrico, para obtener estos voltajes se recurre al calculo integral, pero si se considera el periodo y la amplitud constantes en el tiempo este se mide como de la siguiente forma: 

* V_(rms)=V_(max)/(2^(1/2))

- Que también se lo estima como el Voltaje máximo es mayor en un 30% al voltaje eficaz, lo que se demuestra al obtener al obtener la diferencia en porcentaje de los 2 valores de voltaje observados. 

### 5. VIDEO

https://youtu.be/WkjY1Si2qeY

### 6. CONCLUSIONES

- *Se logró identificar correctamente cómo usar el osciloscopio identificando cada una de las perillas a fin de poder ver la onda senoidal de 
   una mejor manera en la que se puedan tomar más fácilmente sus datos*
- *Las fuentes de corriente alterna varían en magnitud a lo largo del tiempo describiendo las ondas que muestran el voltaque pico, pico-pico o rms*
- *Un osciloscopio puede mostrar diferentes tipos de ondas dependiendo de la fuente que este conactado y de la frecuencia a la que se muevan los valores de voltaje*
- *El valor del voltaje mostrado en el osciloscopio varia de la del multímetro por un factor de error cuadrático medido llamado "RMS" (Root mean square)*

### 7._ BIBLIOGRAFÍA

- FLOYD, THOMAS L.Principios de circuitos eléctricos. Octava edición. PEARSON EDUCACIÓN, México, 2007
- BOYLESTAD, ROBERT L. Introducción al análisis de circuitos. PEARSON EDUCACIÓN, México, 2004
