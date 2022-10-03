# JavaScript
Repo de mi aprendizaje sobre JavaScript.
## 1・Introduccion
## 2・Variables
## 3・Tipos de datos
## 4・Operadores
## 5・Condicionales
### 5.1・If-else
### 5.2・Switch
Nos permite evaluar una expresión y dependiendo su valor nos permitira ejecutar ciertas instrucciones.
```JavaScript
switch (expresión){
    case x:
        // código si expresión === x
        break;
    case y:
        // código si expresion === y
        break;
    default:
        // código si expresion es diferente
}
```

## 6・Ciclos
### 6.1・While
Evalua una condición, y mientras esa condición sea verdadera, va a ejecutar estas intrucciones que se encuentran dentro del ciclo las veces que sea necesario.

```JavaScript
    let i = 0;
    
    while (i <= 3) {
        //Instrucción
        i++;
    }
```
### 6.2・Do-While
Es una variación del ciclo While, aquí también se evalúa una condición pero se lo hace después de haber ejecutado las instrucciones y mientras se cumpla está condición se va a ejecutar las intrucciones las veces que sea necesario. Es decir, primero se ejecuta las instrucciones y luego se evalúa la condición pero se ejecuta aunque sea una vez.

```JavaScript
    let i = 0;

    do {
        //instrucción
        i++;
    }while (i <= 1);
```

### 6.3・For
## 7・Arrays
## 8・Funciones
## 13. Clases
Una clase es como un plantilla para crear objetos, es decir los objetos que se crean a partir de la clase van a tener las mismas características.
Las características se les conoce como:
- Atributos
- Métodos
Ejm: Lo podemos asociar la clase con un molde para hacer galletas. El molde representa la clase por la cual se puede construir o fabricar objetos que en este ejemplo vendrían a hacer las galletas. Y de forma todas las galletas son iguales pero pueden tener decoraciones diferentes, estas decoraciones serían las propiedades o atributos de cada objeto.

Vimos como crear un Constructor de objeto.
```
Clase = Contructor (Atributos) + Métodos (Funciones)
```

### Sintaxis
Hacemos un proceso de abstracción:
Si queremos construir el videojuego de Mario Bros.
1. Tenemos que definir los Objetos: Playr1 y Player2
2. Definir los Atributos:
   1. Nombre: Mario y Luigui
   2. Color sombrero: Rojo y Verde
5. Definir métodos:
   1. Saltar(), Correr(), Saludar()