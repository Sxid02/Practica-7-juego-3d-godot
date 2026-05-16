# Proyecto Godot 3D - Personaje, Monedas y Recolección

Este es un proyecto desarrollado en **Godot 4.x** donde el objetivo es crear una pequeña escena 3D interactiva. El personaje puede moverse, saltar y recoger monedas.

## **Características principales**
- **Movimiento del personaje**: El personaje puede moverse en las 4 direcciones (adelante, atrás, izquierda y derecha).
- **Salto**: El personaje puede saltar con la tecla **espacio**.
- **Recolección de monedas**: Cuando el personaje entra en contacto con una moneda, esta desaparece y se añade al contador.

## **Estructura del Proyecto**
El proyecto está organizado en las siguientes carpetas:

res://

├─ Models/ # Modelos 3D de las plataformas y monedas

├─ Scenes/ # Escenas principales del juego
│ ├─ Main.tscn

│ ├─ Player.tscn

│ └─ coin_gold.tscn

├─ Scripts/ # Scripts de la lógica del juego

├─ Materials/ # Materiales de las plataformas y objetos

└─ Assets/ # Archivos adicionales (sonidos, imágenes)

## **Video de demostración**
A continuación se muestra un GIF donde se puede ver cómo funciona el movimiento del personaje y la recolección de monedas .
![GIF de demostración](gift3D.gif)
