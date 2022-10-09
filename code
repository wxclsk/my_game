# Import 
import pygame
from pygame.locals import *
pygame.init()

import sys

# Colors
BLACK = (0, 0, 0)
WHITE = (255, 255, 255)
RED = (255, 0, 0)
GREEN = (0, 255, 0)
BLUE = (0, 0, 255)

# Clock for window update
fpsClock = pygame.time.Clock()
fps = 60

# Create window view
width, height = 640, 480
screen = pygame.display.set_mode((width, height))

# Game loop
while True:
    screen.fill((0, 0, 0))
    
    for event in pygame.event.get():
        if event.type == QUIT:
            pygame.quit()
            sys.exit()
    pygame.display.flip()
    fpsClock.tick(fps)
