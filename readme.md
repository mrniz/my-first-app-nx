
# My first NX App! (ESP)
Es una aplicación homebrew MUY simple usando libnx y sus componentes para poder realizarse en una Switch con posibilidad de ejecutar aplicaciones Homebrew
- cur lts ver: 1.1
## Changelog
### 1.0
- Primera versión!!!
### 1.1
- Ahora Megalovania es (en teoría) "activable":
```c
        if (kDown & HidNpadButton_X) 
        {
            megalovania = !megalovania;
        }
```
- Se le sumó BPM a Megalovania.
- Se arreglo el "<" fantasma que aparecía sin motivo
- Se quitó el modo "debug"
- Se pretende arreglar el ícono (eso espero pensar)
## Instalación
La instalación estan sencilla que un boracho con los ojos cerrados y con un pié atado lo puede hacer.

1. Descarga el archivo .nro
2. Copialo en tu carpeta llamada `switch/` de la tarjeta SD

## Funcionamiento
El funcionamiento es sencillo, solo muestra textos de un arreglo (Array) que está en la misma aplicación, un listado con frases/oraciones sin sentido, simplemente para leerlas y ya xd.
### Controles
- ***A***  - Pasar al siguiente text
- ***+***  - Regresar al HB Menu
- ***X***  - xd
- ***B***  - Sumar tonalidad el botón A

# NOTA
- Este proyecto no es con fin lucrativo por lo que no se cobrará por nada del acceso (obvio porque creo es muy malo cobrar por algo Homebrew)

