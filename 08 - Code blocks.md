Markdown can display code inside a sentence or in separate blocks.

Single backticks show code inside a sentence, as in `const x = 42;`.

Three backticks create a code block. You can specify the language after the opening backticks so that a compatible renderer can apply the correct syntax highlighting:

```js
function greeting(name) {
  return `Hello, ${name}!`;
}

console.log(greeting('world'));
```

```python
def greeting(name):
    return f"Hello, {name}!"

print(greeting("world"))
```

Three tildes are another way to create the same type of block:

~~~js
function greeting(name) {
  return `Hello, ${name}!`;
}

console.log(greeting('world'));
~~~
