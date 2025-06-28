# Ricochet

<p align="center">
  <img src="https://img.shields.io/badge/Unity-2D-blue?logo=unity" alt="Unity 2D" />
  <img src="https://img.shields.io/badge/Status-Final%20Build-brightgreen" alt="Final Build" />
  <img src="https://img.shields.io/badge/Platform-Windows-lightgrey?logo=windows" alt="Windows" />
</p>

> 🚀 **Welcome to Ricochet: Rick and Morty Edition!**
>
> 🌀 Embark on a wild, interdimensional adventure with Rick and Morty in this action-packed 2D ricochet game! Smash through bricks, conquer unique levels, and experience the chaos of the multiverse—all in one final build.
>
> 🎮 **Theme:** Inspired by the world of Rick and Morty, each level features custom sprites, sounds, and references from the show. Can you help Morty survive Rick's latest experiment?
>
> 👨‍💻 **Created by Ken Patrick Garcia as a project for our Game Development course.**
>
> ⚠️ **Note:** This repository contains the final build of the Ricochet game application. The full source code and Unity project setup are too large to upload to GitHub. This repo provides the final executable and essential assets for playing the game.

Ricochet is a Unity-based 2D game where you control the paddle and ball to break through brick walls, with each level themed around Rick and Morty's universe. Enjoy custom sound effects, original sprites, and a variety of challenges as you progress through multiple levels inspired by the show's iconic moments.

## Project Structure

```
Assets/
  Physics/
    - Bouncy.physicsMaterial2D
  Prefab/
    - Brick.prefab
  Scenes/
    - Game Over.unity
    - Global.unity
    - IntroScene.unity
    - Level 1.unity
    - Level 2.unity
    - Level 3.unity
  Scripts/
    - Ball.cs
    - Brick.cs
    - BtnGameOver.cs
    - Color.cs
    - GameManager.cs
    - Intro.cs
    - MissZone.cs
    - Paddle.cs
  Sound/
    - audio (1).prefab
    - bg final.MP3
    - end game.MP3
    - intro.mp3
    morty sound/
      - HEY - AUDIO FROM JAYUZUMI.COM.mp3
      - NO 1 - AUDIO FROM JAYUZUMI.COM.mp3
      - OH GEEZ - AUDIO FROM JAYUZUMI.COM.mp3
  Sprites/
    - aef.jpeg
    - bg end morty.png
    - bg.jpeg
    - bg1 1.jpg
    - bg1.jpg
    - bgintro.jpg
    - bottomtop wall.png
    - brick intto.png
    - Brick-Blue.png
    - Brick-Gray.png
    - c1.png, c2.png, c3.png, c4.png
    - CanvasTimeline.playable
    - gameover.jpg
    - intro bg1.jpg
    - intro.gif
    - last play.png
    - level 2.jpg
    - morty ball.png
    - Paddle1.png
    - pickles.png
    - rick end.jpg
    - Rick State 5.png
    - room bg1.jpg
    - start now.png
    - wall left.png
    - wall right.png
    bricks brick/
      - Rick State 1.png
      - Rick State 2.png
      - Rick State 3.png
      - Rick State 4.png
      - Rick State 5.png
      - Rick State 6.png
```

## Key Components

- **Scenes**: Multiple Unity scenes for different game states (Intro, Levels, Game Over, etc.).
- **Scripts**: Core C# scripts for game logic, including ball and paddle behavior, game management, and UI controls.
- **Prefabs**: Reusable game objects, such as bricks.
- **Physics**: Custom physics materials for 2D interactions.
- **Sound**: Background music, sound effects, and character voice clips.
- **Sprites**: Visual assets for backgrounds, UI, characters, and game elements.

## Getting Started

1. Open `Ricochet.sln` or the project folder in Unity Hub.
2. Make sure all assets are imported and scripts are compiled.
3. Open any scene from the `Assets/Scenes` folder to start playing or editing.

## Credits

- Audio clips in `morty sound` are from [jayuzumi.com](https://jayuzumi.com).
- All other assets are either original or sourced for educational use.

## Screenshots

![image](https://github.com/user-attachments/assets/f198a437-1030-4567-a4dc-ba848c8f5f2d)
![image](https://github.com/user-attachments/assets/3764b07e-f3f8-4c93-855e-1cc9a0a3721f)
![image](https://github.com/user-attachments/assets/fe6a7ebc-cf7a-4a6f-96cf-5c2ac69012c4)
![image](https://github.com/user-attachments/assets/047b28c5-e2cb-4d22-aadf-00910866b13d)


---

<p align="center">
  <img src="https://img.shields.io/badge/Made%20with-Love-red" alt="Made with Love" />
  <img src="https://img.shields.io/badge/Game%20Jam-Project-orange" alt="Game Jam" />
  <img src="https://img.shields.io/badge/Play%20Now-Download-blue" alt="Download" />
</p>
