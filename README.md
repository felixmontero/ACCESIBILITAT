# Practica Accesibilidad

El objetivo de esta practica es mejorar la accesibilidad de la página web (en este caso mi portfolio)
Se revisarán diferentes puntos con tal de que siga la normativa de la W3C

## Lighthouse

Para poder comprobar los fallos que tiene nuestro sitio web Utilizamos dicha herramienta que nos dará una valoración de nuestra página.

--FOTOS

### PERFORMANCE

+ Eliminate render-blocking resources
+ Properly size images
+ Serve images in next-gen formats -> Arreglado
+ Minify CSS -> Arreglado
+ Enable text compression -> Arreglado

### ACCESIBILIDAD

+ Links do not have a discernible name -> Arreglado (He puesto un título a las etiquetas para que google no tengas problema en leerlo)

![image](https://user-images.githubusercontent.com/91874727/213931304-b6a61a5a-b3f1-45a8-8cab-8e68486fee77.png)


### BEST PRACTISE

Arreglado al mejorar la página. Sin errores.

## Correciones de forma manual

En este apartado abarcaremos todos los problemas de accesibilidad que no se puede comprobar con Lighthouse.

### Principio 1 – Perceptible
#### Pauta 1.1 – Textos alternativos
+ 1.1.1 Contenido sin texto Nivel A -> Arreglado
#### Directriz 1.2 – Medios basados en el tiempo
+ 1.2.1 Solo audio y solo video (pregrabado) Nivel A -> Comprobado (Se cumple "no tengo audio")
+ 1.2.2 Subtítulos (pregrabados) Nivel A -> Comprobado (Se cumple)
+ 1.2.3 Descripción de audio o alternativa de medios (pregrabada) Nivel A-> Comprobado (No se utilza audio en la página)
+ 1.2.4 Subtítulos (en vivo) Nivel AA -> Comprobado (No se utilza audio en la página)
+ 1.2.5 Descripción de audio (pregrabado) Nivel AA -> Comprobado (No se utilza audio en la página)
#### Directriz 1.3 – Adaptable
+ 1.3.1 Información y Relaciones Nivel A -> Comprobado (Se Cumple)
+ 1.3.2 Secuencia significativa Nivel A -> Comprobado (G57, se cumple)
+ 1.3.3 Características sensoriales Nivel A -> Comprobado (Se cumple)
#### Pauta 1.4 – Distinguible
+ 1.4.1 Uso del color Nivel A -> Se cumple
+ 1.4.2 control de sonido Nivel A -> No hay audio en la página web
+ 1.4.3 Contraste (mínimo) Nivel AA -> Cumple con la normativa
+ 1.4.4 Cambiar el tamaño del texto Nivel AA -> Cumple (No pierde funcionalidad con el zoom)
+ 1.4.5 Imágenes de texto Nivel AA -> Comprobado (La página cumple con los requerimietos)
### Principio 2 – Operable
#### Pauta 2.1 – Teclado accesible
+ 2.1.1 Teclado Nivel A -> Comprobado (Cumple)
+ 2.1.2 Sin trampa de teclado Nivel A-> Comprobado
#### Pauta 2.2 – Tiempo suficiente
+ 2.2.1 Tiempo ajustable Nivel A -> Comprobado (en la página no hay ningín elemento que requiera tiempo)
+ 2.2.2 Pausa, Detener, Ocultar Nivel A -> Comprobado (No hay desplazamiento automático
#### Pauta 2.3 – Convulsiones y Reacciones Físicas
+ 2.3.1
Tres destellos o por debajo del umbral Nivel A -> Comprobado (No hay nada que cambie más de 3 veces en 1 segundo)
#### Directriz 2.4 – Navegable
