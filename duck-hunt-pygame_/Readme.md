# Duck Hunt – Prototipo Retro en Pygame

## Descripción
Este proyecto prototipo funcional inspirado en el videojuego clásico
Duck Hunt. El objetivo principal es recrear la mecánica básica del juego, enfocándose en
el movimiento del pato y la acción de disparo, manteniendo un estilo retro.

-El proyecto representa un avance inicial y no una versión final del videojuego.

## Paradigma Utilizado
Se utilizó Programación Estructurada, organizando el código mediante funciones y variables.
Este enfoque permite una comprensión clara del flujo del programa y facilita el aprendizaje
de los conceptos básicos de desarrollo de videojuegos.

## Instalación y Ejecución
1. Instalar Python 3.
2. Instalar la librería Pygame ejecutando:
   pip install pygame
3. Ejecutar el juego con:
   python main.py

## Controles
El juego está diseñado para ser utilizado con un mando clásico de Nintendo, reforzando la
experiencia retro del videojuego.

- Pad direccional izquierda/derecha: Movimiento del pato
- Botón A: Disparo

De forma alternativa, el juego también puede controlarse mediante teclado:
- Flechas izquierda/derecha: Movimiento
- Barra espaciadora: Disparo

## Explicación del Código
- main.py: Contiene toda la lógica del videojuego.
- Se utiliza un bucle principal para manejar eventos, movimiento y renderizado.
- Se implementa detección de colisiones entre el disparo y el pato.
- Al impactar el pato, su posición se reinicia como condición básica del juego.

## Estado del Proyecto
Este proyecto corresponde a un avance funcional enfocado en:
- Movimiento del personaje
- Acción básica
- Entorno simple
- Control retro mediante mando
