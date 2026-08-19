# Paste Rabbit (v1.0.0)

A lightweight, system-wide desktop text expansion utility and code snippet repository engineered for speed, privacy, and seamless local productivity. 

## 🚀 Core Features
- **Local-First Security:** Complete offline operation with zero external data sync vectors or cloud dependencies.
- **Cryptographic Storage:** Complete database persistence encrypted locally using Fernet (AES-128) via PBKDF2 key derivation.
- **Global Event Hook System:** Frameless UI widget bound to global system hotkeys for instant text injection into any native Windows application.
- **Commercial Licensing Pipeline:** Secure integration with Lemon Squeezy API for cryptographic license key verification and local device instance binding.

## 🛠️ Technical Stack
- **Language:** Python 3.11+
- **Security & Cryptography:** `cryptography` (Fernet, PBKDF2), `bcrypt`
- **Network & Integration:** `requests` for asynchronous external license activation
- **Distribution:** Compiled binary deployment engineered via `PyInstaller`

## 📦 Architecture & Monetization
This application represents a production-grade Minimum Viable Product (MVP) designed with full commercial launch metrics. The system utilizes a dual-state architecture:

1. **Trial Runtime State:** Local verification maps user initialization limits across a standalone local configuration registry.
2. **Activated Runtime State:** An outbound network handshake communicates securely with Lemon Squeezy endpoints to fetch activation boolean properties before securely caching state flags in local system storage via high-entropy encryption keys.

## 🛠️ Installation & Local Development

### Prerequisites
- Python 3.11 or higher
- Windows 10 / 11 (64-bit environment)

### Setup
Clone the repository and install dependencies:
```bash
git clone https://github.com
cd wordvaultpro
pip install -r requirements.txt
```

### Compiling the Executable
To bundle the Python application into a standalone Windows binary:
```bash
pyinstaller --onefile --windowed --name="PasteRabbit" main.py
```

## 🔒 Security Posture
Paste Rabbit implements a Zero-Knowledge local data pattern. Plaintext text assets and personal user templates are never transmitted across public networks. The application requires outbound internet connectivity exclusively during the initial product key activation sequence.
