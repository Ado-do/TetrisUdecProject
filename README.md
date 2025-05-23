<div id="top"></div>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  </a>
    <img src="/assets/frontpage.png" alt="Logo" width="869" height="489">
  </a>

  <h3 align="center">PROYECTO PROGRAMACIÓN I (S1 2022)</h3>

  <p align="center">
    Tetris en C (SDL2)
    <br />
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Tabla de contenidos</summary>
  <ol>
    <li>
      <a href="#sobre-el-proyecto">Sobre el proyecto</a>
    </li>
	<li><a href="#objetivos">Objetivos</a></li>
    <li>
      <a href="#instrucciones">Instrucciones</a>
      <ul>
        <li><a href="#prerequisitos">Prerequisitos</a></li>
        <li><a href="#instalación">Instalación</a></li>
		<li><a href="#controles">Controles</a></li>
      </ul>
    </li>
    <li><a href="#links-utiles">Links utiles</a></li>
  </ol>
</details>

<p align="right">(<a href="#top">volver a inicio</a>)</p>

<!-- ABOUT THE PROJECT -->
## Sobre el proyecto
### Equipo
* Alonso Bustos (Adodo)
* Franchesca Mora (Franchesita)
* Cristobal Figueroa (Krozz)

### Imagenes
Gameplay (Nivel 1)             |  Gameover
:-------------------------:|:-------------------------:
![](/img/gameplay1.png)  |  ![](/img/gameover.gif)

<p align="right">(<a href="#top">volver a inicio</a>)</p>

<!-- ROADMAP -->
## Objetivos

- [x] ~~***Crear ventana y mover el cubo***~~

- [ ] **Implementar sistema de menús**
    - [ ] Pantalla de Start
    - [ ] Configuración <sub>(Opcional)</sub>
    - [ ] Mayores puntuaciones  <sub>(Opcional)</sub>

- [X] ~~***Crear campo de juego (grilla 16x10) y mover piezas en esta***~~
    - [X] ~~**Definir limites de movimiento en la grilla**~~
    - [X] ~~**Game Over! (Si una pieza sobrepasa el campo de juego)**~~

- [X] ~~***Implementar los 7 tetrominos***~~
    - [X] ~~**Rotaciones**~~
     - [ ] ["Super rotation system"](https://tetris.wiki/Super_Rotation_System)
     - [ ] ["Wall kicks"](https://tetris.wiki/Super_Rotation_System#Wall_Kicks)
    - [X] ~~**Mostrar la siguiente pieza en la secuencia**~~
    - [X] ~~**Elimininar lineas completadas**~~
    - [ ] **Usar ["Random generator"](https://www.educative.io/courses/game-development-js-tetris/xlKZA7B9lLr) para crear la secuencia de piezas**
    - [X] ~~Preview de donde caera la pieza~~

- [X] ~~***Definir los [controles finales](https://strategywiki.org/wiki/Tetris/Controls)***~~
    - [ ] DAS (Delayed Auto-Shift) y tipos de drops (Soft drop y Hard drop)

- [X] ~~***Duracion de juego "infinita"***~~

- [ ] ***Sistema de Puntuación (["Scoring"](https://tetris.wiki/Scoring))***
    - [X] ~~**Contador de puntuación en pantalla**~~
    - [X] ~~**Contador de lineas completadas**~~
    - [X] ~~Implementar velocidades y dificultad~~
    - [X] ~~Cambiar escenarios segun puntuacion <sub>(Opcional)</sub>~~
    - [ ] Guardar records

- [ ] Retoques finales
    - [ ] Solucionar bugs
    - [ ] Musiquita! _(Loo-fi estilo tetris - Doom estilo tetris)_ <sub>(Opcional)</sub>
    - [ ] ***Ser el mejor tetris en C del mundo >:)***

<p align="right">(<a href="#top">volver a inicio</a>)</p>

<!-- GETTING STARTED -->
## Instrucciones

Aqui dar instrucciones de como montar el repositorio localmente y como compilar el juego, ademas de como jugarlo

### Prerequisitos

~~Ser vio pa la wea~~
Dependencias para poder compilar

* SDL2
 
* SDL2_image
 
* SDL2_ttf

* SDL2_mixer

### Instalación

1. Descargar el repositorio
2. Ir a la carpeta del repositorio desde el terminal
   ```
   cd ../Proyecto-Tetris/
   ```
3. Usar make
   ```sh
   make
   ```
4. Una vez compilado abrir con
   ```
   ./tetris.exe
   ```
 5. Have fun :)

### Controles

En menús:
* <kbd>↑</kbd>, <kbd>↓</kbd>, <kbd>←</kbd> y <kbd>→</kbd>: Moverse por el menú
* <kbd>ENTER</kbd> y <kbd>ESPACIO</kbd>: Confirmar
* <kbd>ESC</kbd>: Salir del juego

En partida:
* <kbd>←</kbd> y <kbd>→</kbd>: Mover el tetrominó
* <kbd>ESPACIO</kbd> o <kbd>↓</kbd>: Drop  instantáneo/rapido del tetrominó
* <kbd>X</kbd> o <kbd>Z</kbd>: Rotar 90° (sentido horario o antihorario) el tetrominó
* <kbd>A</kbd>: Rotar 180° el tetrominó
* <kbd>C</kbd>: Guardar pieza
* <kbd>ESC</kbd>: Pausar
* <kbd>R</kbd>: Reinciar

<p align="right">(<a href="#top">volver a inicio</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Links utiles

Aqui pondremos links utiles para el proyecto, ya sea documentacion de SDL2 o ideas para programar Tetris

* [Documentación SDL2 (Wiki)](https://wiki.libsdl.org/)
* [Wiki SDL2 por categorias](https://wiki.libsdl.org/APIByCategory)
* [Santa biblia para aprender SDL y game dev (lazyfoo)](https://lazyfoo.net/tutorials/SDL/) 
* [Seminario de un tipo de Harvard que explica de pana el SDL (esta en español)](https://youtu.be/yFLa3ln16w0)
* [Tutorial para hacer un menú bomnito con SDL](https://www.parallelrealities.co.uk/tutorials/widgets/widgets1.php)
* [Insertar texto con SDL_ttf (puede ser util para el menu y score)](https://www.parallelrealities.co.uk/tutorials/ttf/ttf1.php)
* [Gameplay general Tetris](https://tetris.wiki/Gameplay_of_Tetris), [Categorias del Gameplay](https://tetris.wiki/Category:Gameplay)
* [Generacion de piezas](https://tetris.wiki/Category:Gameplay), [Implementación](https://www.educative.io/courses/game-development-js-tetris/xlKZA7B9lLr)
* [Sistema de puntuación en Tetris (Scoring)](https://tetris.wiki/Scoring)
* [Controles generales](https://strategywiki.org/wiki/Tetris/Controls)
* [Sistema de rotaciones "Super rotation system"](https://tetris.wiki/Super_Rotation_System)

Sobre github
* [Readme formatos y syntaxis](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
* [Video funcionamiento de github](https://youtu.be/8Dd7KRpKeaE)
