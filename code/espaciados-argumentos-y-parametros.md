# Espaciados, argumentos y parametros

Esta estandarización se debe seguir en todo momento para que los desarrolladores puedan tener un código homogéneo en todo el desarrollo.

1.- Debe existir un espacio antes y después de un igual, de un igual-igual-igual, de un menor que y de un mayor que. p.e.:

```javascript
// antes y después de un igual
var i = 0;

// antes y después de un igual-igual-igual
if ( i === 12 ) { ... }

// antes y después de un menor que
if ( i <= 12 ) { ... }

// antes y después de un mayor que
if ( i >= 12 ) { ... }
```

2.- Siempre se deben escribir triples iguales (cuando aplique). p.e.:

```javascript
// igual a ...
if ( i === 1 ) { ... }

// diferente de
if ( i !== 1 ) { ... }
```
3.- Siempre debe existir un espacio antes y uno después de cada parametro en un método o condicional. p.e.:

```javascript
// declarando un método/función
function myFunction ( _param1, _param2, ..., _paramN ) { ... }

// declaración de una función arrow
const myFunction => ( _param1, _param2, ..., _paramN ) = { ... }

// ejecutando un método/función
myFunction( param1, param2, ..., paramN );

// en un condicional
if ( conditionalExpression ) { ... }

while( conditionalExpression ) { ... }

for ( initialization ; conditionalExpression ; afterExecution ) { ... }

do { ... } while( conditionalExpression );
```

4.- Siempre debe existir un espacio entre la declaración del condicional o del método/función y la llave de su contenido de instrucciones.p.e.:
```javascript
// declaración de un método/función
function myFunction () { ... }

// declaración de un condicional y ciclos
while ( conditionalExpression ) { ... }
```

5.- Si un método/función no necesita parametros, los paréntesis deben permanecer sin espacios, sin embardo debe existir un espacio entre el nombre del método/función y el primer paréntesis aunque el método/función necesite parametros o no. p.e.:

```javascript
// declaración de método/función
function myFunction () { ... }
```
