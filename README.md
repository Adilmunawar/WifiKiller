```markdown
# Wi-Fi Hacking Tool

A Python-based command-line interface for performing various Wi-Fi network operations, including enabling monitor mode, scanning networks, capturing handshakes, and cracking Wi-Fi passwords. This tool utilizes essential Wi-Fi penetration testing tools such as `aircrack-ng`, `reaver`, and `wifite`.

## Features

- **Monitor Mode:** Start and stop monitor mode for wireless interfaces.
- **Network Scanning:** Scan for available Wi-Fi networks.
- **Handshake Capture:** Capture WPA/WPA2 handshakes for password cracking.
- **Password Cracking:**
  - Use `rockyou.txt` or custom wordlists.
  - Generate custom wordlists with specified parameters.
- **WPS Attacks:** Conduct WPS attacks using `reaver`, `bully`, or `wifite`.

## Requirements

- Python 3.x
- Linux (Kali Linux recommended)
- Administrative privileges (sudo access)
- Necessary tools (installed via the script)

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Wi-Fi-Hacking.git
cd Wi-Fi-Hacking
```

Run the installation script to set up required tools:

```bash
python3 wifi_hacking.py
```

## Usage

Run the script:

```bash
python3 wifi_hacking.py
```

Follow the on-screen instructions to select desired operations.

## Legal Notice

**This tool is intended for educational purposes only.** Ensure you have permission to test any network before using this tool. Unauthorized access to networks is illegal and unethical.

## Author

Coded by Adil Munwar

## License

This project is licensed under the MIT License.
```
