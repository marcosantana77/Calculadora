# Calculadora
Una calculadora simple construida utilizando HTML, CSS y JavaScript.

Características
Operaciones aritméticas básicas: adición, substracción, multiplicación y división
Botón "Borrar" (C) para restablecer la calculadora
Botón "Igual" (=) para calcular el resultado
Uso
Abre el archivo index.html en un navegador web.
Utiliza los botones de la calculadora para ingresar números y realizar operaciones.
Presiona el botón "Borrar" (C) para restablecer la calculadora.
Presiona el botón "Igual" (=) para calcular el resultado.

Construido con
HTML
CSS
JavaScript

Cómo funciona
La calculadora funciona actualizando el elemento display con la entrada del usuario a medida que hace clic en los botones. El código de JavaScript escucha los eventos de clic en los botones y actualiza el display en consecuencia.

El código de JavaScript también realiza un seguimiento del valor actual, el operador y el segundo valor a medida que el usuario ingresa la entrada. Cuando el usuario presiona el botón "Igual" (=), el código realiza la operación aritmética adecuada en el valor actual y el segundo valor y actualiza el display con el resultado.

Que hace document.querySelector(".display"); ? - Selecciona el primer elemento en html que tenga la clase display

Que hace const buttons = document.querySelectorAll("button"); ? Esto permite seleccionar todos los botones que se encuentran en el documento html y los guarda en una lista

Que hace buttonText = button.textContent; ? Se utiliza para obtener el texto de un boton

Que hace y como funciona buttons.forEach((button) => { ...} ? se usa para iterar sobre todos los elementos de la lista buttons.
Que hace y como funciona button.addEventListener("click", () => { } ) Se agrega un evento al botón, que al momento de hacer click ejecuta una acción
