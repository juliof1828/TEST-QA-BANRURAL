En la linea 44 encontramos un error ya que anteriormente tenia el Math.floor en "*10" y este debe ser mayor a 100* asi tambien era faltante en + 1 recordemos que esto debido a que el programa reconoce los dato de 0 en adelante y no en 1.

En la linea 46 notamos que "const ATTEMPS = 5;" siendo ATTEMPS y el resto de la linea esta de más ya que realmente se escribe attempts que en ingles significa intentos los cuales trata de definir que son 5 cuando en realidad son 10, los intentos los nombramos en la linea 66.

En la line 58 estamos nombrando constantes "guess" y Guess" y no variables como estaba anteriormente "let userGuess = guessFiel.value;"

En la linea 87 y 95 la funcion "addeventListener" esta escrita de forma incorrecta siendo que la escritura correcta es addEventListener.

En la linea 102 nuevamente estamos asignando constantes como "for (const resetPara of resetParas) {" y no variables con ciertos valores asiganando un bucle no necasario como anteriormente estaba "for (let i = 0; i < resetParas.length; i++){"

En la Linea 103 resetParas[i].textContent = ''; no deberia ir incluida la [i] esto identifica la cantidad de veces o de iteraciones que realizara el programa en bucle hasta finalizar los intentos y/o dar con el numero correcto la cual ya asignamos en la linea 69.

En la linea 109 estaba "randomNumber = Math.floor(Math.random());" y esta faltante por Asignacion el *100 junto al + 1.

En la Linea 117 Agregamos //<body> asignando asi al programa un atributo que muestre el control de forma fisica al programa llamando asi con seguridad la visibilidad de los colores programados anteriormente.
