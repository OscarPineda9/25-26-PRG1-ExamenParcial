# Respuesta Pregunta 3

## ¿Hay error en el fragmento?

do {

    if (Math.random() < PORCENTAJE_EXITO_GUERRERO) {
        vidaVampiro = vidaVampiro - DAÑO_ESPADA;
        System.out.println("¡El vampiro recibe la ostia!");
    } else {
        System.out.println("¡El vampiro esquiva la ostia!");
    }

    boolean vampiroVivo = vidaVampiro > 0;
}

## Respuesta
El if esta bien implementado. Hay un error al final con boolean vampiroVivo = vidaVampiro > 0 no pondria como boolean primero que todo y no esta estructurado o bien puesto ahi.

## Solucion de Problema
Como esta es una condicion por la cual puede terminar la pelea la pondria en el argumento del bucle para que pueda terminar el bucle cuand el vampiro este muerto y no volverlo a poner o repetirlo en el codigo.
