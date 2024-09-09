# CURSO: APRENDE BLAZOR

# LECCIÓN 29: Navegación a un elemento HTML contenido en un componente

1. Abrir la aplicación con Visual Studio 2022 o VSCode

2. Incluimos el Id en el elemento de HTML al que queremos navegar

Por ejemplo si queremos navegar al elemento de HTLM h2 con identificador id="section2",
incluimos el siguiente código:

```razor
<h2 id="section2">Section 2</h2>
```

3. Para navegar y mostrar el elemento HTML incluimos su id precedido por el símbolo #.

```razor
<ul>
    <li><a href="#section2">Go to Section 2</a></li>
</ul>
```
