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
```python
import pygame
```
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
### Clock es clase tiempo del submodulo time
```python
clock = pygame.time.Clock
```
### guardamos en una variable boobleana True
### True: el juego esta en ejecucion
### False: el juego se detiene
```python
running = True
```
### Mientras running es verdadero ejecutar este bloque
```python
    while running:
```
### event es un modulo de pygame que contiene eventos
### como cerrrar la ventana, presionar una tecla, mover el mouse, cerra el click, etc
```python
        for event in pygame.event.get():
```
### Da la lista de todos los eventos del modulo event de pygame
```python
        for event in pygame.event.get():
```
    
        if event.type == pygame.QUIT:
            running = False

    # fill the screen with a color to wipe away anything from last frame
    screen.fill("purple")

    # RENDER YOUR GAME HERE

    # flip() the display to put your work on screen
    pygame.display.flip()

    clock.tick(60)  # limits FPS to 60

pygame.quit()
