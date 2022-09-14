 //Falto el metodo de math.floor, para poder evaluaar los numeros, y la limitacion de las cantidades a evaluar
  let randomNumber = Math.floor(Math.random() + 100) + 1;

   //const ATTEMPS
   la variable o constante, puede que sea util, pero de igual manera se cambia, la limitacion de 10num o mas entonces no hay tanta variacion

     ///// eventos de click
  guessSubmit.addEventListener('click', checkGuess);
  debe iniciarce antes y no al final, para que este pueda ejecutar de manera correcta los eventos
  y se verifico que estuviera bien escrita la linea de codigo ya que daba error a la hora de ejecutarse

    //Flata que evaluar/////
    let userGuess = Number(guessField.value);
    aca no tenenia esta linea de codigo del cual no se podia evaluar algo, o no habia que evaluar

     //nuevamente no tiene limitacion de medicio de 1 a 100
	  randomNumber = Math.floor(Math.random() + 100) + 1;
      No habia nuevamente una especificacion de limitacion de numeros


      //espacio de mas en el texto black
    if(userGuess === randomNumber) {
      lastResult.textContent == '!!!Pérdistes!!!';
      lastResult.style.backgroundColor == 'black';
      lowOrHi.textContent == '';
      setGameOver();
    } else if(guessCount === ATTEMPS) {
      lastResult.textContent == 'Felicitaciones! adivinaste el número!';
      lowOrHi.textContent == '';
      lastResult.style.backgroundColor == 'red';
      setGameOver();
    } else {
      lastResult.textContent == 'Incorrecto! ';
      lastResult.style.backgroundColor == 'green';
      if(userGuess < randomNumber) {
        lowOrHi.textContent == 'El número es mayor!';
      } else if(userGuess > randomNumber) {
        lowOrHi.textContent == 'El número es menor!';
      }


      Se le agra doblemente "=" para poder mostrar texto
      ///

      <div class="form">
 //// <label for="guessField">Ingresa el número a adivinar: </label><input type="text" id="guessField" class="guessField">
   //FAlta la funcion onclick
  /// <input type="submit" onclick="checkGuess()" value="Ingresar el número aleatorio" class="guessSubmit">

  ////  const lowOrHi = document.querySelector('.lowOrHi'); //Contantes si es mas alto o mas bajo y falto un "." para seleccionar la clase

      
      
     