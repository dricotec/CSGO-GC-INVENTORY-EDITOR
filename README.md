# 🎮 csgo_gc inventory editor

**CSGO-GC-INVENTORY-EDITOR** is a **graphical WPF inventory editor** for [Mikko’s `csgo_gc`](https://github.com/mikkokko/csgo_gc).
It provides a modern Windows interface for editing and managing CS:GO inventories handled through the Game Coordinator without needing to modify inventory files manually.

---

## Features

* 🖥️ **Modern WPF UI:** Intuitive Windows interface for managing CS:GO inventory data.
* 🔗 **Seamless Integration:** Designed to work directly with [`csgo_gc`](https://github.com/mikkokko/csgo_gc).
* 🎨 **Visual Editing:** Modify items, skins, and their attributes visually.
* 💾 **Import / Export Support:** Load and save inventory configurations.

---

## Requirements

Before building or running, make sure you have:

* **Windows 10/11**
* **.NET 8.0 SDK** (or .NET 6.0+)
* (Optional) Visual Studio 2022 or JetBrains Rider for development

---

## 🛠️ Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/dricotec/CSGO-GC-INVENTORY-EDITOR.git
   cd CSGO-GC-INVENTORY-EDITOR
   ```

2. **Open the solution in Visual Studio**
   Open the `.sln` file in Visual Studio and restore NuGet packages if prompted.

3. **Build the project**
   Press `Ctrl+Shift+B` or use the **Build** menu.

4. **Run the application**
   Hit `F5` to launch the editor.

---

## Usage

1. Start the **CSGO-GC Inventory Editor**.
2. Connect to your running instance of `csgo_gc`.
3. Load your inventory data (from file or GC).
4. Add, remove, or modify items as desired.
5. Save or export your updated inventory configuration.

---

## 📂 Project Structure

```
CSGO-GC-INVENTORY-EDITOR/
├── CSGO-GC-INVENTORY-EDITOR.sln
├── src/
│   ├── App.xaml
│   ├── MainWindow.xaml
│   ├── MainWindow.xaml.cs
│   ├── Views/
│   ├── ViewModels/
└── README.md
```

---

## Info

* **Language:** C#
* **Framework:** WPF / .NET 8.0
---

## Future Plans

* Inventory preview images and item icons
* Steam/CS2 inventory import/export
  
---

## 🧾 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 🙏 Credits

* **[Mikko](https://github.com/mikkokko)** — Author of [`csgo_gc`](https://github.com/mikkokko/csgo_gc)
* **CSGO-GC-INVENTORY-EDITOR** — GUI built on top for user-friendly inventory editing experience

---
