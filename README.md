# Metodos

## Índice de la presentación (Splines cuadráticos)

1. Introducción.
2. Descripción del espacio de splines cuadráticos: base, dimensión
3. Interpolación con splines cuadráticos
   1. A trozos
   2. Global
4. Ejemplos
5. Implementación en ordenador
   1. A trozos
   2. Global


## Índice del trabajo

- Splines cuadráticos
	- Introducción
	- Descripción del espacio de splines cuadráticos
	- Interpolación con splines cuadráticos
   	- A trozos
   	- Global
	- Ejemplos
- Splines cúbicos
	- [Construcción de splines clásicos a partir de la segunda derivada](https://en.wikiversity.org/wiki/Cubic_Spline_Interpolation)
   	- Spline sujeto
   	- Spline natural
   	- Spline periódico
	- Propiedades de minimización
	- Ejemplos
- Implementación en ordenador
	- Splines cuadráticos
      - A trozos
      - Global
	- Splines sujeto
	- Spline natural
	- Spline periódico


## Compilar el documento

Hay que utilizar `pandoc`:

- `sudo apt-get install pandoc`
- Seguir [estas](http://pandoc.org/installing.html#linux) instrucciones
- `pandoc Trabajo.md -o Trabajo.pdf`

## Cómo usar Markdown

### Títulos
```md
# Título
## Segundo título
### ...
<!---Comentarios-->
```

### Fórmulas

Tutorial de latex, muy útil para ver como funcionan entornos tales como tablas,
matrices, o derivados del entorno equation:
[The Not So Short Introduction to LaTeX - Tobi Oetiker](https://tobi.oetiker.ch/lshort/lshort.pdf)

Los símbolos se pueden mirar en [DeteXify](http://detexify.kirelabs.org/classify.html).
- Fórmulas dentro del texto: `$ < Código en LaTeX > $`
- Fórmulas con linea propia: `\[ < Código en LaTeX > \]`
- Fórmulas con número para referenciarlas:
     ```md
        \begin{equation}
          < Cosas >
        \end{equation}
      ```
### Formato

 - **Negrita**: `**Negrita**`
 - *Cursiva*: `*Cursiva*`
