# Ejercicio1Javadoc
## Descripción
Este programa en Java analiza un array de números enteros para encontrar el valor más alto y contar cuántas veces se repite dentro del array.

    int[] d = {4, 7, 2, 9, 2, 5}; 
    int e = 0;
    int f = d[0];

El funcionamiento es el siguiente:
-Se recorre el array para localizar el número mayor.

     for (int i = 1; i < d.length; i++) { 
			if (d[i] > f) { 
				f = d[i]; 
			} 
		} 

-Se vuelve a recorrer el array para contar cuántas veces aparece ese número.

    for (int i = 1; i < d.length; i++) { 
			if (d[i] > f) { 
				f = d[i]; 
			} 
		} 

-Finalmente, se muestra por pantalla el número mayor seguido del número de repeticiones en el formato mayor:repeticiones.

		for (int i = 0; i < d.length; i++) { 
			if (d[i] == f) { 
				e++; 
			} 

## Como ejecutar el programa
-Eliges los valores que va a contener la array.

-Una vez creado el codigo completo, se ejecuta desde el "run", y el propio codigo acabará mostrando por pantalla el número mayor, y su número de repeticiones.

## Autor
Joel García
