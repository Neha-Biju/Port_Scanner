
# 🔍 Port Scanner

A multithreaded port scanning tool built with Python. This script scans all 65,535 TCP ports of a target IP address and reports which ports are open.

## 🧰 Features

- Scans all TCP ports (1–65535)
- Uses multithreading for fast execution (`ThreadPoolExecutor`)
- Displays scan banner with `pyfiglet`
- Graceful handling of keyboard interrupt and socket errors

## 🖥️ Requirements

- Python 3.x
- `pyfiglet` library

You can install the required library using pip:

```bash
pip install pyfiglet
```

## 🚀 Usage

Run the script using Python:

```bash
python port_scanner.py
```

You will be prompted to enter the target IP address:

```bash
Enter the IP: 192.168.1.1
```

Example output:

```
PORT SCANNING
______________________________________________
Scanning Target: 192.168.1.1
Scanning target at: 2025-05-07 14:03:00.000000
______________________________________________
[*] Port 22 is open
Searching.......
[*] Port 80 is open
Searching.......
```

## ⚠️ Disclaimer

This tool is intended for educational and authorized network testing purposes only. Scanning systems without permission is illegal and unethical.

## 📁 File Structure

```
port_scanner.py        # Main script file
README.md              # Project documentation
```


