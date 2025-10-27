# Pygame
## Instalación pygame
```python
pip install pygame
```
## Desinstalación pygame
```python
pip uninstall pygame
```
### Primero para comenzar nuestro juego llamamos a pygame
import pygame
### Sacamos nuestra caja de herramientas para construir el juego
```python
pygame.init()
```
### Submodulos
### screen : pantalla
### el tamaño de la ventana es fijo y el usuario no puede cambiarlo
```python
screen = pygame.display.set_mode((1280,720))    
```
### clock : tiempo 
```python
clock = pygame.time.Clock
```
***Submodulos de pygame***
  pygame.display → maneja la ventana y la pantalla
  Contiene clases como:
    .set_mode((x,y)) -> maneja el ancho x y altura y de la ventana
  pygame.image → carga imágenes
    
  pygame.mixer → maneja sonido
  
  pygame.event → maneja teclado, ratón, joystick

  pygame.time → controla el tiempo y los FPS(Frames por segundo)
  Maneja relojes, temporizadores, ticks
  Contiene clases como:
    .CLock()
    .
  
  pygame.draw → dibuja líneas, círculos, etc.
