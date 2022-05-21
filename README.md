# Cub3D
## Wolfenstein3d inspired Raycasting project

The aim of this project was to extract information from a .cub file and use that information to draw a 3d maze on the screen using raycasting principles.

### Example of a valid cub file's information:
```
R 1920 1080

NO ./textures/greystone.xpm
SO ./textures/purplestone.xpm
WE ./textures/redbrick.xpm
EA ./textures/wood.xpm

S ./textures/creeper.xpm
F 77,92,53
C 163,208,230

		1111111111111111111111111
		1000000000110000000000001
		1011000001110000002000001
		1001000000000000000002001
111111111011000001110000000000001
100000000011000001110111110111111
11110111111111011100000010001
11110111111111011101010010001
11000000110101011100000010001
10002000000000001100000010001
10000000000000001101010010001
11000001110101011111011110N0111
11110111 1110101 101111010001
11111111 1111111 111111111111
```

### And the result onscreen:

<img width="797" alt="Screen Shot 2022-05-21 at 3 02 09 PM" src="https://user-images.githubusercontent.com/105823790/169653063-fd878958-df57-4bb5-9fb4-148fbe29bd04.png">


