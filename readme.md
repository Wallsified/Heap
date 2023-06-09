## Práctica 5: Heap, MaxHeap y MinHeap.

<br>

| Alumno                      | No. de Cuenta |
| --------------------------- | ------------- |
| Paredes Zamudio Luis Daniel | 318159926     |

## Comandos de Ejecución

En la carpeta de la práctica abre la terminal y ejecuta los siguientes comandos:

```
javac -cp ".:lib/PilasYColas.jar" -d bin src/*.java

java -cp ".:lib/PilasYColas.jar:bin/" PruebaHeaps
```

Para poder ver la documentación, se ejecuta:

```
javadoc -cp ".:lib/PilasYColas.jar" -d docs src/*.java

cd /docs
```

y revisar el archivo _allclasses-index_.

## Resultado previsto en terminal.

```
[0, 1, 2, 3, 4, 12, 7, 5, 6, 11, 9, 14, 13, 10, 16, 15, 8]

[16, 15, 14, 11, 9, 12, 13, 6, 3, 4, 5, 8, 10, 2, 7, 1, 0]

[0, 1, 2, 3, 4, 12, 7, 5, 6, 11, 9, 14, 13, 10, 16, 15, 8]

[16, 15, 14, 11, 9, 12, 13, 6, 3, 4, 5, 8, 10, 2, 7, 1, 0]

[0, 1, 2, 3, 4, 12, 7, 5, 6, 11, 9, 14, 13, 10, 16, 15, 8]

[16, 15, 14, 11, 9, 12, 13, 6, 3, 4, 5, 8, 10, 2, 7, 1, 0]

```

## Notas

Hice modificaciones a todos los archivos de la práctica, unos son menores y no afectan a la estructura o al funcionamiento del código:

- En general hice modificaciones a la documentación previa, pues al momento de generarla me marcaba errores, pero se respetaron las ideas que estaban previamente. ie:

```
@author Adriana Sanchez Del Moral <adrisanchez@ciencias.unam.mx>
>> @author <a href="mailto:adrisanchez@ciencias.unam.mx"> Adriana Sanchez Del Moral </a>
```

- En _Coleccionable.java_ el método Iterador cambia a _Iterator\<T>_ para evitar chequeos multiples de posible falla de conversión al usarlo. ie:

```
public java.util.Iterator iterator();
>> public java.util.Iterator<T> iterator();
```

En consecuencia, esto ahorra muchos casteos a _T_ posteriormente.

El _.jar_ usado es propio, no use el _.jar_ que nos dieron por que antes de que fuera proporcionado use el propio que hice con mis clases de prácticas anteriores y no tuve fallos con ellas.

<br>

## Updates

- 08/Junio/23 Done! (eso parece. )

<br>

> _Greetings, programs! Together we have achieved a great many things...._
