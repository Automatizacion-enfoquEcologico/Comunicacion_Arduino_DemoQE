# Comunicacion_Arduino_DemoQE

Contiene código en lenguaje C para el DemoQE, destinado a comprobar el funcionamiento de la comunicación serial con el modulo externo (Arduino) desde la terminal en la PC. 

El programa permite activar las salidas y observar la data leída por el modulo externo cuando este está corriendo su rutina de funcionamiento normal.

Para activar la salida desde la terminal se envía: 

+ 0xFF : RIEGO_ON.
+ 0xF0 : RIEGO_OFF.
