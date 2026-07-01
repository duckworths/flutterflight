# 🦋 Flutter Flight: Special Edition

A physics-based mobile slingshot game celebrating the incredible migratory journey of the Monarch butterfly. Built with pure HTML5 Canvas and JavaScript, featuring a vibrant, juicy *Angry Birds* art style, dynamic wind currents, and mid-flight aerodynamic controls.

---

## 🎮 Gameplay & Mechanics

* **Slingshot Launch:** Drag and pull back on the butterfly to aim your trajectory. Curve or hook your drag path to apply a Magnus-style lateral spin mid-flight.
* **Action Taps (Flapping):** Tap the screen mid-flight up to 3 times to get a punchy vertical boost to escape danger.
* **Glide Cushion:** Tap and **hold** mid-flight to transition into a majestic horizontal glide, drastically reducing gravity's pull to help you navigate tight gaps.
* **Juicy Feedback:** Enjoy high-stakes screen-shake rumble on obstacle impacts and a massive festive particle explosion upon a successful landing.

---

## 🎯 Objectives

1.  **Collect Nectar:** Gather glowing yellow flowers (`🌼`) along your flight path to rack up points and achieve a 3-star rating.
2.  **Avoid Obstacles:** Steer clear of sticky spiderwebs and aggressively patrolling dragonflies.
3.  **Safe Landing:** Descend safely onto the highlighted **Milkweed Target Zone** (`🌾`) to lay your eggs and progress to the next leg of the migration.

---

## 📂 Repository & Asset Structure

To make sure the game renders the custom graphics correctly, ensure your repository matches this file layout:

```text
flutter-flight/
├── index.html            # Main game code and rendering engine
├── README.md             # Project documentation
└── assets/               # Sliced transparent cartoon PNG images
    ├── hero_glide.png    # Frame 1: Butterfly gliding or idling
    ├── hero_up.png       # Frame 2: Wings up (triggered on flap)
    ├── hero_down.png     # Frame 3: Wings down (triggered on falling)
    ├── hero_attack.png   # Frame 4: Aggressive face (triggered during launch pull)
    ├── flower.png        # Juicy vector nectar target flower
    ├── dragonfly.png     # Goofy, big-eyed dragonfly enemy patrol
    ├── milkweed.png      # Glowing milkweed landing patch plants
    └── background.png    # Beautiful cartoon sky/mountain horizon
