# PROYECTO-TARJETA-DE-IDENTIFICACION-
## OBJETIVO
Este programa esta diseñado para familiarizarse con la pataforma de simulacion en linea WOKWI y NODE-RED para crear un proyecto basico "tarjeta de simulacion".
### DESCRIPCCION 
Para este repositorio te mostraremos paso a paso como programar los datos de identificacion de una persona  utilizando una interfaz ESP32, con ayuda de resistencias, pulsadores y una pantalla led, implicando tiempo de creación, edición y personalización para obtener un resultado gráfico impresionante que le dará un cambio muy superior.
#### MATERIAL
* Programa WOKWI
* Programa NODE-RED
* Interfaz ESP32
* Tres resistencias
* Tres pulsadores
* Una pantalla LCD 6X2 (12C)
### INSTRUCCIONES 
1. Abrimos el programa Wokwi y colocamos el codigo.

![.](https://github.com/AdalGuadarrama/PROYECTO-TARJETA-DE-IDENTIFICACION-/blob/main/py1.png)

![.](https://github.com/AdalGuadarrama/PROYECTO-TARJETA-DE-IDENTIFICACION-/blob/main/py2.png)

![.](https://github.com/AdalGuadarrama/PROYECTO-TARJETA-DE-IDENTIFICACION-/blob/main/py3.png)

![.](https://github.com/AdalGuadarrama/PROYECTO-TARJETA-DE-IDENTIFICACION-/blob/main/py4.png)

![.](https://github.com/AdalGuadarrama/PROYECTO-TARJETA-DE-IDENTIFICACION-/blob/main/py5.png)

![.](https://github.com/AdalGuadarrama/PROYECTO-TARJETA-DE-IDENTIFICACION-/blob/main/py6.png)

2. Agregamos las librerias ArduinoJson, Pubsubclient y LiquidCrystal 12C.

![.](https://github.com/AdalGuadarrama/PROYECTO-TARJETA-DE-IDENTIFICACION-/blob/main/py9.jpg)

3. En la interfaz ESP32 colocamos nuestras resistencias y pulsadores junto a la pantalla led.

![.](https://github.com/AdalGuadarrama/PROYECTO-TARJETA-DE-IDENTIFICACION-/blob/main/py7.jpg)

4. Despues hacemos las conexiones correspondientes.

![.](https://github.com/AdalGuadarrama/PROYECTO-TARJETA-DE-IDENTIFICACION-/blob/main/py8.jpg)

5. Abrimos el programa Node-red.

![.](https://github.com/AdalGuadarrama/PROYECTO-TARJETA-DE-IDENTIFICACION-/blob/main/s0.0.png)

6. Agregamos dos bloques llamodos mqtt in y json, agregamos los datos correspondientes para vincularlo a una conexión a internet.

![.](https://github.com/AdalGuadarrama/PROYECTO-TARJETA-DE-IDENTIFICACION-/blob/main/s1.png)

![.](https://github.com/AdalGuadarrama/PROYECTO-TARJETA-DE-IDENTIFICACION-/blob/main/py10.png)

7. En el bloqe de mqtt in damos doble click y en el simbolo del lapiz agregamos los datos correspondientes para vincularlo a una conexión a internet.

![.](https://github.com/AdalGuadarrama/PROYECTO-TARJETA-DE-IDENTIFICACION-/blob/main/py20.jpg)

![.](https://github.com/AdalGuadarrama/PROYECTO-TARJETA-DE-IDENTIFICACION-/blob/main/py21.jpg)

8. A continuacion repetimos el siguiente paso pero ahora dando click en el bloque json.

![.](https://github.com/AdalGuadarrama/PROYECTO-TARJETA-DE-IDENTIFICACION-/blob/main/py22.jpg)

9. Despues agregamos cuatro bloques llamados funtion, texto y colocamos a cada uno su codigo correspondiente (wokwi).

![.](https://github.com/AdalGuadarrama/PROYECTO-TARJETA-DE-IDENTIFICACION-/blob/main/s5..png)

![.](https://github.com/AdalGuadarrama/PROYECTO-TARJETA-DE-IDENTIFICACION-/blob/main/py17.1.jpg)

![.](https://github.com/AdalGuadarrama/PROYECTO-TARJETA-DE-IDENTIFICACION-/blob/main/py12.jpg)

![.](https://github.com/AdalGuadarrama/PROYECTO-TARJETA-DE-IDENTIFICACION-/blob/main/py13.jpg)

![.](https://github.com/AdalGuadarrama/PROYECTO-TARJETA-DE-IDENTIFICACION-/blob/main/py14.jpg)

![.](https://github.com/AdalGuadarrama/PROYECTO-TARJETA-DE-IDENTIFICACION-/blob/main/py15.jpg)

11. Por ultimo conectamos todos lo bloques y nos queda de la siguiente manera.

![.](https://github.com/AdalGuadarrama/PROYECTO-TARJETA-DE-IDENTIFICACION-/blob/main/py17.jpg)    

12. Para finalizar en  la pestaña de de Layout crearemos otro tabulador llamado Proyecto, dentro de el añadiremos cuatro grupos uno para nombre, edad, peso y estatura.

![.](https://github.com/AdalGuadarrama/PROYECTO-TARJETA-DE-IDENTIFICACION-/blob/main/py11.jpg)

### RESULTADOS 
* Visualizamos la interfaz y podremos manilular nuestro resltulados con el programa WOKWI.
* Podremos observar que los valores coinciden dentro del monitor serial y la interfaz como se muestra en la imagen.

![.](https://github.com/AdalGuadarrama/PROYECTO-TARJETA-DE-IDENTIFICACION-/blob/main/py23.png)

![.](https://github.com/AdalGuadarrama/PROYECTO-TARJETA-DE-IDENTIFICACION-/blob/main/py19.jpg)

![.](https://github.com/AdalGuadarrama/PROYECTO-TARJETA-DE-IDENTIFICACION-/blob/main/py24.jpg)

![.](https://github.com/AdalGuadarrama/PROYECTO-TARJETA-DE-IDENTIFICACION-/blob/main/py18.jpg)

#### CREDITOS
* Ing. Amairani Cisneros Hernandez
* Ing. Armando Garcia Linzaga
* Ing. Guadarrama Lome Adalberto

