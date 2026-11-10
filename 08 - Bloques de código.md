Código inline: `const x = 42;`

Bloque de código:

```js
function saludo(nombre) {
  return `Hola, ${nombre}!`;
}

console.log(saludo('mundo'));
```

~~~js
function saludo(nombre) {
  return `Hola, ${nombre}!`;
}

console.log(saludo('mundo'));
~~~

```py
genre_columns = [col for col in df_valid_movies.columns if col.startswith("genre_")]

popularity_by_genre = {}

for genre_col in genre_columns:
    genre_name = genre_col.replace("genre_", "")

    popularity_by_genre[genre_name] = df_valid_movies.loc[
        df_valid_movies[genre_col] == 1,
        "popularity"
    ].mean()

popularity_by_genre = (
    pd.Series(popularity_by_genre)
    .sort_values(ascending=True)
)
```