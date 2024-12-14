# 42_Cub3D

## Project Description
`Cub3D` is a 3D game engine project inspired by the classic game Wolfenstein 3D. It uses raycasting to render a 3D perspective view from a 2D map. This project is a great way to learn about computer graphics, game development, and the mathematical concepts behind raycasting.

## Techniques Used
- **Raycasting**: A rendering technique to create a 3D perspective from a 2D map.
- **2D Map Parsing**: Reading and interpreting a 2D map to create the game world.
- **Graphics Rendering**: Drawing walls, floors, and ceilings based on the player's perspective.
- **Player Movement**: Handling user input to move the player around the game world.
- **Collision Detection**: Ensuring the player cannot walk through walls.

## Building the Project
To build the project, follow these steps:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/Cuteness-overload/42_Cub3D.git
    cd 42_Cub3D
    ```

2. **Compile the project**:
    ```sh
    make bonus
	# or just "make" if you don't want the bonuses
    ```

3. **Run the game**:
    ```sh
    ./cub3d path/to/map.cub
    ```

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
