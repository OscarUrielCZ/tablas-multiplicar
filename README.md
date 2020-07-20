# Multiplicar console app

Una aplicación que despliega tablas de multiplicar de acuerdo a los parametros recibidos.

- base: establece la base de la tabla, también se puede usar b
- limite: establece el limite de la tabla, también se puede usar l

![Imagen de la aplicación](https://raw.githubusercontent.com/OscarUrielCZ/tablas-multiplicar/master/assets/imagen1.png)

## Uso de la aplicación

Instalar las dependencias necesarias con:
```
npm install
```

Crear un nuevo archivo con la tabla de multiplicar del 2 desde el 1 hasta el 9
```
node app crear --base=2 --limite=9
```

Mostrar por consola la tabla de multiplicar del 2 desde el 1 hasta el 9
```
node app listar --base=2 --limite=9
```