# Shadow Rift

A 3D action game that runs in the browser. You play a hunter who grows stronger with every kill and can raise defeated enemies as shadow soldiers to fight beside you.

**Play it:** https://achrafdayoubwork.github.io/shadow-rift/

## How it plays

- **Every kill gives you a level.** Your HP, mana, strength and army size grow as you fight.
- **Recover between fights.** If you take no damage for 7 seconds, you heal quickly (6% of max HP per second). The next hit you take stops the healing.
- **Arise.** Press **R**, or turn on voice with **V** and say "Arise!", to raise nearby fallen enemies as shadow soldiers. Each body fades after a short time, and raising it can fail.
- **Build an army.** Your shadows are saved between sessions. When a shadow falls, it has to reform over time and then costs mana to deploy again.
- **Your army has a price.** Each shadow you own makes rift enemies 5% tougher and 2.5% stronger, up to 40 shadows. The rift panel shows the current bonus.
- **Mana is scarce.** It refills slowly (about 1 per second), so choose your abilities and deployments carefully.
- **Read the attacks.** Enemies wind up with a glowing flare in their weapon hand before each hit, and red energy gathers around them before a special attack.
- **Clear the rifts.** Waves of goblins, dire wolves, orc brutes, warlocks and armored knights come through rift portals. **Every rift ends with a boss.** Bosses have phases, and their big attacks show a red warning zone on the ground before they hit.
  - **Every 5th rift** ends with a major boss: the Rift Colossus, the Bloodfang Alpha or the Ashen Lich.
  - **Every other rift** ends with a Rift Guardian:
    - **Goblin Warchief:** a war cry that enrages nearby enemies, fire bombs that leave burning ground, goblin reinforcements, and permanent bloodlust below 30% HP.
    - **Brood Mother:** venom spit that leaves poison pools, waves of hatchlings, and below half HP it burrows and erupts beneath you.
    - **Crimson Duelist:** chained dash strikes, a parry stance that blocks and punishes close attacks (use ranged attacks), and mirror images.
    - **Rime Warden:** frost nova and ice lances that slow you, and below half HP a frozen armor shell inside a blizzard.
  - From rift 16, two guardians appear at once.
  - **Each rift's boss is much stronger than the last:** more HP, more damage, more armor and faster attacks.
  - **All bosses:**
    - Below 20% HP they enter a **Last Stand**: 30% more damage, 25% less damage taken, faster abilities.
    - If the fight lasts too long (100 s for guardians, 150 s for major bosses), they **enrage** permanently.
    - After a stun they resist stuns for 8 seconds, and a stun can't cancel an attack they've already started.
  - **Major boss extras:** the Colossus throws boulders at players who keep their distance, the Alpha chains its charges back to back, and the Lich's soulfire leaves burning ground below half HP.

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

### On a phone or tablet

Open the same link on your phone and turn it sideways. On-screen touch controls appear automatically:

- **Left side:** drag to move (joystick)
- **Right side:** drag to look around; pinch to zoom
- **⚔ button:** hold to attack. Attacks aim at the nearest enemy automatically.
- **Button ring:** Dash, Shadow Rend, Umbral Step, Gravebind, Daggers, Sovereign, Siphon and **ARISE**
- **Top row:** Deploy, Recall, Army roster, Voice ("Arise!") and Pause

The game pauses while the phone is held upright. Graphics quality is lowered slightly on phones so the game runs more smoothly.

## Running locally

Open `index.html` in Chrome or Edge. You need an internet connection, because the game loads Three.js and the character models from the web.

## Credits

- Built with [Three.js](https://threejs.org/) (MIT).
- Soldier character model and animations from the [Three.js examples](https://github.com/mrdoob/three.js/tree/dev/examples/models/gltf), originally from Mixamo.
- Fox model from the [Khronos glTF Sample Assets](https://github.com/KhronosGroup/glTF-Sample-Assets/tree/main/Models/Fox): model by PixelMannen (CC0), rigging and animation by @tomkranis (CC-BY 4.0).

Shadow Rift is an original game and is not affiliated with any existing franchise.
