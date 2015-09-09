# Calculadora
Esta calculadora tipo excel, además de hacer cálculos básicos al propio estilo de una hoja de cálculo normal, permite operar con matrices.
Existe una lista de funciones desplegable que, una vez elegida la deseada, se muestra en la caja de comandos.
La caja de comandos permite escribir cualquier comando como si fuera la propia consola del navegador, con la diferencia que hay que pulsar el botón "ejecutar" para realizar la acción deseada.
Por otro lado, la otra caja muestra en pantalla, una vez pulsado el botón correspondiente, la matriz deseada que hayamos guardado.

Un ejemplo básico de uso: Cálculo de matriz transpuesta.
  En primer lugar debemos escribir en la hoja la matriz que queremos transponer.
  A continuación debemos elegir la función "guardarMatriz". Debemos ponerle un nombre a la matriz y escribirlo a modo de operación, indicando la casilla inicial y final de la matriz. Por ejemplo, una matriz de 3x3: x=guardarmatriz(A1,C3)
  El siguiente paso, después de ejecutar esta línea de comando, será elegir la función "transpuesta", y volver a guardar el resultado en otra variable. Por ejemplo: y=transpuesta(x)
  Para finalizar, si queremos ver la matriz resultado, debemos escribir el nombre de la matriz resultado en el recuadro inferior y pulsar el botón "Display". En nuestro caso escribiríamos "y" y, en las casillas de la derecha de la matriz original, aparecerá la matriz resultado que buscábamos.
