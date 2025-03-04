# Amalgamemnon's House Rule Macro Pack

Welcome to **Amalgamemnon's House Rule Macro Pack**, a collection of macros designed to automate custom house rules for **Pathfinder 2nd Edition** in **Foundry VTT**.

## 📜 Overview

This module provides automation for two house rules:

1. **Shift** – A free action that allows a character to Stride 5 feet if they have not used a movement action earlier in the turn. The character then gains the **Immobilized** condition until the end of their turn.
2. **Better Potions** – Enhances the usability of potions by streamlining their application, making potion consumption a smoother experience during combat.

## ⚙️ Installation

To install this module in **Foundry VTT**, follow these steps:

1. Open **Foundry VTT** and navigate to the **Module Browser**.
2. Click **Install Module**.
3. Paste the following manifest URL:

https://github.com/amalgamemnon/amalgamemnon-House-Rule-Macro-Pack/releases/latest/download/module.json

4. Click **Install**, then enable the module in your **Game Settings**.

## 🛠️ Usage

### Shift Macro
- **Description:** Allows a character to Stride 5 feet as a free action, provided they have not used movement earlier in the turn.  This free action has the Movement trait.  Charaacters are immobilized until the end of their turn after using this action.
- **Effect:** The macro will announce the action in chat and automatically apply the **Immobilized** condition, which will be removed at the end of the turn.
- **How to Use:** Click the macro when the condition is met.

### Better Potions Macro
- **Description:** Better Potions is a buff to healing potions (and similar).  The house rule we allow is that players can use potions (and similar items) for 1 action given that they're readily available (not stowed in a backpack or similar) and roll for healing.  We also allow players toc choose to spend 2 actions to instead get maximum healing instead of rolling for healing.  This macro will detect any items with the consumable and healing traits in your inventory, allowing you to choose which to use.  It will then ask whether you'd like to use the 1-action (roll for healing) or 2-action (maximum healing) version of the potion.
- **Effect:** Drinking a potion automatically applies the correct healing amount based on the choice, and deducts the healing potion from your inventory.
- **How to Use:** Select your token, then activate the macro, which will pop up a dialog to use the healing potions.

## 📝 Notes
- These macros are written specifically for **Pathfinder 2E** in Foundry VTT.
- If you encounter any issues, feel free to report them via [GitHub Issues](https://github.com/amalgamemnon/amalgamemnon-House-Rule-Macro-Pack/issues).

## 🤝 Contributing
Contributions are welcome! If you have ideas for improvements or additional house rule automation, feel free to submit a **pull request** or open an **issue**.

---

**Created by:** [Amalgamemnon](https://github.com/amalgamemnon)  
**License:** MIT  

Happy gaming! 🎲✨
