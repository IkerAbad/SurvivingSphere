# SurvivingSphere

Juego de Unity en 3D (mayo de 2023), con Unity 2020.3.47f1. Mueves una esfera con las flechas arriba y abajo y giras la cámara con las laterales, en una arena donde van apareciendo oleadas de enemigos que te empujan. Si recoges un potenciador durante 7 segundos puedes lanzar a los enemigos fuera de la plataforma. La escena se llama `Prototype 4`, así que parte de un ejercicio de los cursos de Unity Learn.

## Qué hay

- `PlayerController.cs`: movimiento, potenciador con cuenta atrás de 7 segundos y empuje a los enemigos al chocar con él activo.
- `Enemy.cs`: cada enemigo persigue al jugador y se destruye si cae de la plataforma.
- `SpawnManager.cs`: oleadas con un enemigo más en cada una y un potenciador nuevo por oleada.
- `RotateCamera.cs`: gira la cámara alrededor del centro con el eje horizontal.
- `Assets/Scenes/Prototype 4.unity`, prefabs, un material físico rebotante y la `Course Library` de Unity.

No lo he ejecutado desde aquí: Unity no está disponible en mi entorno de revisión, así que no he comprobado que abra y funcione.

## Cómo abrirlo

Abre la carpeta con Unity Hub usando la versión 2020.3.47f1 (u otra 2020.3 compatible) y carga la escena `Assets/Scenes/Prototype 4.unity`.

## Licencia

Mis scripts de `Assets/Scripts` son MIT, ver [LICENSE](LICENSE). Los recursos de `Assets/Course Library` son de Unity Technologies y se rigen por sus propias condiciones.

---

# SurvivingSphere (English)

A 3D Unity game (May 2023), made with Unity 2020.3.47f1. You move a sphere with the up and down arrows and rotate the camera with the side ones, in an arena where waves of enemies keep appearing and push you around. If you pick up a power-up, for 7 seconds you can knock enemies off the platform. The scene is called `Prototype 4`, so it starts from an exercise of the Unity Learn courses.

## What's inside

- `PlayerController.cs`: movement, a power-up with a 7-second countdown and a push on enemies when colliding with it active.
- `Enemy.cs`: each enemy chases the player and is destroyed if it falls off the platform.
- `SpawnManager.cs`: waves with one more enemy each time and a new power-up per wave.
- `RotateCamera.cs`: rotates the camera around the center with the horizontal axis.
- `Assets/Scenes/Prototype 4.unity`, prefabs, a bouncy physics material and Unity's `Course Library`.

I have not run it from here: Unity is not available in my review environment, so I have not checked that it opens and works.

## Opening it

Open the folder with Unity Hub using version 2020.3.47f1 (or another compatible 2020.3) and load the scene `Assets/Scenes/Prototype 4.unity`.

## License

My scripts in `Assets/Scripts` are MIT, see [LICENSE](LICENSE). The assets in `Assets/Course Library` belong to Unity Technologies and are governed by their own terms.
