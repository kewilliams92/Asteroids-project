#Asteroids Game in Python with Pygame

Overview

This is my version of the classic Asteroids game, built from scratch using Python and Pygame. It’s been a fun and rewarding project that helped me dive deeper into game development, especially in handling movement, collisions, and dynamic object interactions. The game is simple yet engaging, and seeing everything come together has been an awesome experience.

Features

1.	Smooth Gameplay: The game runs at a consistent 60 frames per second, ensuring smooth and responsive controls.
2.	Game Over Mechanic: The game continues until the player collides with an asteroid. When that happens, the game ends and prints “Game Over” in the console.
3.	Organized Code: I utilized Pygame Groups to manage game objects, making updates and drawings cleaner and easier to handle.
4.	Player Movement: The player controls a triangle-shaped ship that can move freely using the WASD keys, offering precise control.
5.	Dynamic Asteroids: The asteroids move randomly, creating unpredictable challenges. Shooting them triggers dynamic splitting:
6•	Large asteroids break into two medium ones.
7•	Medium asteroids break into two small ones.
8•	Small asteroids disappear completely when hit.
9.	Collision Detection: Collision mechanics handle interactions between the player and asteroids (resulting in a game over) or between projectiles and asteroids (causing splitting or destruction).
10.	Constants for Key Values: I used constants to manage settings like speed, size, and frame rates, making it easier to tweak and balance the game.

What I Learned

This project was a great learning experience for me. I gained hands-on knowledge about building smooth and responsive gameplay, managing object interactions like splitting asteroids, and implementing collision detection. Using Pygame Groups was especially helpful—it kept the code organized and allowed me to focus on features instead of getting bogged down by repetitive tasks.

Overall, this project taught me a lot about game development, and I’m excited to continue building on it. If you’d like to see the code or chat more about what I’ve learned, I’d be happy to share!
