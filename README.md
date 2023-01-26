# Practica Accesibilidad

El objetivo de esta practica es mejorar la accesibilidad de la página web (en este caso mi portfolio)
Se revisarán diferentes puntos con tal de que siga la normativa de la W3C

## Lighthouse

Para poder comprobar los fallos que tiene nuestro sitio web Utilizamos dicha herramienta que nos dará una valoración de nuestra página.


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

En este apartado abarcaremos todos los problemas de accesibilidad que no se puede comprobar con Lighthouse. Cumple -> Sigue la normativa, Comprobado -> Sigue la normativa, no obstante no incorpora los elementos que pide el apartado (ej: no tiene audio no hace falta hacer una transcripción) o simplemente los cumple indirectamente, Arreglado -> Problema solucionado, Mejorado -> El problema esta solucionado y se ha mejorado la página para optimizar o mejorar dicho apartado.

### Principio 1 – Perceptible
#### Pauta 1.1 – Textos alternativos
+ 1.1.1 Contenido sin texto Nivel A -> Arreglado
#### Directriz 1.2 – Medios basados en el tiempo
+ 1.2.1 Solo audio y solo video (pregrabado) Nivel A -> Comprobado (Cumple "no tengo audio")
+ 1.2.2 Subtítulos (pregrabados) Nivel A -> Cumple
+ 1.2.3 Descripción de audio o alternativa de medios (pregrabada) Nivel A -> Comprobado (No se utilza audio en la página)
+ 1.2.4 Subtítulos (en vivo) Nivel AA -> Comprobado (No se utilza audio en la página)
+ 1.2.5 Descripción de audio (pregrabado) Nivel AA -> Comprobado (No se utilza audio en la página)
#### Directriz 1.3 – Adaptable
+ 1.3.1 Información y Relaciones Nivel A -> Comprobado (Cumple)
+ 1.3.2 Secuencia significativa Nivel A -> Comprobado (G57,Cumple)
+ 1.3.3 Características sensoriales Nivel A -> Comprobado (Cumple)
#### Pauta 1.4 – Distinguible
+ 1.4.1 Uso del color Nivel A -> Cumple
+ 1.4.2 control de sonido Nivel A -> Comprobado, no hay audio en la página web
+ 1.4.3 Contraste (mínimo) Nivel AA -> Cumple
+ 1.4.4 Cambiar el tamaño del texto Nivel AA -> Cumple (No pierde funcionalidad con el zoom)
+ 1.4.5 Imágenes de texto Nivel AA -> Cumple
### Principio 2 – Operable
#### Pauta 2.1 – Teclado accesible
+ 2.1.1 Teclado Nivel A -> Cumple
+ 2.1.2 Sin trampa de teclado Nivel A-> Cumple
#### Pauta 2.2 – Tiempo suficiente
+ 2.2.1 Tiempo ajustable Nivel A -> Comprobado (en la página no hay ningín elemento que requiera tiempo)
+ 2.2.2 Pausa, Detener, Ocultar Nivel A -> Comprobado (No hay desplazamiento automático)
#### Pauta 2.3 – Convulsiones y Reacciones Físicas
+ 2.3.1
Tres destellos o por debajo del umbral Nivel A -> Comprobado (No hay nada que cambie más de 3 veces en 1 segundo)
#### Directriz 2.4 – Navegable
+ 2.4.1 Bloques de derivación Nivel A -> Cumple ("nav")
+ 2.4.2 Página titulada Nivel A -> Mejorado (title más descriptivo "Cumple") 
+ 2.4.3 Orden de enfoque Nivel A -> Cumple
+ 2.4.4 Propósito del enlace (en contexto) Nivel A -> Arreglado (title y alt)
+ 2.4.5 Múltiples formas Nivel AA -> Cumple (tiene enlaces para navegar por la página "no tiene para ir a otras ya se que es una single page")
+ 2.4.6 Encabezados y etiquetas Nivel AA -> Cumple
+ 2.4.7 Enfoque Visible Nivel AA -> Cumple
#### Directriz 2.5 – Modalidades de entrada
+ Facilitar a los usuarios operar la funcionalidad a través de varias entradas más allá del teclado. ->  Sí (ya que aparte del teclado se utiliza ratón)
### Principio 3 – Comprensible
#### Pauta 3.1 – Legible
+ 3.1.1 Idioma de la página Nivel A -> Cumple
+ 3.1.2 Idioma de las partes Nivel AA -> Cumple
#### Directriz 3.2 – Predecible
+ 3.2.1 Enfocado Nivel A -> Cumple
+ 3.2.2 en la entrada Nivel A -> Cumple
+ 3.2.3 Navegación consistente Nivel AA -> Comprobado (Sigue un orden "solo una página" ya que es una single page, cumple la normativa)
+ 3.2.4 Identificación consistente Nivel AA -> Cumple
#### Pauta 3.3 – Asistencia de entrada
+ 3.3.1 Error de identificación Nivel A -> Cumple
+ 3.3.2 Etiquetas o instrucciones Nivel A -> Cumple 
+ 3.3.3 Sugerencia de error Nivel AA -> Cumple
+ 3.3.4 Prevención de Errores (Legal, Financiero, Datos) Nivel AA -> Comprobado (Cumple, los datos al rellenar el formulario son reversibles "si existe algún error ej: poner mal el correo sin @", el usuario puede comprobar los datos antes de enviarlos no obstante como no hay servidor el usuario no puede ver los datos enviados).ç
### Principio 4 – Robusto
#### Pauta 4.1 – Compatible
+ 4.1.1 análisis Nivel A ->  Cumple
4.1.2 Nombre, Rol, Valor Nivel A -> Cumple (H88)
