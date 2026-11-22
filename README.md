# CombatFX-Lite

## Documentation

Full project documentation is available in the `Content/Documentation/` directory.

* **[README / Quick Start](Content/Documentation/README.pdf)** — Project overview and installation guide.
* **[Technical Documentation](Content/Documentation/DOCUMENTATION.pdf)** — System architecture, Blueprint implementation, execution flows, and API reference.
* **[FAQ](Content/Documentation/FAQ.pdf)** — Common questions, setup instructions, and troubleshooting.
* **[Changelog](Content/Documentation/CHANGELOG.pdf)** — Version history, implemented features, and planned improvements.

> **Note:** This repository contains a lightweight combat feedback system developed as a study and portfolio project in Unreal Engine 5. Its primary focus is demonstrating essential combat feedback mechanics using Blueprint Visual Scripting.

## Technical Details

* **Engine:** Unreal Engine 5
* **Implementation:** 100% **Blueprints**
* **Status:** Lite Version / Portfolio Project
* **Main Components:** `BP_CombatFX_Lite`, `BP_CombatFX_Component`
* **UI:** `WBP_DamageNumber`

## How to Run

1. Download or clone this repository.
2. Move the project folder into your local **Unreal Projects** directory.
3. Open the `.uproject` file using a compatible version of Unreal Engine 5.
4. Open the project and explore the Blueprint systems.

## Core Features

| Feature | Description |
| :--- | :--- |
| **Damage Numbers** | Displays floating damage values when an actor receives damage. |
| **Combat Feedback** | Provides visual feedback for combat interactions. |
| **Health Bar** | Displays the health status of the target or character. |
| **Blueprint Integration** | Uses Blueprint logic to manage and display combat feedback. |
| **Damage Number Widget** | Uses `WBP_DamageNumber` to display floating damage values. |

### Main Blueprint Elements

* **BP_CombatFX_Lite:** Main Blueprint responsible for the combat feedback system.
* **BP_CombatFX_Component:** Blueprint component designed to handle combat feedback functionality.
* **WBP_DamageNumber:** Widget responsible for displaying floating damage numbers.

## Future Improvements & Next Project Practices

Looking back at CombatFX-Lite, we recognize several architectural improvements that will be implemented in future projects.

Our main goal is to develop systems with better modularity, scalability, organization, and maintainability.

* **100% Modular Architecture:** Design systems using independent and reusable components, reducing unnecessary dependencies between gameplay systems.
* **Actor Components:** Separate individual responsibilities into dedicated Actor Components, making systems easier to reuse and integrate into different projects.
* **Blueprint Refactoring:** Improve Blueprint organization by using smaller, clearly defined functions and responsibilities instead of concentrating too much logic in a single Blueprint.
* **Better System Separation:** Establish clearer boundaries between gameplay logic, combat calculations, visual feedback, and UI.
* **Improved Documentation:** Provide more detailed technical documentation explaining Blueprint architecture, system flows, integration, and implementation decisions.

## Next Project: Action Combat Kit

Our next project will be **Action Combat Kit**.

Building on the experience gained from CombatFX-Lite, our objective is to develop a more advanced and fully modular combat system.

The next project will focus on better architecture, reusable components, cleaner Blueprint organization, and more professional development practices.

**Our goal is to make every new project better structured, more modular, and more polished than the previous one.**
