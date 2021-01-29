# NFLCuadro
Juego de lotería cuadro para el Super Bowl [sitio](https://lodoz.github.io/NFLCuadro/)

## ¿y esto? ¿Cómo se juega?
###Preparación
El juego es una lotería y se prepara antes de que inicie el partido, para que todos estén enterados de cómo están participando y no se hacen movimientos durante el partido.
Se hace una cuadricula para registrar el marcador para el Super Bowl, de 10 columnas por 10 filas y así se generan 100 casillas, donde se encuentran todas las coordenadas posibles con los números del 0 al 9, tanto en horizontal como vertical.
Este cuadro tiene también una fila adicional superior y una columna adicional izquierda, para poner los números de las unidades, con las que se va a jugar.
Y tiene una fila adicional con el equipo en horizontal y otra columna para el equipo en horizontal, donde se representa el resultado del equipo que va en ese eje. 
Una vez listo el cuadro, que es lo que se incluye en este proyecto, estas listo para el sorteo. 

###Sorteo
El sorteo tiene que ser antes del partido, y la recomendación es que sea 2 horas antes, ya que, si es la primera vez, toma mucho tiempo la coordinación. 
Se sortea o venden los cuadros, como son 100 lo más fácil es ponerle un precio por cuadro, y dejar que los participantes compren tantos cuadros quieran, si no se completa o alguien no quiere comprar tantos cuadros se puedan revender en otros participantes. 
Entre los participantes se sortea o se elige el orden en el que se elegirán los cuadros, y se va a seguir el mismo orden toda la ronda de selección. Una vez ordenados, cada participante, pones sus iniciales en el cuadro que seleccione, se selecciona entre 1 o 3 cuadros para dar oportunidad a que todos puedan seleccionar cuadros cuando todavía hay disponibilidad, y se hace por rondas, las que sean necesarias para terminar de llenar los 100 cuadros de selección. 
Si sobran cuadros se pueden vender a cualquier participante, o en su defecto los compra el organizador. 
Continua la rifa de los números, estos se rifan independientes los de las columnas de los de las filas, solo se puede los números que son unidades, del 0 al 9, y conforme se van sorteando se va llenando la fila de números, primero un eje y después el otro. 
Al final se rifan los equipos, uno para vertical y otro para horizontal. 

###Ganadores y premios
Son 4 premios iguales, que se dividen la bolsa acumulada de la venta de los cuadros. Durante el partido, los marcadores parciales de cada cuarto cuartos y el marcador final determinan a los ganadores cada premio.
Para determinar el ganador se toman las unidades del marcador de cada equipo, y se ubica el eje del equipo y la unidad del marcador correspondiente a ese equipo, para obtener una coordenada, y la otra coordenada con el marcador y equipo contrario y el ganador son las iniciales de donde concuerden los registros en la matriz, será el ganador de ese cuarto, por ejemplo, si el primer cuarto termina: CHIEFS 7 – 3 49ERS el ganador será cuyo cuadro cruce el 3 con el 7 en la posición seleccionada. Si en el medio tiempo el partido termina CHIEFS 10 – 10 49ERS el ganador se determina con las unidades del marcador, en este ejemplo 0 y 0, y así por cada cuarto. 
¡Al finalizar el partido se tienen los 4 ganadores de los cuadros y el campeón del Super Bowl!

Este cuadro tiene el ejemplo del SuperBowl LIV [sitio](https://lodoz.github.io/NFLCuadro/)

## Por hacer
Queda mucho por mejorar, automatizar y perfeccionar, si te sirve, y tienes alguna sugerencia o hacer Pull request a alguna mejora. 
Bienvenid@!

lodoz
