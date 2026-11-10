Markdown permite representar fragmentos de código dentro de una línea o en bloques independientes.

Los backticks simples muestran código dentro de una oración, como en `const x = 42;`.

Tres backticks crean un bloque de código. Después de los backticks de apertura se puede especificar el lenguaje para que un renderizador compatible aplique el resaltado de sintaxis correspondiente:

```js
function saludo(nombre) {
  return `Hola, ${nombre}!`;
}

console.log(saludo('mundo'));
```

```python
def saludo(nombre):
    return f"Hola, {nombre}!"

print(saludo("mundo"))
```

Tres virgulillas constituyen una forma alternativa de crear el mismo bloque:

~~~js
function saludo(nombre) {
  return `Hola, ${nombre}!`;
}

console.log(saludo('mundo'));
~~~
