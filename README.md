Taller 1 Diseñando con Algoritmos
Sofía Gutiérrez
Clase Lógica
Es donde se desarrollan los procesos generales del código.
Atributos
inter: Es el numero de interacción (el usuario escoge).
datos: Lo que contiene cada palabra (Arreglos)
Relaciones con las Clases:
lluvia.
Viento.
Primavera.
Tornado.
Huracán.
Otoño.
Verano.
Invierto
Métodos:
pintar() Este método pinta todos los elementos.
key() Ejecuta cuando se presiona alguna tecla.
selectorInter() numero de interacción que el usuario escoge.
cambioTexto() cambios en el texto donde están los datos.
inicio() Ejecuta el inicio de la interacción donde el usuario escoge.
click(int, int) Se ejecuta cuando el usuario da click con el mouse.
lluvia() Se encarga de ejecutar ciertos procesos de la clase Lluvia.
viento() Se encarga de ejecutar ciertos procesos de la clase Viento.
primavera() Se encarga de ejecutar ciertos procesos de la clase Primavera.
tornado() Se encarga de ejecutar ciertos procesos de la clase Tornado.
huracan() Se encarga de ejecutar ciertos procesos de la clase Huracán.
otoño() Se encarga de ejecutar ciertos procesos de la clase Otoño.
verano() Se encarga de ejecutar ciertos procesos de la clase Verano.
invierno() Se encarga de ejecutar ciertos procesos de la clase Invierno.
Clase Lluvia
Atributos:
numCirculos: numero de circulos que caen
numRayos: numero de rayos.
vel: velocidad.
Metodos:
pintar() pinta los elementos.
mover() Ejecuta el movimiento de los elementos

Clase Viento
Atributos:
cir: Cantidad de círculos que rebotaran por el lienzo. (entero)
tam: Tamaño de los círculos.(entero)
pos: posición de los círculos.(entero)
vel: velocidad de los círculos.(vector)
Metodos:
pintar() pinta los círculos.
click() qué pasa cuando da click.
move() Ejecuta el movimiento de los círculos.
cambiarDir() Ejecuta el movimiento de los elementos.
Clase Primavera
Atributos:
numRev: numero de revoluciones de los petalos.
cir: círculo del centro:
centro: centro del círculo del medio.
Metodos:
pintar() pinta los elementos.
mover() Ejecuta el movimiento de los elementos.
Clase Tornado

Atributos:
numPenta: Este entero representa la cantidad de pentagono en el lienzo.
pos: posición de los pentágonos.(entero)
Metodos:
pintar() pinta los elementos.
Clase Huraca:
Atributos:
numTrian: La cantidad de triángulos en el lienzo.
Metodos:
pintar() pinta los elementos.
move() Ejecuta el movimiento de los elementos.
choque() Ejecuta una acción cuando dos triángulos se tocan.
Clase Otoño

Atributos:
numHojas: número de hojas.
vel: velocidad.
Metodos:
pintar() pinta los elementos.
move() Ejecuta el movimiento de los elementos.
camVel() cambiar la velocidad de los elementos.
Clase Verano
Atributos:
numSol: número límite de soles.
Metodos:
pintar() pinta los elementos.
move() Ejecuta el movimiento de los elementos.
cambiarTam() Este método se encarga de aumentar o disminuir el tamaño de los soles.
Clase Invierno
Clase que representa la cuarta interacción.
Atributos:
numCopos: Límite de cupos que puede recolectar.
posCopos: Posición copos.
vel: velocidad en que caen los copos.
Metodos:
pintar() pinta los elementos.
move() Ejecuta el movimiento de los círculos.
Click() Ejecuta la acción al hacer click.
