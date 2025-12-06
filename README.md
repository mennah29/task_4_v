<div align="center">

# 🩺 Medical VR Simulation Suite 2.0

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-4A90E2?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Unity-2021.3+-00D084?style=for-the-badge&logo=unity&logoColor=white" alt="Unity"/>
  <img src="https://img.shields.io/badge/License-MIT-B794F4?style=for-the-badge&logo=opensourceinitiative&logoColor=white" alt="License"/>
  <img src="https://img.shields.io/badge/Platform-Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Windows"/>
</p>

<br>

**A centralized hub for launching high-fidelity surgical VR training modules.**

![Surgical Simulation Suite](assets/preview.png)
*(Note: Add a screenshot of the app here)*

</div>

<hr>

## 📋 Overview
The **Surgical Simulation Suite** is a PyQt5-based launcher designed to integrate various standalone Unity medical simulations into a single, cohesive user interface. It allows users to configure paths, manage modules, and launch training scenarios seamlessly.

## 🧬 Modules
The suite currently supports the following simulation modules:

| Module | Description | Icon |
| :--- | :--- | :---: |
| **Heart** | Cardiac Surgery VR | ❤️ |
| **Liver** | Hepatic Procedures VR | 🟤 |
| **Tooth** | Dental Training VR | 🦷 |
| **Flow** | Vascular Flow VR | 💧 |
| **Nose** | ENT Surgery VR | 👃 |

## ⚙️ Requirements

- **OS**: Windows 10/11
- **Python**: 3.8 or higher
- **Dependencies**: `PyQt5`

## 🚀 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/surgical-simulation-suite.git
   cd surgical-simulation-suite
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## 🎮 Usage

1. **Launch the Application**:
   ```bash
   python gui_vr.py
   ```

2. **First-Time Setup**:
   - Access **"⚙️ Configure Simulation Paths"**.
   - Browse and select the `.exe` file for each Unity module.
   - Status indicators will turn **Green** when ready.

3. **Running Simulations**:
   - Click the **Rocket Launch Button** on any card.

## 📁 Project Structure

```
surgical-simulation-suite/
├── assets/
│   └── icons/       # Custom vector icons for modules
├── gui_vr.py        # Main launcher application
├── requirements.txt # Python dependencies
└── README.md        # This documentation
```

## 🤝 Contributing
Contributions are welcome! Please open an issue to discuss proposed changes or submit a pull request.

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.
