# Shooter Espacial - Introducción a la Programación (C++)

<p align="center">
  Juego de consola desarrollado en C++ donde el jugador debe destruir aliens mientras evita meteoritos.
</p>

<p align="center">

![C++](https://img.shields.io/badge/language-C%2B%2B-blue)
![Game](https://img.shields.io/badge/type-console%20game-green)
![IDE](https://img.shields.io/badge/IDE-Zinjai-orange)

</p>

---

## Descripción

Shooter espacial desarrollado en **C++** utilizando **programación orientada a objetos**.

El jugador controla una nave dentro de un área delimitada en la consola y debe destruir aliens que cruzan la pantalla mientras evita meteoritos que caen desde arriba.

Cada enemigo tiene una velocidad diferente y otorga distintos puntajes.

El juego termina cuando el jugador pierde todas sus vidas.

**Todos los elementos del juego están dibujados utilizando caracteres ASCII**

---

## Mecánicas del Juego

- Movimiento libre dentro del área de juego
- Sistema de disparo
- Aliens que se mueven horizontalmente
- Meteoritos que caen desde arriba
- Sistema de vidas
- Sistema de puntaje
- Mensajes aleatorios al destruir enemigos

---

## Controles

| Tecla | Acción |
|------|------|
| W | Mover arriba |
| S | Mover abajo |
| A | Mover izquierda |
| D | Mover derecha |
| Espacio | Disparar |

---

## Tecnologías Utilizadas

- C++
- Programación Orientada a Objetos
- Librería `conio2`
- Zinjai editor

---

## Arquitectura del Proyecto

El proyecto está organizado en varias clases principales.


### Pantalla
Se encarga de dibujar los bordes del área de juego y mostrar mensajes.

### Jugador
Controla el movimiento del jugador y el sistema de disparo.

### Enemigo
Clase base para los enemigos del juego.

### Alien
Enemigo que se mueve horizontalmente por la pantalla.

### Meteorito
Enemigo que cae verticalmente desde la parte superior.

### Juego
Controla el loop principal, las colisiones, las vidas y el puntaje.

---

## Gameplay

El jugador debe destruir aliens que cruzan la pantalla mientras evita meteoritos.

Los aliens más rápidos otorgan más puntos.

Cuando el jugador pierde todas sus vidas aparece la pantalla de **Game Over**.

---

## Capturas de Pantalla

<p align="center">

<img src="https://github.com/user-attachments/assets/c019cceb-c580-42ea-93f4-3fb1768692d7" 
width="45%" 
style="border:3px solid #555; margin:10px; border-radius:6px;">

<img src="https://github.com/user-attachments/assets/3e55f217-eaa1-441b-8214-5385aaef3ca4" 
width="45%" 
style="border:3px solid #555; margin:10px; border-radius:6px;">

</p>



## Autor

Lucas Boffa  
Tecnicatura en Diseño y Desarrollo de Videojuegos  
UNL


