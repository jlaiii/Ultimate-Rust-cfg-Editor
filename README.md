# Ultimate Rust Configuration Editor

A suite of powerful, client-side web tools designed to simplify editing your Rust configuration files. Make complex changes to your game settings, keybinds, and favorite servers through an intuitive graphical interface, all without leaving your browser.

**Your privacy is paramount:** All file processing is done locally on your computer. Your configuration files are never uploaded to any server.

## 🚀 Live Site

**Access the live tools here: [https://jlaiii.github.io/Ultimate-Rust-cfg-Editor/](https://jlaiii.github.io/Ultimate-Rust-cfg-Editor/)**

---

## Features

The hub provides three powerful, purpose-built editors:

### ⚙️ Game Settings Editor (`client.cfg`)
Expose and edit advanced settings normally buried in the console.

*   **Visual Editor:** Manipulate hundreds of game variables with sliders, dropdowns, and toggles.
*   **Easy Navigation:** Settings are grouped by category for clarity.
*   **Quick Search:** Instantly find any setting by its name or description.
*   **Smart Snap:** A helper tool to easily snap slider values to sensible increments.

### ⌨️ Keybind Editor (`keys.cfg`)
Build the perfect control scheme without ever opening the console.

*   **Visual Keyboard:** See all your current binds and potential conflicts at a glance.
*   **Advanced Command Builder:** Create complex actions (crafting queues, chat messages, toggles) without manual typing.
*   **Robust Parsing:** Handles even complex, multi-command binds correctly.
*   **Conflict Detection:** Automatically highlights keys bound to multiple actions.

### ⭐ Favorite Servers Editor (`favorites.cfg`)
Manage your list of favorite servers with ease.

*   **Simple CRUD:** Easily add, edit, and delete servers from your list.
*   **Sort & Filter:** Organize your server list by name, date added, or use the search bar to find a specific server instantly.
*   **JSON Export:** Copy your server list as a clean JSON object for backup or sharing.

---

## How to Use

1.  Navigate to the [**live editor site**](https://jlaiii.github.io/Ultimate-Rust-cfg-Editor/).
2.  Choose the editor you wish to use (e.g., "Keybind Editor").
3.  Locate your Rust `cfg` folder. This is typically found at:
    ```
    C:\Program Files (x86)\Steam\steamapps\common\Rust\cfg\
    ```
4.  Drag and drop the corresponding file (`client.cfg`, `keys.cfg`, or `favorites.cfg`) onto the web page.
5.  Use the interface to make your desired changes.
6.  Click the "Download" or "Export" button to save your modified file.
7.  Replace the original file in your `cfg` folder with the one you just downloaded. **It's a good idea to back up your original file first!**

---

## 📜 Disclaimer

This project is an unofficial fan-made tool and is not affiliated with, endorsed, or sponsored by Facepunch Studios. All game assets and names are the property of their respective owners.

---

## ⚖️ License and Usage

**Copyright (c) 2024 jlaiii**

This project is provided for personal use only. You are permitted to use the live version of this tool and download its output for your own personal gameplay.

You are **not permitted** to:
*   Copy, modify, or distribute the source code.
*   Re-host, re-publish, or create derivative works from this project.
*   Use this project for any commercial purposes.

The source code in this repository is provided for transparency, but it is not under an open-source license. All rights are reserved.
