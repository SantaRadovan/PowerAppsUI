# ⭐ Power Apps Rating Component

![Power Apps](https://img.shields.io/badge/built%20with-Power%20Apps-purple?style=flat-square)
![Version](https://img.shields.io/badge/version-1.0.0-blue?style=flat-square)
[![License](https://img.shields.io/github/license/SantaRadovan/PowerAppsUI?style=flat-square)](../../LICENSE)

A simple, reusable, and customizable **Rating Component** built for Power Apps Canvas Apps. Easily add star-based rating functionality to your apps with full support for dynamic input/output and theming.

---

## ✨ Features

- ⭐ Star-based rating (1 to 5 or custom range)
- 🎨 Fully customizable (star color, max stars)
- 🔄 Two-way binding (user input + read-only modes)
- 🔧 Lightweight and easy to integrate
- 📱 Mobile and desktop responsive

---

## 📸 Demo

![RatingComponent](https://github.com/user-attachments/assets/4c06c34c-c70b-4bbe-a944-5594eed059fe)

---

## 🚀 Getting Started

### 1. Download the Component

Download the latest `.msapp` file from the [Releases](https://github.com/yourusername/powerapps-rating-component/releases) section.

### 2. Import to Power Apps

1. Open your Power Apps Canvas App.
2. Go to **Tree view** > **Components** > **Import components**.
3. Upload the `.msapp` file.

### 3. Add to Screen

- Drag and drop the component onto your screen.

---

## ⚙️ Properties

| Property | Type | Description |
|---------|------|-------------|
| `RatingValue` | Number | The current rating (output or input) |
| `MaxStars` | Number | Max number of stars (default: 5) |
| `StarColor` | Color | Color of the filled stars |
| `IsReadOnly` | Boolean | Set to true to disable interaction |

