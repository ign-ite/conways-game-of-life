# 🌱 Conway's Game of Life — Pygame Edition

A cellular automaton simulation brought to life with Python and Pygame. Build your own patterns, bring them to life, and watch them evolve... or perish. 🧬

---

## 🎮 Features

- ✅ Click to add or remove live cells  
- ▶️ Press `Space` to start or pause the simulation  
- 🎲 Press `G` to generate a random initial population  
- 🧼 Press `C` to clear the board  
- 🧠 Classic Game of Life rules implemented  
- 🎨 Grid-based visualization using `pygame`  

---

## 🔧 Installation

Make sure you have Python installed. Then:

```bash
pip install pygame
```

Clone this repository and Run:
```bash
python colorful_main.py
```

---

## 🕹️ Controls

| Key / Action       | Function                      |
|--------------------|-------------------------------|
| `Left Click`       | Toggle cell alive/dead        |
| `Space`            | Play / Pause simulation       |
| `G`                | Generate a random pattern     |
| `C`                | Clear the grid                |
| `Close Window`     | Quit                          |

---

## 📚 How It Works

Each cell interacts with its 8 neighbors:

- 👶 A dead cell with **exactly 3** live neighbors becomes alive (birth).  
- ❤️ A live cell with **2 or 3** live neighbors survives.  
- ☠️ All other live cells die (underpopulation or overpopulation).  

---

## 🧠 Behind the Scenes

- Grid is updated based on the classic rules of Conway’s Game of Life.  
- Efficient use of `set` for storing alive cells and calculating next states.  
- Customizable speed and grid size.  

---

## 🤓 About Me

Made with love by Varun — a curious mind exploring AI, code, and pixels.  
Let’s connect on [LinkedIn](https://www.linkedin.com/in/your-profile)!

---

## 🌟 Star This Repo

If you enjoyed the simulation or learned something cool, feel free to ⭐ it!  
Every star gives a new cell life! (Not really... but it feels that way 😄)

