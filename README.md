# P2_Visuals-to-Disseny-en-Moviment__

## Briefing

El briefing propone la creación de una pieza audiovisual de 10 segundos en formato vertical (1080 × 1920), que explora la creatividad visual a través del movimiento, el color y los efectos digitales, con libertad para experimentar con técnicas de animación y programación creativa.

## Concepto

Tres composiciones generativas desarrolladas con Processing, todas basadas en conceptos del libro *The Nature of Code* de Daniel Shiffman: sistemas de partículas, campos de flujo y fuerzas. Miles de partículas con reglas simples generan dibujos complejos que nunca se repiten. Del mismo sistema surgen tres lecturas visuales diferentes.

## Composición 1 (principal): emisores y formas matemáticas

Tres "pinceles invisibles" recorren la pantalla siguiendo fórmulas matemáticas (una flor, una curva de Lissajous y una espiral) y van soltando miles de partículas de colores. Cada capa usa una paleta distinta de tres colores (atardecer, océano, bosque, fuego o neón) sobre fondo negro, con estela de luz.

**Interacción:** el ratón atrae el centro de los dibujos y controla cuánto se desvanece la estela. Al mantener el clic, las partículas cercanas se alejan.

## Composición 2: campo de flujo en tonos fríos

Mil quinientas partículas se dejan llevar por una corriente invisible creada con ruido de Perlin (`noise()`), como hojas en un río. Los trazos forman ríos y remolinos de luz en azul, cian, turquesa y violeta sobre un fondo azul muy oscuro.

**Interacción:** cada clic lanza una nueva corriente de partículas de otro color (blanco hielo, lavanda, menta, cobalto) que serpentea por el campo hasta desvanecerse. El ratón en horizontal cambia lo rizado del campo.

## Composición 3: remolinos luminosos

Dos remolinos invisibles, que giran en sentidos contrarios y se pasean por la pantalla, mantienen a miles de partículas en espirales vivas e irregulares. Las partículas se suman con un efecto de brillo (`blendMode(ADD)`) en paletas de aurora, ámbar, hielo y rosa.

**Interacción:** cada clic crea una nube de chispas pequeñas que el remolino más cercano absorbe y enrosca hacia su centro mientras se apagan.

## Movimiento

- **Sistemas de partículas:** muchos objetos pequeños que nacen, se mueven y se eliminan.
- **Fuerzas:** rozamiento, repulsión, atracción y giro modifican la velocidad de cada partícula.
- **Campos de flujo:** una malla invisible de ruido indica a cada partícula hacia dónde ir.
- **Oscilación y órbitas:** senos y cosenos crean pétalos, lazos y espirales.
- **Azar suave:** `noise()` mueve los centros de forma orgánica, sin saltos.

## Color y efectos visuales

Fondos oscuros con colores intensos: paletas de tres colores en la primera pieza, tonos fríos en la segunda y brillos aditivos en la tercera. El fondo semitransparente que se repinta en cada fotograma deja estelas de luz y da profundidad, y refuerza la estética digital.

## Objetivo

Crear tres piezas visuales dinámicas que combinan programación creativa, reglas simples y movimiento para generar una experiencia abstracta, hipnótica e impredecible. El resultado es un vídeo de 10 segundos (250 fotogramas a 25 fps) que muestra la pieza principal en una maqueta de pantalla urbana.

## Herramientas

- **Processing:** generación de gráficos y animación. Exporta los fotogramas en PNG.
- **After Effects:** montaje de las secuencias e integración en las maquetas.
- **GitHub:** repositorio público con el código de las tres composiciones.
