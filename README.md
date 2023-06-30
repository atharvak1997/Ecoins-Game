# ECOINS

<div align="center">
<h1 align="center">
<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" />
<br>ECOINS
</h1>
<h3>◦ </h3>
<h3>◦ Developed with the software and tools listed below.</h3>

<p align="center">
<img src="https://img.shields.io/badge/SVG-FFB13B.svg?style&logo=SVG&logoColor=black" alt="SVG" />
<img src="https://img.shields.io/badge/HTML5-E34F26.svg?style&logo=HTML5&logoColor=white" alt="HTML5" />
<img src="https://img.shields.io/badge/Dart-0175C2.svg?style&logo=Dart&logoColor=white" alt="Dart" />
<img src="https://img.shields.io/badge/Markdown-000000.svg?style&logo=Markdown&logoColor=white" alt="Markdown" />
<img src="https://img.shields.io/badge/JSON-000000.svg?style&logo=JSON&logoColor=white" alt="JSON" />
</p>
<img src="https://img.shields.io/github/languages/top/FrugalInnovationHub/ECOINS?style&color=5D6D7E" alt="GitHub top language" />
<img src="https://img.shields.io/github/languages/code-size/FrugalInnovationHub/ECOINS?style&color=5D6D7E" alt="GitHub code size in bytes" />
<img src="https://img.shields.io/github/commit-activity/m/FrugalInnovationHub/ECOINS?style&color=5D6D7E" alt="GitHub commit activity" />
<img src="https://img.shields.io/github/license/FrugalInnovationHub/ECOINS?style&color=5D6D7E" alt="GitHub license" />
</div>

---

## 📒 Table of Contents
- [📒 Table of Contents](#-table-of-contents)
- [📍 Overview](#-overview)
- [⚙️ Features](#-features)
- [🧩 Modules](#modules)
- [🚀 Getting Started](#-getting-started)
- [🗺 Roadmap](#-roadmap)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [👏 Acknowledgments](#-acknowledgments)

---


## 📍 Overview
Ecoins is an innovative, multi-platform application available on IOS, Android, and Web, designed to educate and engage users in the concept of waste management through an immersive and gamified experience. The primary objective of Ecoins is to raise awareness about the importance of recycling and proper waste disposal practices.

The game within Ecoins revolves around various items commonly found in our daily lives, such as plastics, metals, paper, cardboard, and more. Players are tasked with the responsibility of sorting these items correctly to maximize recycling efficiency. By successfully segregating the items, players earn valuable in-game resources like sun and water power-ups, which symbolize the renewable energy sources used in recycling processes.

As the game progresses, the complexity and difficulty level dynamically increase, presenting players with more challenging scenarios that require strategic decision-making and quick thinking. The aim is to simulate real-life waste management situations and encourage players to adopt environmentally friendly habits in their daily lives.

Ecoins not only provides an entertaining gaming experience but also serves as an educational platform. Throughout the game, players receive informative tips and facts about waste management, recycling techniques, and the positive impact of responsible waste disposal. By blending entertainment with education, Ecoins aims to empower individuals to make conscious choices and contribute to a sustainable future.

With its cross-platform compatibility, Ecoins ensures that players can access and enjoy the game seamlessly across multiple devices, making it easily accessible to a wide range of users. By incorporating gamification and interactive elements, Ecoins aims to make waste management engaging, enjoyable, and accessible to users of all ages, fostering a sense of responsibility and environmental consciousness in the process.

---

## ⚙️ Features

1. Tutorial for player
2. SFX controls
3. Sorting waste items
4. Clickable collectibles
5. Powerups
6. Levels


---

## 🧩 Modules

<details closed><summary>Root</summary>

| File                                                                                                   | Summary                                                                                                                                                                                                                                                                                                                                                                                                           |
| ---                                                                                                    | ---                                                                                                                                                                                                                                                                                                                                                                                                               |
| [.metadata](https://github.com/FrugalInnovationHub/ECOINS/blob/main/.metadata)                         | The code snippet provides metadata about a Flutter project, including version information, project type, and migration details for different platforms. It also includes a user-provided section to specify files that should be ignored by the migrate tool.                                                                                                                                                     |
| [basureros.dart](https://github.com/FrugalInnovationHub/ECOINS/blob/main/lib\basureros.dart)           | The provided code snippet defines a class called "Basureros" that extends the "SpriteComponent" class. It loads an image sprite, sets its position and size, and adds four instances of the "Basureros_HBox" class as child components. Each "Basureros_HBox" instance represents a different type of trash bin with a specific color, size, and position.                                                        |
| [basureros_hbox.dart](https://github.com/FrugalInnovationHub/ECOINS/blob/main/lib\basureros_hbox.dart) | The code snippet includes imports for various Flame libraries, such as components and collisions. It defines an enum for different types of basureros (garbage bins) and a class called Basureros_HBox that extends RectangleComponent. This class represents a rectangular component for a basurero and has various properties and methods. The onLoad method sets the paint and adds a hitbox to the component. |
| [banda_t_hole.dart](https://github.com/FrugalInnovationHub/ECOINS/blob/main/lib\banda_t_hole.dart) | The code snippet includes imports for various Flame libraries, such as components and collisions. This code defines the holes from which the items will fall.
| [basureros_hbox.dart](https://github.com/FrugalInnovationHub/ECOINS/blob/main/lib\basureros_hbox.dart) | The code snippet includes imports for various Flame libraries, such as components and collisions. It defines the conveyor belt on which the items will be traveling. |
| [game.dart](https://github.com/FrugalInnovationHub/ECOINS/blob/main/lib\game.dart) | The code snippet includes imports for various Flame libraries, such as components and collisions. Main file which initializes all the game elements. This file also has all the logic of which trash item should go in which bin and the speed of each trash item on the conveyor belt. It also keeps count of the core and track of the powerups. |
| [trash_items.dart](https://github.com/FrugalInnovationHub/ECOINS/blob/main/lib\trash_items.dart) | This file handles generation of trash items on the conveyor belt. New trash items are generated as old ones are recycled|

</details>

---

## 🚀 Getting Started

### ✔️ Prerequisites

Before you begin, ensure that you have the following prerequisites installed:
> - `ℹ️ Android Studio`
> - `ℹ️ Flame Game Engine`
> - `ℹ️ Java`

### 📦 Installation

1. Clone the ECOINS repository:
```sh
git clone https://github.com/FrugalInnovationHub/ECOINS
```

2. Change to the project directory:
```sh
cd ECOINS
```

3. Install the dependencies:
```sh
pub get
```

### 🎮 Using ECOINS

```sh
dart main.dart
```

### 🧪 Running Tests
```sh
dart test
```

---


## 🗺 Roadmap

> - [X] `ℹ️  Task 1: Implement Conveyor belt`
> - [X] `ℹ️  Task 2: Implement Holes in Conveyor belt`
> - [X] `ℹ️  Task 3: Implement Generations of trash items`
> - [X] `ℹ️  Task 4: Implement Generation of distractive items`
> - [X] `ℹ️  Task 5: Implement generation of powerups`
> - [X] `ℹ️  Task 5: Implement tutorials`

---

## 🤝 Contributing

Contributions are always welcome! Please follow these steps:
1. Fork the project repository. This creates a copy of the project on your account that you can modify without affecting the original project.
2. Clone the forked repository to your local machine using a Git client like Git or GitHub Desktop.
3. Create a new branch with a descriptive name (e.g., `new-feature-branch` or `bugfix-issue-123`).
```sh
git checkout -b new-feature-branch
```
4. Make changes to the project's codebase.
5. Commit your changes to your local branch with a clear commit message that explains the changes you've made.
```sh
git commit -m 'Implemented new feature.'
```
6. Push your changes to your forked repository on GitHub using the following command
```sh
git push origin new-feature-branch
```
7. Create a new pull request to the original project repository. In the pull request, describe the changes you've made and why they're necessary.
The project maintainers will review your changes and provide feedback or merge them into the main branch.

---

## 📄 License

This project is licensed under the `ℹ️  INSERT-LICENSE-TYPE` License. See the [LICENSE](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository) file for additional info.

---

## 👏 Acknowledgments

> - `ℹ️  List any resources, contributors, inspiration, etc.`

---
