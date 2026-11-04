# Shadow Rift

A 3D action game that runs in the browser. You play a hunter who grows stronger with every kill and can raise defeated enemies as shadow soldiers to fight beside you.

**Play it:** https://achrafdayoubwork.github.io/shadow-rift/

## How it plays

- **Every kill gives you a level.** Your HP, mana, strength and army size grow as you fight.
- **Arise.** Press **R**, or turn on voice with **V** and say "Arise!", to raise nearby fallen enemies as shadow soldiers. Each body fades after a short time, and raising it can fail.
- **Build an army.** Your shadows are saved between sessions. When a shadow falls, it has to reform over time and then costs mana to deploy again.
- **Clear the rifts.** Waves of goblins, dire wolves, orc brutes, warlocks and armored knights come through rift portals. Every 5th rift has a boss: the Rift Colossus, the Bloodfang Alpha or the Ashen Lich. Each boss has phases and attacks that warn you with red zones on the ground.

## Controls

| Key | Action |
|---|---|
| W A S D / Mouse | Move / look (click to lock the mouse) |
| Left click | Dagger combo |
| Shift | Dash (invulnerable while dashing) |
| E | Shadow Rend: area blast |
| F | Umbral Step: teleport behind an enemy and backstab |
| 1 | Gravebind: pull enemies together and stun them |
| 2 | Dagger Tempest: piercing dagger fan |
| 3 | Night Sovereignty: empower and heal your army |
| 4 | Soul Siphon: drain life from nearby enemies |
| R | Arise |
| Q / G | Deploy / recall shadows |
| V | Voice commands: "Arise", "Come out", "Return" (Chrome or Edge) |
| Tab | Shadow army roster |
| P | Pause |

## Running locally

Open `index.html` in Chrome or Edge. You need an internet connection, because the game loads Three.js and the character models from the web.

## Credits

- Built with [Three.js](https://threejs.org/) (MIT).
- Soldier character model and animations from the [Three.js examples](https://github.com/mrdoob/three.js/tree/dev/examples/models/gltf), originally from Mixamo.
- Fox model from the [Khronos glTF Sample Assets](https://github.com/KhronosGroup/glTF-Sample-Assets/tree/main/Models/Fox): model by PixelMannen (CC0), rigging and animation by @tomkranis (CC-BY 4.0).

Shadow Rift is an original game and is not affiliated with any existing franchise.
