# Duong Dat 🇻🇳
**Game developer** · Unity / C# · Multiplayer systems

I build games in Vietnam. Sometimes that means syncing a fight between players. Sometimes it means figuring out which blocks a torch should light up underground.

## ▶ Now showing · Vecto Arena

[![Vecto Arena gameplay — open the video demo](https://raw.githubusercontent.com/duongdatdev/VectoArena/main/docs/images/gameplay-arena.png)](https://youtu.be/4xNxysfBVFM)

A 3D multiplayer arena built in Unity. Colyseus rooms handle live matches over WebSockets, while a separate REST API handles accounts, skins and inventory.

[Watch gameplay ↗](https://youtu.be/4xNxysfBVFM) · [Unity client](https://github.com/duongdatdev/VectoArena) · [Game server](https://github.com/duongdatdev/vectoarena_server)

## Select a cartridge

| Game | What happens when you press start |
| --- | --- |
| [Mini Island 2.0](https://github.com/duongdatdev/miniisland-2.0) | Meet friends on a shared island, hunt monsters and race the maze timer. Built with Java Swing, AWT and WebSockets. |
| [Voxel Sandbox](https://github.com/duongdatdev/voxel-sandbox-unity) | Dig into procedural caves, light a tunnel with torches and plant crops above ground. Terrain loads in chunks as you explore. |
| [UniFire 2D](https://github.com/duongdatdev/unifire2d) | Your ship fires automatically. Use the mouse to steer through the fight in this Unity survival shooter. |
| [Caro Online](https://github.com/duongdatdev/caro-game-web) | Find an opponent and play five in a row in the browser. Laravel and Vue power matchmaking, chat and leaderboards. |

## Inside the build

- **World generation** · In Voxel Sandbox, Perlin noise shapes the terrain. Each chunk holds 16 × 16 × 128 blocks and loads as the player approaches.
- **Multiplayer** · Mini Island pairs a Java desktop client with a WebSocket server. Players see each other move and talk through speech bubbles inside the world.
- **Arcade gameplay** · In UniFire, the ship fires automatically so the player can focus on movement.
