# Escribe qué es un fork y para qué sirve upstream. 
Un fork es una copia en local de un proyecto que está en la web
upstream es el nombre que se da al origen que está en la web, cuyo dueño no soy yo. S ediferencia así del origin que es el mio.

![Captura 1](capturas/Captura1.png)

#  Explica por qué la rama parte de dev y no de main.
Por la filosofía de flujos de programación, es mejor tener todo aquello que se va a modificar que cuelgue de una rama dev, para podr interpretar el main como lo que está en producción y lo demás está pendiente de pasar a producción.

# Explica qué es un conflicto en Git y por qué se va a producir aquí.
Se ha creado una rama que modificaba una línea de un  fichero. Por otro lasdo se ha creado otra rama que modificaba con otro cambio la misma línea del mismo fichero. Pero esos cambios no están aún subidos mezclados, por lo que habrá un conflico donde me preguntará como resolverlo y con cuál de los dos cambios quedarme.

# Explica qué revisaste en la pestaña Files changed y por qué es útil hacerlo antes de mergear. 
Revisé lo que había cambiado con respecto al original. Es útil para estar seguro d ellos cambios que se van a confirmar.

# Explica qué significan los marcadores <<<<<<<, ======= y >>>>>>> y qué criterio usaste para decidir qué versión conservar. 

Indican , cuando hay un conflicto, la parte del código, donde empieza y acaba cada conflicto (con «««)  y con = = =   en cada conficto se detemina las opciones que provocan el conflico para que elija alguna de las opcions como definitivas, para resolver el conflicto.

# Adjunta la captura 8 (git log --oneline). Cierra el diario con un párrafo libre: qué te ha resultado más difícil y qué tiene más sentido ahora que antes de la clase.

Lo que me ha resultado más dificil es resolver los conflictos y sobre todo hacer aparecer el menú emergente para poder pulsar y decidir con qué cambio quedarme.
Ahora puedo enseñar a mis alumnos/os cómo controlar que no se pisen unos cambios con otros cuando trabajen en equipo.
Antes yo usaba subversion y me hacía falta ponerme al día con el uso de git