# tarea1-an
 Tarea 1 de Análisis Numérico.
 Integrantes: 
 - Diego Carvajal González
 - Luisa Fernanda Quintero González
 - Shara Gallego Grisales⠀⠀
 
 ¿Cómo ingresar los datos para el código polinomio_caracteristico?
 
 El código pedirá que ingrese primero el número de filas y luego el número de columnas. En esta parte, ingrese el mismo número de filas que de columnas de lo contrario el código no correrá.
 Luego, le pedirá que ingrese por cada fila las entradas, cada entrada debe estar separada con un espacio.
 El código está hecho por casillas, debe correr todo el entorno de ejecución o "Run all", de lo contraario puede no funcionar.
 Este código solo funciona en matrices para la cuales sus valores propios sean todos reales y de multiplicidad menor a 2, de lo contrario puede no funcionar. ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀



Ingreso de  datos en el metodo de potencia. 
Para correr el metodo de potencia, puedes simplemente en donde hay casos de prueba, en especial, caso del libro, modificar la matriz por otra matriz cuadrada de su preferencia, modificar la tolerancia y escoger un vector aleatorio de longitud nx1 que sea diferente del nulo, de lo contrario el codigo podria fallar. Tambien se debe jugar con la tolerancia, en algunos casos cuando tomo la tolerancia muy pequena el codigo puede fallar. 

Ingreso de datos método descomposición QR
Se necesita tener instalado numpy. Todas las entradas de los cuadernos vienen precalculadas.
Se trabaja con la función QR_algor, que debe recibir un array de numpy bidimensional cuadrdo, correspondiente a una matriz simple con autovalores reales y de módulo distinto para asegurar convergencia. Se presentan ejemplos en la descrición del código y en la sección de experimentos, para agregar mas tests, basta con almacenar en una variable un array con las condiciones de arriba y correr QR_algor sobre ella, cambiando de ser necesario los parámetros como tolerancia o cantidad máxima de iteraciones. 
