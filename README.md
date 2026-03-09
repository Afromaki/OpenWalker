# OpenWalker

> **The "MUGEN" of pedometers and the open-source spiritual successor to the Pokéwalker.**

OpenWalker is a highly modular, hackable pedometer and virtual pet RPG. Built with a barebones philosophy, it is designed to be completely customizable—allowing anyone to easily drop in their own sprites, write custom RPG logic, and build their own daily walking companion.

Currently in the **Mobile MVP phase**, the ultimate goal of OpenWalker is to become a standalone, 3D-printed hardware device featuring an E-ink display and an ESP32 microcontroller.

## 🌟 Core Philosophy

* **The MUGEN of Pedometers:** Bring your own art, your own logic, and your own companions. Asset loading is designed to be as simple as editing a configuration file.
* **Hardware Agnostic:** Sensor logic is completely decoupled from the game loop. Whether it's reading from an Android smartphone accelerometer or a dedicated MPU6050 chip, the game engine doesn't care.
* **Earn Your Keep:** A built-in RPG economy where real-world steps convert into digital currency to unlock hats, new companions, or alternate pixel-art states.

## 🗺️ Project Roadmap

### Phase 1: The Mobile MVP (Current Focus)
- [ ] **Engine:** Godot 4.x (C#)
- [ ] **Target:** Android APK
- [ ] **Features:** Hook into native mobile pedometer APIs, implement the core game loop, and establish the step-to-coin economy. 
- [ ] **Customization:** Basic shop UI to spend step-coins on sprite modifications.

### Phase 2: The E-Ink Hardware Translation
- [ ] **Translation:** Porting the C# game logic into C++ for microcontroller compatibility.
- [ ] **Hardware:** ESP32 brain, Waveshare 1.54" E-ink display, MPU6050 accelerometer, LiPo battery.
- [ ] **Fabrication:** Design and manufacture a custom 3D-printed shell. 
- [ ] **Final Build:** A standalone, pocket-sized companion with week-long battery life.

## 🛠️ Tech Stack (MVP)
* **Game Engine:** [Godot Engine](https://godotengine.org/)
* **Language:** C#
* **Data Storage:** Local persistent JSON/FileAccess

## 🚀 Getting Started (Coming Soon)
*(Instructions for cloning the repo, opening the Godot project, and compiling the Android APK will be added as the MVP takes shape.)*

## 🤝 Contributing
OpenWalker thrives on modularity. Whether you want to contribute better step-filtering algorithms, new pixel art templates, or optimize the eventual C++ hardware port, pull requests are welcome!

---
*Walking is better when you have a companion.*
