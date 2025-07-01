# 🧭 Power Apps Collapsible Navbar Component

![Power Apps](https://img.shields.io/badge/built%20with-Power%20Apps-purple?style=flat-square)
![Version](https://img.shields.io/badge/version-1.0.0-blue?style=flat-square)
[![License](https://img.shields.io/github/license/SantaRadovan/PowerAppsUI?style=flat-square)](../../LICENSE)

A simple, reusable, and customizable **Collapsible Navbar Component** built for Power Apps Canvas Apps. Easily navigate between screens using a modern collapsible navbar with full customization—define navbar items, set colors, and add transitions.

---

## ✨ Features

- 📂 Collapsible navigation menu
- 🎨 Fully customizable (color, transitions, navbar items)
- ⚡ Lightweight and easy to integrate
- 📱 Mobile and desktop responsive

---

## 🎥 Demo

![CollapsibleNavbar](https://github.com/user-attachments/assets/6e9aa33f-13c2-420e-9c7a-2ce25f0b9ec8)

---

## 🚀 Getting Started

### 1. Download the Component

Download the latest `.msapp` file.

### 2. Import to Power Apps

1. Open your Power Apps Canvas App.
2. Go to **Insert** > **Get more components** > **Import component**.
3. Upload the `.msapp` file.

### 3. Add to Screen

- Drag and drop the component onto your screen.

### 4. Define Navbar Items

- Create a table for the `NavbarItems` property (see usage example below).

---

## ⚙️ Properties

| Property       | Type   | Description                       |
|----------------|--------|-----------------------------------|
| `NavbarItems`  | Table  | Define the items for the navbar   |
| `Color`        | Color  | Set the color of the component    |

---

## 🛠️ Usage

Define your `NavbarItems` table like this:

```powerapps
[
    // First navbar item
    {
        sequence: 1, // Number of item, easily to reorder
        name: "Example Tab 1", // Display name of the screen
        icon: Icon.Printing3D, // Icon
        screen: Screen1 // Specify the screen
    },
    // Second navbar item
    {
        sequence: 2,
        name: "Example Tab 2",
        icon: Icon.Draw,
        screen: Screen2
    },
    {
        sequence: 3,
        name: "Example Tab 3",
        icon: Icon.Money,
        screen: Screen3
    },
    {
        sequence: 4,
        name: "Example Tab 4",
        icon: Icon.AddUser,
        screen: Screen4
    },
    {
        sequence: 5,
        name: "Example Tab 5",
        icon: Icon.Cars,
        screen: Screen5
    }
]
