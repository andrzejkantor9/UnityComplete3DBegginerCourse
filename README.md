This repository contains summary of 3 minigames made with help of course linked at the bottom.

### Argon Assault
Simple spaceship railshooter game. Movement is done via timeline with possibility to move slightly in all directions. Along the rail player faces enemies that must be shot or avoided, otherwise player dies on collision, displays highscore and repeats level. Rail movement can last indefinitely.

#### Input Information
Input | Action
--- | ---
WASD |  move
Space | shoot

- [Image album](https://imgur.com/a/7BKUdxp)
- [Executable build](https://drive.google.com/file/d/1KReOHTLTrFoAnDC2ihzcYk44YDU_Egr6/view)
- [Full repository](https://github.com/andrzejkantor9/ArgonAssault)

### Realm Rush
Simple tower defense game. Player starts with 250 gold, enemies try to get from starting to finish gate. Killing enemy grants 25 gold, placing turret uses 75 gold, enemy reaching finish gate removes 25 gold. Enemies are object-pooled and their hit points increase by 1 each time they die and they respawn at starting gate with a delay indefinitely. When gold goes below 0 player loses and scene is reloaded. Enemies move via pathfinding path - player can place turrets to change their path, but cannot block their path.

#### Input Information
Input | Action
--- | ---
LMB |  place turret

- [Image album](https://imgur.com/a/nEcWRCY)
- [Executable build](https://drive.google.com/file/d/1ZCls-VWJnf8OkeBVj4300zni7-AceVNE/view)
- [Full repository](https://github.com/andrzejkantor9/RealmRush)

### Zombie Runner
Simple shooter in dark scenery with zombies. Contains 3 different weapons (different range, damage, speed, reload speed, ammo, zoom), slowly fading flashlight, pickups, basic effects. Zombies slowly approach player within certain range and kill him if he isn't careful.

#### Input Information
Input | Action
--- | ---
LMB |  shoot
RMB | zoom in (only riffle)
1-3 (alpha-numeric) / scroll wheel | choose weapon
Shift | run

- [Image album](https://imgur.com/a/Ezp8nSR)
- [Executable build](https://drive.google.com/file/d/1kmpsm0rxb1P9z8x2FAfC6wem6tQzayfl/view)
- [Full repository](https://github.com/andrzejkantor9/ZombieRunner)

### Course link
- [Course link](https://www.gamedev.tv/p/complete-c-unity-game-developer-3d-online-course-2020/?coupon_code=HOORAY)
