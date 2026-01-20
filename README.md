# Paws Cat Store 🐾

A professional-grade retail application designed to manage cat breeds and accessory inventory. This project bridges the gap between a high-performance C++ backend and a user-friendly web interface.

## 🏗 Project Architecture
The project follows a **Modular Design** to ensure scalability and clean code separation:

* **`include/`**: Header files (`.h`) defining the blueprints for Cats, Accessories, and Store logic.
* **`src/`**: Implementation files (`.cpp`) containing the core business logic.
* **`data/`**: Persistent storage using CSV and TXT files for inventory and sales logging.
* **`web/`**: The frontend layer, including organized assets, modern CSS grids, and interactive JavaScript.

## 🚀 Features
- **Data Persistence**: Loads inventory from `inventory.csv`.
- **Transaction Logging**: Records every successful purchase into `sales.txt`.
- **Input Normalization**: Case-insensitive search using utility helpers.
- **Responsive Web UI**: A clean product grid featuring cat breeds like Persian, BSH, and Munchkin.

## 🛠 Setup & Installation

### Prerequisites
- **Compiler**: GCC/MinGW (g++) installed and added to your System PATH.
- **Tools**: VS Code with the "Live Server" extension.

### Compilation
To build the C++ backend, run the following command in your terminal:
```bash
g++ src/*.cpp -I include -o PawsStore
