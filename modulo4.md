## Control por radio y mando IR
# Ejemplo 1: control del robot utilizando otro microbit
En este ejercicio tienes que controlar los leds de maqueen a traves de una placa de microbit aparte, es decir cuando presione un boton u otro se cambie de color.

![image](video4ej1.png)
![image](video4ej2.png)

- [CÓDIGO](microbit-modulo_ampliacion_video4.hex)
- [CÓDIGO](microbit-modulo_ampliacion_video4_ejemplo2.hex)
- [VÍDEO](https://youtube.com/shorts/KYnD0uvBFBE?feature=share)

# Ejemplo 2: Control del robot a través de un mando
Primero tenemos que realizar un pequeño codigo, el cual necesitaremos para saber que numero da cada boton que pulsemos.
Dichos numeros tendremos que anotarlos.

 ![image](ejem2.1.PNG)
 - [CÓDIGO](microbit-ejem21.hex)

Una vez realizado el apartado anterior, realizaremos un nuevo programa, el cual controlará los motores para que el robot haga lo que nosotros queramos. 
En este caso es:

- Tecla UP - Num 198 - `IR HACIA DELANTE`
- Tecla DOWN - Num 199 - `IR HACIA ATRAS`
- Tecla LEFT - Num 200 - `GIRAR HACIA LA IZQUIERDA`
- Tecla RIGHT - Num 201 - `GIRAR HACIA LA DERECHA`
- Tecla ENTER - Num 202 - `PARAR`

El Código es simple, a cada acción se le ha asignado un número, cuando el robot detecte dicho número, realizará la acción que hemos configurado.

![image](ejem2.2.PNG)
- [CÓDIGO](microbit-ejem22.hex)
- [VÍDEO](https://youtube.com/shorts/NtKUifpcM6M?feature=share)

# Ejemplo 3: Sensor de sonido
El código para el sensor de sonido consiste en que al realizar un sonido, el sensor lo detecte y realize la acción que queramos, en este caso, es que el robot gire a la izquierda, se le cambie el color de los led y reproduzca un sonido y que cuando no reconozca ningun sonido, de pare, no reproduzca nungún sonido y cambie el color de los leds. 

![image](eje3.PNG)

- [CÓDIGO](microbit-sensor-de-sonido.hex)
- [VÍDEO](https://youtube.com/shorts/halrqbR2ZaA?feature=share)

# Ejemplo 4: Sensor de ultrasonido
El Código consiste en, el robot avanza, cuando el sensor de ultrasonido detecte un obstaculo a una distancia (marcada en el programa), cambiará de dirección, en este caso el cambio de dirección es al azar, mero se puede hacer que gire a la misma dirección simpre, cuano el sensor deje de detectar un objeto, volverá a avanzar.

![image](eje4.png)

- [CÓDIGO](microbit-sensor-ultrasonido.hex)
- [VÍDEO](https://youtube.com/shorts/RC3SltphyQk?feature=share)

# Ejemplo 5:Robot sigue linea
Este codigo consiste en que hay una linea negra por lo cual el robot maqueen la tiene que seguir, y cuando este fuera de la linea negra la intentara encontrar como el motor solo en direccion para adelante

![image](robotlinea.png)
- [CODIGO](microbit-mcqueen-linea.hex)
- [VIDEO](https://youtube.com/shorts/jKWAmS0edgU?feature=share)
