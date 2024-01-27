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
1. Abrimos el programa Worwi y colocamos el codigo.
2. Agregamos las librerias ArduinoJson, Pubsubclient y LiquidCrystal 12C.
3. En la interfaz ESP32 colocamos nuestras resistencias y pulsadores junto a la pantalla led.
4. Despues hacemos las conexiones correspondientes.
5. Abrimos el programa Node-red.
6. Agregamos dos bloques llamodos mqtt in y json.
7. En el bloqe de mqtt in damos doble click y en el simbolo del lapiz agregamos los datos correspondientes para vincularlo a una conexión a internet.
8. A continuacion repetimos el siguiente paso pero ahora dando click en el bloque json.
9. Despues agregamos cuatro bloques llamados funtion y  colocamos a cada uno su codigo correspondiente (wokwi).
10. Por ultimo agramos otro bloque llamado texto, damos click y colocamos los datos correspondientes.
11. Para finalizar en  la pestaña de de Layout crearemos otro tabulador llamado Proyecto, dentro de el añadiremos cuatro grupos uno para nombre, edad, peso y estatura.
### RESULTADOS 
* Visualizamos la interfaz y podremos manilular nuestro resltulados con el programa WOKWI.
* Podremos observar que los valores coinciden dentro del monitor serial y la interfaz como se muestra en la imagen.


