# 🚀 Space Dodger

An action-packed, arcade-style space shooter built using MIT Scratch blocks. Take control of a powerful spaceship, blast through waves of incoming comets, and upgrade your ship to survive the deep cosmic void.

## 🔗 Project Links
* **▶️ Play Live Browser Version:** [Click here to play Space Dodger](https://aks242424.github.io/Space-Dodger-Game/Space%20Dodger.html)
* **🌐 MIT Scratch Platform:** [View Original Project Page](https://scratch.mit.edu/projects/1328673826)

---

## 📝 Project Description
This project is a dynamic, event-driven space arcade game where players must navigate a hazardous asteroid field. As you destroy comets and increase your score, your spaceship automatically upgrades to handle tougher threats. With a built-in health tracking system and escalating difficulty levels, the game tests agility and quick reflexes.

### Key Gameplay Features:
* **Multiple Comet Levels:** Comets spawn randomly with varying sizes and hit-point values, requiring strategic target prioritization.
* **Dynamic Spaceship Upgrades:** Reaching specific score milestones automatically evolves your spaceship's visual appearance and fire power.
* **Health & Vitality System:** Players start with 5 lives. Visual indicators track damage whenever a comet bypasses defenses or hits the ship.
* **Projectile Combat:** High-speed laser mechanics with optimized block scripts to handle multiple on-screen clones smoothly.

---

## 🕹️ How to Play

### Controls:
* **← Left Arrow / → Right Arrow:** Move the spaceship left and right.
* **Touch Gestures:** Mobile-friendly touch support is integrated for seamless handheld play.
* **Spacebar:** Shoot laser projectiles.

### Rules & Objectives:
1. **Destroy Comets:** Shoot comets down to earn points and clear your path.
2. **Handle Tougher Targets:** Keep an eye out for high-level comets; they require multiple hits to shatter!
3. **Survive:** Avoid direct collisions with comets. If you lose all **5 lives**, the game ends.
4. **Upgrade:** Maximize your score to unlock advanced spaceship tiers automatically.

---

## 🛠️ Technical Concepts Used
This project applies fundamental computer science and game development concepts:
* **Object Cloning & Memory Management:** Utilized Scratch's cloning engine to dynamically spawn random comets and clear lasers from memory upon impact to prevent lag.
* **Collision Detection Logic:** Implemented precise hitbox detection sequences between lasers, comets, and the player sprite.
* **State Management:** Handled multiple game states (Start Screen, Active Gameplay, Level Up Upgrades, and Game Over) using global message broadcasting.
* **Data Variables:** Tracked dynamic values including player `Lives`, `Score`, and variable comet health levels.

---

## 🎨 Notes and Credits
* **Development:** Game design, programming logic, and script assembly completely engineered by **Arun**.
* **Visuals & Assets:** Space-themed graphics and artistic assets were curated, edited, and seamlessly integrated to fit the gameplay environment.
* **Attribution:** Built using the MIT Scratch framework. Special thanks to the Scratch community for inspiration and educational resources.

---

## 📁 Repository Structure
```text
├── LICENSE          # MIT License documentation
├── README.md        # Project documentation (this file)
├── index.html       # Playable standalone web version (via TurboWarp) deployed on GitHub Pages
└── Space-Dodger.sb3 # Raw source file containing block scripts and assets
