## Tu ficha personal (w2ch4)

Te unes a un proyecto donde se ha maquetado una página con un formulario para rellenar una ficha personal.

La página carga un script que se encarga de reaccionar a los cambios que hace el usuario en el formulario. En el archivo `index.js` tienes un `switch` que tendrás que rellenar invocando a diferentes funciones.

Las funciones que tienes que definir aparte son las siguientes:

- `setName()`: recibe un nombre y hace que el elemento HTML con clase `name` muestre ese nombre. También debe mostrarse en el texto alternativo de la imagen.
- `setAge()`: recibe una fecha en formato dd/mm/aaaa y hace que el elemento HTML con clase `age-number` muestre la edad que tiene la persona.
- `setPicture()`: recibe una URL de una imagen y la muestra en la `<img>`.
- `setJavaScript()`: recibe un booleano dependiendo de si la persona ha programado previamente con JS o no. Si es `true`, muestra el elemento HTML con clase `javascript-yes`, si es `false`, muestra el elemento HTML con clase `javascript-no`.
- `setSuffering()`: recibe un grado de sufrimiento. En el elemento HTML con clase `.suffering-quantity` debe poner "poco" si el sufrimiento es inferior a 5, "normal" si el sufrimiento es mayor o igual a 5 y menor que 8, y "mucho" si el sufrimiento es mayor o igual a 8.
  Además, dicho elemento HTML debe tener una clase adicional que sea `suffering-danger` cuando el sufrimiento sea inferior a 5, `suffering-warning` cuando el sufrimiento sea mayor o igual a 5 y menor que 8, y `suffering-ok` cuando sea mayor o igual a 8.

Además, todas esas funciones deberían quitar la clase `off` al elemento que van a modificar, y deberían hacerlo en primer lugar. Ejemplo:

`setName()`: primero le quita la clase `off` al elemento con clase `name`, y luego le pone el nombre.

Rellena el `switch` con llamadas a esas funciones para que la página funcione.
