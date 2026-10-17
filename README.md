<p align="center">
  <a href="https://github.com/djehutylab/smart-glasses-firmware">💻 <b>Repo:</b> smart-glasses-firmware</a> &nbsp;|&nbsp; 
  <a href="https://github.com/djehutylab/smart-glasses-firmware">🟢 <b>Status:</b> Active Coding</a> &nbsp;|&nbsp; 
  <a href="#license">📜 <b>License:</b> GNU GPLv3</a>
</p>
<hr>

 
## 🔬 About This Repository
This repository holds the low-level firmware code running directly on the glasses' embedded system microcontroller/SoC. It manages hardware peripherals, display pipes, and low-latency data streams.

## 📂 Repository Structure
```text
smart-glasses-firmware/
├── .github/                   # CI/CD workflows (e.g., auto-building firmware)
├── docs/                      # API and memory map documentation
├── src/                       # Main source code files (.c, .cpp, .h)
│   ├── drivers/               # Display, BLE, and IMU sensor drivers
│   ├── display/               # UI rendering engine logic
│   └── main.cpp               # Main application loop
├── include/                   # Global header files
├── platformio.ini             # Build configuration (if using PlatformIO)
├── LICENSE                    # GPLv3 license text
└── README.md                  # Flashing guide, pinout diagrams, and dependencies
```

## 📜 License
This firmware code is open-source and licensed under the **GNU General Public License v3 (GPLv3)**. See the `LICENSE` file for full terms.
