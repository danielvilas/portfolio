---
title: '"Plagiando" y "Falsificando"'
summary: Practicas, ChatGPT y sus usos...
date: 2025-04-22
authors:
  - admin
tags:
  - IA
  - UNIR
  - Master
image:   
  caption: 'Image credit: [**Luke Chesser**](https://unsplash.com/es/@lukechesser?utm_content=creditCopyText&utm_medium=referral&tm_source=unsplash) en [**Unsplash**](https://unsplash.com/es/fotos/graficos-de-analisis-de-rendimiento-en-la-pantalla-de-un-portatil-JKUTrJ4vK00?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash)'
---

## Falsificando

Hoy en día quien mas quien menos tiene acceso a un agente de IA que le ayude a crear contenido. Pues bien, ya han llegado las
primeras tareas del master y nos piden hacer un informe de un experimento, sin realizarlo. Es decir nos tenemos que inventar
los resultados. En realidad la practica era de redacción general y del planteamiento del experimento, asi que tampoco es tan raro.
Asi que en las instrucciones nos instan a inventarnos datos que puedan pasar como reales, usando si queremos una IA generativa.

Bueno como para ello necesitaba un gráfico de entrenamiento de una Red Neuronal, le he pedido a chatGPT que me haga código para
crear la serie y pintarla con python. Y me ha generado un código que genera datos muy creíbles y muy fácilmente.

'''text
Buenas, necesito un código python que me genere una gráfica tipo error loss de un proceso de entrenamiento de un LLM, puedes ayudarme
'''

Ese simple commando genera el código para crear las gráficas. A partir de ahí podemos pedirle algunos cambios o hacerlos nosotros
mismos por nuestra cuenta. Y con esto y un bizcocho ya tenemos nuestros datos Falsos, hemos hecho "P-Hacking" y todos contentos.

Y llegamos al problema:

### Es demasiado fácil

No hemos tenido ni que poner dato tras dato hasta que nos haya salido las curvas que queremos, ni pensar que ecuaciones podrían
describir los datos, ni escribir el código. Solo con 23 palabras ya tenemos todo lo que necesitamos. Y eso me ASUSTA.

Me preocupa, por que ... ¿Qué garantías tenemos ahora que los datos publicados vienen de fuentes reales y no de una IA?. Ya  sin IA, tenemos casos de papers retirados por "P-Hacking" como para encima que esto te lo haga una IA en un par de segundos.

## Plagiando

Otra forma donde nos ayuda es con la redacción de texto, para otra practica, me piden un "articulo" en latex y lo estaba
codificando/escribiendo con VS-Code y por cosas del azar se me activo el copilot (reinicio de los contadores mensuales). Desde ese
momento me empezó a sugerir texto con unas expresiones largas y sobre-explicativas. Cuatro palabras y un tabulador resultan en un
párrafo larguísimo y coherente con sentido. Ahora bien, si hablamos de correctitud y precisión,...

Si lees en diagonal el texto pasa muchos controles, pero como sepas y leas a fondo.... encuentras muchos errores, como que tiende a
repetir, se inventa citas (pero se acerca), a veces se contradice. Pero si lo controlas, revisa lo que pone te puede acelerar mucho.

Para escribir rápido, puede ayudar mucho, pero si no se controla. Se cometerán muchos errores. Por ejemplo, ¿de donde se saca lo que
dice? Lo que pongamos en los artículos, debemos citarlo, y copilot no te dice de donde lo saca. Y sera muy fácil plagiar, sin saber
que lo estamos haciendo.

Eso si, donde más se luce copilot es en tareas repetitivas, como describir los parámetros de una función o replicar la estructura de
posicionar 4 imágenes varias veces.

## Uso Ético del la IA Generativa

Al final del dia, la IA es una herramienta y sera tan buena o tan mala como el que la usa. Mientras revisemos con calma y tengamos
un origen al que atribuir las citas, no estaremos plagiando, pero sino cambiaremos el esfuerzo de escribir por nosotros, por el
esfuerzo de validar los textos y las citas. Y para tratar los datos la IA nos puede ayudar con el código de procesado, representación, etc. Pero nunca para generar los datos.

Y el problema es que es **demasiado fácil**, tan fácil, que, de hecho, no te das cuenta, tienes que fijarte.
