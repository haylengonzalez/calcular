# CALCULADORA BÁSICA CON MENÚ

Una calculadora básica se puede realizar con condiciones. Se desea realizar alguna de las operaciones básicas con dos números`x, y`. Además se desea calcular la potencia y el logaritmo. Se deben de considerar los casos dende `y - 0` donde la división `x/y` No se puede realizar y cuando `x <=0` donde NO se puede calcular el `log(x)`. Se desea generar en menú para que el usuario pueda seleccionar la operación a realizar. Una manera de hacerlo es la siguiente:

1. Se reciben los dos números `x, y` para realizar la operación.
2. se recibe la operación a realizar mediante la vriable `opcion` la que selecciona e menú que operación ejecut el algoritmo.
3. Se inicializa la variable lógica `bandera = falso`. Si la división a el logaritmo no se puede calcular,  se hace `bandera = True`.
4. Mediante condiciones se realiza al operación deseada.
    * En el caso de la división, si `y = 0`, NO se puede realizar la división, se muestra un mensaje y se hace `bandera = True`,
    * En el caso del logaritmo, si `x <= 0`, NO se puede calcular el logaritmo, se muestra un mensaje y se hace `bandera = True`,
5. Se muestra el resultado en el caso en que `bandera = False`.

*Tomado de: Python con aplicaciones a las matemáticas, ingenieria y fianzas. Cervantes O Baez D.*