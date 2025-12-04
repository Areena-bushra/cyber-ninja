🕹️ CyberNinja: Sky Run

A fast-paced endless runner built in Unity, featuring smooth camera motion, procedural tile spawning, and responsive player controls.
🚀 Features

🎮 Smooth Player Controls (A/D to turn left & right)

🧱 Procedural Tile Generation — infinite path system

🎥 Smooth Trail Camera for cinematic movement

⚡ Fast, responsive, and lightweight gameplay

🧩 Easy to extend and customize


How It Works (Core Scripts)


1️⃣ PlayerMovement.cs

Handles player motion and 90-degree turns.

- A → Turn Left
- D → Turn Right
- Auto-forward movement
- CharacterController ensures smooth movement

2️⃣ SpawnTile.cs

Procedurally spawns tiles ahead of the player at fixed intervals.
Includes:

Random directional switching

Distance-based tile placement

Endless path generation

3️⃣ TrailCamera.cs

A smooth follow-camera system using:

trail distance

height offset

camera delay smoothing
📂 Project Structure
/Assets
  /Scripts
    - PlayerMovement.cs
    - SpawnTile.cs
    - TrailCamera.cs
  /Prefabs
    - TilePrefab
  /Scenes
    - MainScene

    📘 Script Highlights
⭐ PlayerMovement.cs

Smooth turning + constant forward run.

⭐ SpawnTile.cs

Auto tile generation for infinite gameplay.

⭐ TrailCamera.cs

Cinematic trailing camera logic.

🤖 Future Enhancements

Add enemies & traps

Add score system

Add animations & character models

Sound effects & background music

Power-ups (speed boost, shield, invisibility)
