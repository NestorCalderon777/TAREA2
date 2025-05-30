# BIENVENID@ A SPOTIFIND EL SISTEMA DE GESTION Y BUSQUEDA DE CANCIONES.


## Descripcion:

- Spotifind es una aplicacion desarrollada en lenguaje C que permite gestionar y buscar canciones de manera eficiente,
Las canciones se cargan desde un archivo CSV y se organizan internamente usando estructuras tipo Map y List.

Cada canción cuenta con los siguientes atributos:

- Ttulo

- Artista

- Album

- Genero

- Tempo

## Cómo compilar y ejecutar:

- Tener instalado Visual Studio Code

- Tener la extensión C/C++

- Tener instalado un compilador como gcc

Pasos:

1. Descarga y descomprime el proyecto en una carpeta.

2. Abre el proyecto en VS Code

3. Ir a Archivo --> Abrir carpeta... y seleccionar la carpeta del proyecto

4. Abre el archivo tarea2.c

5. Compila el programa desde la terminal integrada con:
```
gcc tarea2.c tdas/extra.c tdas/list.c tdas/map.c -o tarea2.exe
```
Ejecuta el programa con:
```
./tarea2.exe
````
## Funcionalidades Implementadas:

- **Cargar canciones desde un archivo CSV.**

- **Buscar canciones por genero.**

- **Buscar canciones por artista.**

- **Buscar canciones por tempo (lentas, moderadas, rapidas).**

- **Salir del programa.**

## Consideraciones importantes:

- El archivo CSV debe tener un formato adecuado con columnas: Titulo, Artista, Album, Genero, Tempo. 
- No se permiten caracteres especiales o comas sin comillas dentro de los campos del CSV.
- El sistema puede experimentar cierta demora si se cargan muchas canciones.

# **Ejemplo de uso**
1. Cargar canciones desde archivo
```
Opcion seleccionada: 1) Cargar canciones
Archivo 'song_dataset_.csv' cargado con exito. Se procesaron 320 canciones.
```
2. Buscar por genero
```
Opción seleccionada: 2) Buscar por genero
Ingrese el genero a buscar: acoustic
Canciones del genero 'acoustic':
| Titulo: Comedy | Album: Comedy | Tempo: 87.92
| Titulo: Ghost - Acoustic | Album: Ghost (Acoustic) | Tempo: 77.49
| Titulo: To Begin Again | Album: To Begin Again | Tempo: 76.33
etc...
```
3. Buscar por artista
```
Opción seleccionada: 3) Buscar por artista
Ingrese el nombre del artista: Travis Scott
Canciones del artista 'Travis Scott':
| Titulo: SICKO MODE | Album: ASTROWORLD | Genero: house | Tempo: 155.01
etc...
```
4. Buscar por tempo
```
Opción seleccionada: 4) Buscar por tempo
Que tipo de tempo estas buscando hoy ??
1) Lentas --> (Menor de 80)
2) Moderadas --> (De 80 a 120)
3) Rapidas --> (Mayor a 120)
Selecciona una opcion (1-3): 3
| Título: R.I.P | Genero: Hip-Hop | Album: Bad Boy Club | Tempo: 140.00 
etc...
```
5. Salida del programa
```
Opción seleccionada: 5) Salida
Gracias por usar Spotifind (^-^)
Vuelve pronto!
```
