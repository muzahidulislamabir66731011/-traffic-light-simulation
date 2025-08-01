# 🚦 ESP32 Traffic Light Simulation (5 LEDs)

Simulates a 5-color traffic light system using an ESP32 and basic LEDs.


## 🔌 GPIO Pin Mapping

| LED Color | GPIO Pin | ESP32 Label | Resistor | Notes |
|-----------|-----------|-------------|----------|-------|
| Red       | GPIO 2    | G2          | 220Ω     | Anode to GPIO |
| Yellow    | GPIO 4    | G4          | 220Ω     |           |
| Green     | GPIO 5    | G5          | 220Ω     |           |
| Blue      | GPIO 15   | G15         | 220Ω     |           |
| White     | GPIO 18   | G18         | 220Ω     |           |

---

## 🛠️ Setup Instructions

1. Insert 5 LEDs into the breadboard.
2. Connect a **220Ω resistor** from each GPIO pin to the **anode (+)** of an LED.
3. Connect all **cathodes (–)** of LEDs to **GND rail**.
4. Connect breadboard GND rail to **ESP32 GND** pin.
5. Upload the `LED_Sequencer.ino` code via Arduino IDE.
6. Observe the LED sequence acting as a traffic light.

---

## 📁 Files Included

- `LED_Sequencer.ino` — Code
- `.gitignore`, `LICENSE`, `README.md`

---

## 📃 License

MIT License — use and modify freely.
