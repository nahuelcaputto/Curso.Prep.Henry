1. En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

	* Objetos: Son cajas donde se puede almacenar contenido, al igual que los arrays, pero con la particularidad que cada contenido ira referenciado con una palabra clave, en pares de clave:contenido. Asi en el objeto bicicleta tendremos la propiedad cantidadRuedas: 2 y color:rojo de la siguiente manera
	bicicleta={
	cantidadRuedas:2,
	color:rojo}
	* Propiedades: son las caracteristicas dentro de los objetos a las que se les asignan valores. En el ejemplo: cantiddadRuedas y color son propiedades del objeto bicicleta.
	* Métodos: Son las funciones declaradas dentro de un objeto.
	* Bucle `for…in`: es la manera de recorrer los objetos. Ya que los mismos carecen de indices numericos como los arrays. Luego del for se declara una variable que es la que ira iterando dentro del for hasta que el objeto este vacio: for(let variable in objeto){'codigo'}.
	* Notación de puntos vs notación de corchetes: son las dos maneras de hacer referencia a las propiedades dentro de un objeto
	Notacion de puntos: objeto.propiedad
	Notacion de corchetes: objeto['propiedad']