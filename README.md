# Shadow Rift

A 3D action game that runs in the browser. You play a hunter who grows stronger with every kill and can raise defeated enemies as shadow soldiers to fight beside you.

**Play it:** https://achrafdayoubwork.github.io/shadow-rift/

## How it plays

- **Bosses make you stronger.** You only level up by defeating bosses: **+3 levels** for a Rift Guardian and **+5** for a major boss. Regular enemies give no levels. Each level adds 20 max HP and more strength and mana, and the soldier deploy limit grows by 1 every 2 levels.
- **The rifts grow with you.** Enemy HP keeps pace with your strength and their damage with your level, so leveling up never makes fights easy. Regular enemies sit a few levels below you, guardians just above you, and major bosses 5+ levels above. Each later rift adds more on top.
- **Dodge.** Press **Space** (or the Dodge button on a phone) to roll. It covers less ground than a dash but keeps you invulnerable longer. Rolling through an attack is a **Perfect Dodge** and gives +50% damage for 2 seconds.
- **Three lives per run.** When you fall:
  - You lose levels: everything gained in that rift, plus 10% (at least 1).
  - Every shadow you raised during that rift is lost. You keep the army you had when the rift opened.
  - You revive with full HP but **0 MP**, and all your shadows wait in reserve until you deploy them.
  - The same rift then restarts after 8 seconds.
  - On the third death the run ends. Your lives are shown as hearts next to your level.
- **Recover between fights.** If you take no damage for 7 seconds, you heal quickly (6% of max HP per second). The next hit you take stops the healing.
- **Arise.** Press **R**, or turn on voice with **V** and say "Arise!", to raise nearby fallen enemies as shadow soldiers. Each body fades after a short time, and raising it can fail.
- **Build an army.** Your shadows are saved between sessions. When a shadow falls, it has to reform over time and then costs mana to deploy again (14 MP for the weakest up to 140 MP for an S-rank).
- **Army limits.** At most 10 shadow soldiers and 1 shadow boss can fight at once. The soldier limit starts lower and grows with your level; the rest wait in reserve. You can own as many boss shadows as you raise, but only one fights at a time.
- **Choose who fights.** Pressing **Q** (or Deploy on a phone) pauses the game and opens a list of your shadows. Tap or click the ones you want, see the total MP cost and the free slots, then press Deploy (or Enter). "Auto-pick best" fills the slots with your strongest shadows.
- **Save and continue later.** Press **Esc** (or the ❚❚ button in the top-left corner on a phone) to pause. From there you can resume, or **Save & Exit** back to the title screen. Your level and current rift are saved; the title screen then offers **Continue** from that rift, with the lives you had left, or a new run from Rift 1. If you leave in the middle of a rift, you come back with the shadow army you had when that rift began: shadows raised in an unfinished rift are only kept once you clear it. Progress is also saved at the start of every rift.
- **Your army has a price.** Each shadow you own makes rift enemies 5% tougher and 2.5% stronger, up to 40 shadows. The rift panel shows the current bonus.
- **Mana is scarce.** It refills slowly (about 1 per second), so choose your abilities and deployments carefully.
- **Read the attacks.** Enemies wind up with a glowing flare in their weapon hand before each hit, lean back as red energy gathers around them before a special attack, and lunge into their swings. Anything that gets hit flashes and recoils.
- **Characters.** Characters use realistic lighting: the models keep their texture detail (straps, pouches, armour seams), each enemy has its own surface (metal plate shines, cloth and fur stay matte, the Rime Warden looks icy), and wolves have smooth natural-coloured fur. A subtle edge light shows who is who: purple for you and your shadows, the colour of their eyes for enemies, and gold for elites. You, the casters, knights, Warchief, Duelist, Reaper and Tyrant wear capes that billow as they run; armoured foes have shoulder plates; giants kick up dust as they walk; and a faint shadow mist trails behind you.
- **Clear the rifts.** Waves of goblins, dire wolves, orc brutes, warlocks and armored knights come through rift portals. **Every rift ends with a boss.** Bosses have phases, and their big attacks show a red warning zone on the ground before they hit.
  - **Every 5th rift** ends with a major boss: the Rift Colossus, the Bloodfang Alpha, the Ashen Lich or the **Void Tyrant**.
    - **Void Tyrant:** spinning cross-shaped void beams, gravity wells that drag you in before they explode, shadow-step strikes from behind below half HP, and below 25% an Event Horizon that blasts everything except the area close to it.
  - **The first boss** (end of Rift 1) is an easy introduction: much less HP and damage, no reinforcements, no Last Stand or enrage, and it doesn't heal.
  - **Every other rift** ends with a Rift Guardian:
    - **Goblin Warchief:** a war cry that enrages nearby enemies, fire bombs that leave burning ground, goblin reinforcements, and permanent bloodlust below 30% HP.
    - **Brood Mother:** venom spit that leaves poison pools, waves of hatchlings, and below half HP it burrows and erupts beneath you.
    - **Crimson Duelist:** chained dash strikes, a parry stance that blocks and punishes close attacks (use ranged attacks), and mirror images.
    - **Rime Warden:** frost nova and ice lances that slow you, and below half HP a frozen armor shell inside a blizzard.
    - **Storm Herald:** marching lines of lightning, chain lightning that jumps between you and your shadows, and below half HP an overcharge with a static surge that blinks it away.
    - **Bone Reaper:** a ring-shaped scythe sweep (stand right next to it to stay safe), death marks that hit where you stand three times, soul harvest that drains your shadows to heal it, and risen dead below 40% HP.
    - **Cinder Hound:** flame rushes that leave burning ground, rings of eruptions around you, and below half HP a trail of fire everywhere it runs.
  - **Wolf bosses are rare.** The Bloodfang Alpha, Brood Mother and Cinder Hound show up only a tenth as often as the others; most of the time another boss takes their place.
  - From rift 16, two guardians appear at once.
  - **A boss never has more than 5 of its summoned guards alive at once.**
  - **Each rift's boss is much stronger than the last:** more HP, more damage, more armor and faster attacks.
  - **All bosses:**
    - Below 20% HP they enter a **Last Stand**: 30% more damage, 25% less damage taken, faster abilities.
    - If the fight lasts too long (100 s for guardians, 150 s for major bosses), they **enrage** permanently.
    - After a stun they resist stuns for 8 seconds, and a stun can't cancel an attack they've already started.
    - Left alone for 8 seconds, they slowly heal (0.5% of max HP per second).
  - **Major boss extras:** the Colossus throws boulders at players who keep their distance, the Alpha chains its charges back to back, and the Lich's soulfire leaves burning ground below half HP.

## Controls

| Key | Action |
|---|---|
| W A S D / Mouse | Move / look (click to lock the mouse) |
| Left click | Dagger combo |
| Q | Pause and pick which shadows to deploy |
| G | Recall shadows |
| Shift | Dash (invulnerable while dashing) |
| Space | Dodge roll (Perfect Dodge: +50% damage for 2 s) |
| E | Shadow Rend: area blast |
| F | Umbral Step: teleport behind an enemy and backstab |
| 1 | Dagger Tempest: piercing dagger fan |
| 2 | Night Sovereignty: empower and heal your army |
| R | Arise |
| V | Voice commands: "Arise", "Come out" (deploys your best shadows automatically), "Return" (Chrome or Edge) |
| Tab | Shadow army roster |
| Esc | Pause menu: resume, or save & exit |
| P | Quick pause |

### On a phone or tablet

Open the same link on your phone and turn it sideways. On-screen touch controls appear automatically:

- **Left side:** drag to move (joystick)
- **Right side:** drag to look around; pinch to zoom
- **⚔ button:** hold to attack. Attacks aim at the nearest enemy automatically.
- **Button ring:** **Deploy** (right next to ⚔), Dash, Dodge, Shadow Rend, Umbral Step, Daggers, Sovereign and **ARISE**
- **Top-left ❚❚:** pause menu (resume, or save & exit)
- **Top row:** Recall, Army roster and Voice ("Arise!")

The game pauses while the phone is held upright. Graphics quality is lowered slightly on phones so the game runs more smoothly.

## Running locally

Open `index.html` in Chrome or Edge. You need an internet connection, because the game loads Three.js and the character models from the web.

## Credits

- Built with [Three.js](https://threejs.org/) (MIT).
- Soldier character model and animations from the [Three.js examples](https://github.com/mrdoob/three.js/tree/dev/examples/models/gltf), originally from Mixamo.
- Fox model from the [Khronos glTF Sample Assets](https://github.com/KhronosGroup/glTF-Sample-Assets/tree/main/Models/Fox): model by PixelMannen (CC0), rigging and animation by @tomkranis (CC-BY 4.0).

Shadow Rift is an original game and is not affiliated with any existing franchise.
