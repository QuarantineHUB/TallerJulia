Repositorio para dar la ponencia de introducción a Julia. El notebook a utilizar es encuentra en la carpeta `/notebooks`.

Necesitan intalar  `Julia` +v1.0 y tener instalado `Jupyter Notebook`

Para agregar Julia a Jupyter. Basta ejecutar en terminal 

`$ julia`

Y cuando entren a al REPL de Julia. Tecleen

```Julia
> using Pkg
> Pkd.add("IJulia")
```
Cuando habran de nuevo Jupyter y ejecuten el notebook de este taller cargará el nucleo de Julia.
