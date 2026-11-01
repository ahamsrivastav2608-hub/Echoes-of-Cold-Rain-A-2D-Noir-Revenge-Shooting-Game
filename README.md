# Echoes of Cold Rain (A 2D Noir Revenge Story)

> *"Rain doesn't wash away blood. It just makes the stains spread deeper into the concrete."*

**Echoes of Cold Rain** is a story-driven 2D top-down action shooting game centered on grief, vengeance, and the haunting search for closure.

You play as **Daniel Ward**, an ex-homicide detective whose wife Clara and 7-year-old daughter Lily were executed in a calculated syndicate hit. Left for dead with three bullets near his heart, Daniel survived with only one physical keepsake: **Lily's music box**.

---

## 🎮 How to Launch & Play

You can play immediately with zero installation required:
1. Double-click or open [`index.html`](file:///d:/project antigravity/index.html) in any modern web browser (Google Chrome, Microsoft Edge, Firefox, Brave, Safari).
2. Click **BEGIN HUNT** on the title screen to initialize the procedural sound engine and start the campaign.

---

## 📖 Story & Escalating Level Progression

The game follows a 3-act narrative structure. At each level, the game becomes significantly harder with more resilient enemies, dangerous AI behaviors, and complex boss mechanics:

### 🚇 Act I: The Subway Metro — *"The Lookout"*
* **Target**: **Victor 'Viper' Vance**
* **Setting**: A flooded, decaying subway terminal illuminated by flickering fluorescents and rain filtering through gratings.
* **Minions**: Street thugs armed with 9mm pistols and pipes.
* **Boss Mechanics**: Victor is erratic and cowardly. He sprints between cover, rolls away from Daniel's crosshairs, and sprays rapid Uzi bursts.
* **Emotional Beat**: Victor breaks down, coughing blood onto the tracks. He confesses that he only drove the van and begged the enforcers not to harm the little girl, giving Daniel the location of the harbor warehouse before dying.

### ⚓ Act II: Pier 14 Shipping Docks — *"The Enforcer"*
* **Target**: **Boris 'The Bear' Reznov**
* **Setting**: Rusted industrial shipping container yard during a ferocious midnight thunderstorm with lightning flashes and water ripples.
* **Minions**: Heavily armored PMC mercenaries with tactical assault rifles, flanking AI, and higher durability.
* **Boss Mechanics**: Boris carries a heavy combat shotgun and a ballistic riot shield that deflects 85% of frontal fire. Players must roll behind him, flank his guard, and avoid his devastating seismic charge stomps.
* **Emotional Beat**: Boris mocks Daniel with his dying breaths, forcing Daniel to confront what he has become: *"Look at your hands, Ward. How many bodies did you drop tonight to get to me? You're just another killer in the dark."*

### 🏙️ Act III: The Obsidian Penthouse — *"The Architect"*
* **Target**: **Julian Mercer**
* **Setting**: The 78th-floor glass penthouse overlooking a dark metropolis, with shattered glass, rain sweeping through panoramic windows, and classical music playing.
* **Minions**: Elite cyber-guards equipped with high-speed lasers and combat support drones.
* **Multi-Phase Boss Battle**:
  * **Phase 1**: Julian uses high-tech dual plasma revolvers in three-way spreads.
  * **Phase 2 (HP < 66%)**: Julian deploys automated combat drones and fires spiraling kinetic bolts while dashing with cyber-afterimages.
  * **Phase 3 (HP < 33%)**: Overdrive bullet-hell barrage with rapid teleports and relentless laser pressure.
* **Emotional Climax & Epilogue**: Julian offers his entire fortune for mercy. Daniel realizes that revenge will never replace Lily's laughter. In a poignant resolution, Lily's music box plays its final chime as dawn breaks through six months of rain, giving Daniel the strength to lay down his weapon and choose to live.

---

## 🕹️ Controls

| Action | Control | Description |
| :--- | :--- | :--- |
| **Move** | <kbd>W</kbd> <kbd>A</kbd> <kbd>S</kbd> <kbd>D</kbd> or Arrows | 8-directional smooth movement |
| **Aim & Shoot** | <kbd>Mouse</kbd> + <kbd>Left Click</kbd> | 360-degree aiming with crosshair; hold for automatic fire |
| **Dodge Roll** | <kbd>Space</kbd> or <kbd>Right Click</kbd> | High-speed evasive dash with invulnerability frames |
| **Focus (Bullet-Time)**| <kbd>Shift</kbd> | Slows down time (35% speed), muffles sound, heightens heartbeat; recharges with kills |
| **Weapon Selection** | <kbd>1</kbd>, <kbd>2</kbd>, <kbd>3</kbd> or <kbd>Q</kbd> / Scroll Wheel | Swap between Revolver, Shotgun, and Carbine |
| **Reload** | <kbd>R</kbd> | Reload active weapon magazine |
| **Advance Dialogue** | <kbd>Space</kbd> or <kbd>Left Click</kbd> | Skip typing or advance story text |

---

## 🔫 Weapons Arsenal

1. **Service Revolver (.44)**: Daniel's trusty police service weapon. High precision, heavy single-target stopping power, infinite reserve ammo.
2. **Tactical 12G Shotgun**: Devastating close-range weapon that fires 7 high-impact pellets per shell. Excellent for crowd control and flanking Boris.
3. **Covert Carbine (5.56)**: High-capacity, rapid-fire automatic rifle ideal for suppressing Julian's drone swarms and agile cyber-guards.

---

## 🎵 Procedural Web Audio Engine

* **Zero external audio file dependencies**: Built entirely using the browser's native Web Audio API (oscillators, biquad filters, white noise rain generators, and gain envelopes).
* **Adaptive soundtrack**:
  * *A-minor melancholic piano motifs* during story dialogues and quiet moments.
  * *Tense dark synth basslines* during tactical shootouts.
  * *Heavy brass warning horns* when boss murderers confront Daniel.
  * *Lily's Music Box lullaby* for the emotional epilogue.
* **Dynamic Lowpass Filter & Heartbeat**: When Grief Focus (Bullet-Time) is activated, high frequencies are muffled while Daniel's pulsing heartbeat echoes in the player's ears.

---

## 🎨 Visual Atmosphere & Architecture

* **Dynamic Lighting**: Flashlight cones cast forward into shadows, muzzle flashes illuminate rooms, and lightning flashes illuminate the rain.
* **Persistent Gore Decals**: Blood splatters and shell casings stain the battlefield.
* **Water Physics**: Rain drops produce real-time expanding water ripples on asphalt and marble floors.
* **Cinematic Letterboxing & Typewriter Dialogue**: Immersive narrative presentation with character portraits and expressive text speeds.
