# RelayPi

RelayPi is a Raspberry Pi–based relay controller project.  
It provides scripts and configurations to manage multiple relay boards (4-port, 8-port, and 16-port) using Python.

---

## 📂 Repository Structure

- **.github/workflows/**  
  Contains CI/CD workflows, including the SLSA generic generator for secure builds.

- **4port/**  
  Scripts and configurations for controlling a 4-port relay board.

- **8port/**  
  Scripts and configurations for controlling an 8-port relay board.

- **16port/**  
  Scripts and configurations for controlling a 16-port relay board.

---

## 🚀 Features

- Python 3–compatible scripts for relay control  
- Support for multiple relay board sizes (4, 8, 16 ports)  
- Modular design for easy extension  
- GitHub Actions workflows for automation and security compliance  

---

## ⚙️ Requirements

- Raspberry Pi (any model with GPIO support)  
- Python 3.x  
- RPi.GPIO library (or equivalent GPIO control library)  

Install dependencies:

```bash
sudo apt-get update
sudo apt-get install python3 python3-pip
pip3 install RPi.GPIO
```

---

## 🔧 Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/rish3119/relaypi.git
   cd relaypi
   ```

2. Navigate to the desired relay board folder (`4port`, `8port`, or `16port`).

3. Run the script:
   ```bash
   python3 relay_control.py
   ```

4. Follow on-screen instructions to toggle relays.

---

## 📜 Contributing

Contributions are welcome!  
- Fork the repo  
- Create a feature branch  
- Submit a pull request  

Please ensure Python 3 compatibility and follow existing code style.

---

## 🛡️ License

This project is licensed under the MIT License.  
See the `[Looks like the result wasn't safe to show. Let's switch things up and try something else!]` file for details.

---

## 🙌 Acknowledgments

- Raspberry Pi community for GPIO libraries  
- Contributors who helped migrate scripts to Python 3  
