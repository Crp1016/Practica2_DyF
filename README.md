\# Práctica 2



\## Tabla de controles



|**Input Actions**|**Keyboard**|**GenericUSBController**|**mando XInput**|
|-|-|-|-|
|**Flipper Derecho**|flecha derecha|Botón 1|Hombro derecho|
|**Flipper Izquierdo**|flecha izquierda|Botón 2|Hombro izquierdo|
|**Lanzador**|flecha arriba|Botón 3|Botón frontal inferior|
|**Reiniciar**|R|Botón 4|Botón derecho especial|



\## Valores físicos



**Bola**



|**Mass (kg)**|0,5|
|-|-|
|**Linear Damping**|0,01|
|**Angular Damping**|0,0|



**Material físico**



|**Friction**|0,05|
|-|-|
|**Static Friction**|0,0|
|**Restitution**|0,75|
|**Density**|1,0 g/cm³|
|**Sleep Linear Velocity Threshold**|1,0|
|**Sleep Angular Velocity Threshold**|0,05|
|**Sleep Counter Threshold**|4|



\## Mejoras implementadas



**ESCENARIO:**



Se ha cambiado el color de las paredes.

Se ha añadido...



* SM\_TanukiWhacker + SM\_TanukiWhacker\_Hammer
* SM\_ArcadeCabinet\_04
* SM\_MoneyExchange
* SM\_CraneMachine\_01 y dentro de ella:



SM\_Plushie\_Cat

SM\_Plushie\_Donut

SM\_Plushie\_Kiwi

SM\_Plushie\_Onigiri

SM\_Plushie\_Penguin

SM\_Plushie\_Person

SM\_Plushie\_Squid

SM\_Plushie\_Tanuki

SM\_Plushie\_Toast



* SM\_AirplaneSimulator\_01
* BasketballGame



*Fab*



* Vending\_Machine\_2\_LOWPOLY
* Billiard\_Pool\_Table
* Game\_Controller
* SciFi\_windows
* Simple\_Space\_poster\_\_-\_low\_poly\_-
* Worn\_Sci-Fi\_Retro\_Travel\_Poster



**ELEMENTOS DE JUEGO:**



Dentro de la función Puntuar Elemento en el Event Hit he hecho que puntúen también dianas y gomas.

Se suman distintos valores a la puntuación según el Tag acorde a lo que considero que es más fácil de golpear o se golpea más veces (más fácil->menos puntos se suman):



|Bouncers|50|
|-|-|
|Diana|30|
|Goma|10|



