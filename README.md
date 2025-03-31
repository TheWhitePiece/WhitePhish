# WhitePhish

A Python phishing script for login phishing, image phishing, video phishing, and more.

---

## Description

WhitePhish is a versatile phishing tool that supports multiple phishing methods, including login, image, and video phishing. It includes built-in templates and leverages tunneling services for efficient phishing page deployment.

---

## Installation (Linux)

### Prerequisites
Ensure you have the following installed:
- **git**
- **python3**
- **php**
- **openssh-client**

### Installation Steps

#### Debian-based Systems (Ubuntu, Kali-Linux, Parrot)
```bash
sudo apt install git python3 php openssh-client -y
```

#### Arch-based Systems (Manjaro)
```bash
sudo pacman -S git python3 php openssh --noconfirm
```

#### Redhat-based Systems (Fedora)
```bash
sudo dnf install git python3 php openssh -y
```

---

## Cloning and Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/thewhitepiece/WhitePhish
   ```

2. **Navigate to the Directory**
   ```bash
   cd WhitePhish
   ```

3. **Install Required Dependencies**
   ```bash
   pip3 install -r files/requirements.txt
   ```

---

## Running WhitePhish

```bash
python3 whitephish.py
```

For more options and help, run:
```bash
python3 whitephish.py --help
```

---

## Credits

- **WhitePhish** is developed by **The White Piece**.
- This project is inspired by the work of **KasRoudra**. Check out [KasRoudra's GitHub](https://github.com/KasRoudra) for more tools and resources.

---
