# Taller 1 Diseñando con Algoritmos- Valeria Ramirez

## Clase Logica

Es la clase donde se hace el procesamiento general del programa

**Atributos**

- interaccion:  Es el numero de interaccion que el usuario escogera.

- datos: Arreglo que contiene cada palabra del texto.

**Relaciones:**

La clase Logica tiene relaciones con las Clases:

- Sneik 
- Expan
- Bouncie
- Rainbou
- Trisoup
- Warld
- Worm
- Zum


**Metodos:**

- pintar()  Este metodo hace visible todos los elementos.

- inicio()  Ejecuta el inicio de la interaccion donde el usuario va escoger que interaccion ver.

- press(int, int)  Se ejecuta cuando el usuario da click con el mouse, los parametros son enteros son las posiciones del mouse.

- teclado()   Ejecuta cuando se presiona alguna tecla

- atras()  Se ejecuta cuando el usuario quiere ir al inicio a ir otra interaccion.

- seleccionarInteraccion() Este metodo se encarga de tomar el numero de interacccion que el usuario escoge.

- bouncie() Se encarga de ejecutar ciertos procesos de la clase Bouncie.

- expan()   Se encarga de ejecutar ciertos procesos de la clase Expan.

- trisoup() Se encarga de ejecutar ciertos procesos de la clase Trisoup.

- warld()  Se encarga de ejecutar ciertos procesos de la clase Warld.

- rainbou()  Se encarga de ejecutar ciertos procesos de la clase Rainbou.

- worm()  Se encarga de ejecutar ciertos procesos de la clase Worm.

- sneik() Se encarga de ejecutar ciertos procesos de la clase Sneik.

- zum() Se encarga de ejecutar ciertos procesos de la clase Zum.

- cambiosTexto() Este metodo hace cambios en el texto donde se saca todo los datos.


## Clase Bouncie

Clase que representa la primera interaccion. 

**Atributos:**

- bolas: entero que representa la cantidad de circulos que rebotaran por el lienzo.

- tam: entero que representa el tamaño de los circulos.

- pos: vector que representa la posicion de los circulos.

- vel: vector que representa la velocidad de los circulos.

- dirx: entero que representa la direccion en x del circulo.

- diry: entero que representa la direccion en y del circulo.

**Metodos:**

- pintar() pinta los circulos.

- mover() Ejecuta el movimiento de los circulos.

- colision() Ejecuta el cambio que sucede cuando dos circulos se tocan. 


## Clase Expan

Clase que representa la segunda interaccion. 

**Atributos:**

- cuantoMov: Este entero representa el limite de tamaño que tendran los elementos. 
- tamCirculo: Entero que representa el tamaño del primer circulo.
- tamMin:  Entero que representa el tamaño del segundo circulo.
- tamCua: Entero que representa el tamaño del cuadrado.


**Metodos:**

- pintar() pinta los elementos.

- mover() Ejecuta el movimiento de los elementos


## Clase Rainbou

Clase que representa la tercera interaccion. 

**Atributos:**

- numLineas: Este entero representa el limite de lineas que tendran los elementos. 



**Metodos:**

- pintar() pinta los elementos.

- mover() Ejecuta el movimiento de los elementos.

- cambiarLineas() Este metodo se encarga de aumentar o disminuir el tamaño de lineas.


## Clase Sneik

Clase que representa la cuarta interaccion. 

**Atributos:**

- cantComida: Este entero representa el limite de comida que puede recolectar. 
- comida: Posicion de la comida.
- pos: Vector que representa la posicion de la serpiente. 
- vel: Vector que representa la velocidad de la serpiente.
- largoSerp: Arraylist que contiene el tamaño de la serpiente.
- tam: Tamaño del fragmento de la serpiente.
- vivo: Boolean que representa la vida de la serpiente.


**Metodos:**

- pintar() pinta los elementos.

- mover() Ejecuta el movimiento de los circulos.

- teclado() Ejecuta las acciones al presionar una tecla.

- comer() Ejecuta la accion de la serpiente al estar en contacto con una comida.

- revivir() volver a iniciar la interaccion.

- nuevaComida()  cuando la serpiente come, se crea otra comida.


## Clase Trisoup

Clase que representa la quinta interaccion. 

**Atributos:**

- cantTriangulos: Este entero representa la cantidad de triangulos en el lienzo. 


**Metodos:**

- pintar() pinta los elementos.

- mover() Ejecuta el movimiento de los elementos.


## Clase Warld

Clase que representa la sexta interaccion. 

**Atributos:**

- revolu: Este entero representa la cantidad de revoluciones que haran los circulos. 


**Metodos:**

- pintar() pinta los elementos.

- mover() Ejecuta el movimiento de los elementos.

- cambiarVelocidad() Este metodo se encarga de cambiar la velocidad de la revolucion de los elementos.


## Clase Worm

Clase que representa la septima interaccion. 

**Atributos:**

- largo: Este entero representa el largo del gusano. 


**Metodos:**

- pintar() pinta los elementos.

- mover() Ejecuta el movimiento de los elementos.


## Clase Zum

Clase que representa la octava interaccion. 

**Atributos:**

- cantidad: Este entero representa la cantidad de moscas en el lienzo. 


**Metodos:**

- pintar() pinta los elementos.

- mover() Ejecuta el movimiento de los elementos.

- colision() Ejecuta una accion cuando dos moscas se tocan.




