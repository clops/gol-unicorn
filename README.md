# 🌌 Conway’s Game of Life on Cosmic Unicorn

A vibrant, animated twist on Conway’s Game of Life designed for the [Pimoroni Cosmic Unicorn](https://shop.pimoroni.com/products/cosmic-unicorn) 32×32 RGB LED matrix. This project brings cellular automata to life with smooth color fading, interactive brightness control, and automatic re-seeding for endless pixel art animation.

---

## 🧠 Features

- **32×32 LED Grid**: Simulates life and aging with 8 brightness levels.
- **Custom Life Rules**:
  - Dead cell becomes alive if it has exactly 3 live neighbors.
  - Live cell survives with 2 or 3 neighbors.
  - All others increment toward “dead” (fading effect).
- **Visual Fading**: Color gradients visualize cell age.
- **Dynamic Palettes**: Color mapping cycles every new simulation.
- **Control Brightness** with Unicorn hardware buttons.
- **Automatic Detection**:
  - Extinction
  - Stability
  - Oscillation
- **Random Seeding** via center-origin random walk.

---

## 🚀 Getting Started

### 🔧 Prerequisites

- [Raspberry Pi Pico SDK](https://github.com/raspberrypi/pico-sdk)
- [Pimoroni Unicorn Library](https://github.com/pimoroni/pimoroni-pico)
- A working C++ development setup for the Raspberry Pi Pico


----------------------------



## gol for cosmic unicorn

requires pico-sdk.


```
make -j
```



`//:~`
