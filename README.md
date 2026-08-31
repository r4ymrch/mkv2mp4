# MKV to MP4 Video Converter

Simple Bash script to convert MKV video format to MP4 using `ffmpeg`. This script supports direct convert as well as bulk/batch convert.

---

## Features

* **Fast local conversion**
* **Support Batch/Bulk Convert**

---

## Dependencies

Make sure your system (Linux / macOS / WSL) has the following dependencies installed:

1. **Bash Shell**
2. **ffmpeg**

### Ubuntu/Debian/Mint/Pop!_OS
```bash
sudo apt update
sudo apt install ffmpeg -y
```

### Arch/Manjaro/EndeavourOS/CachyOS
```bash
sudo pacman -Syu
sudo pacman -S ffmpeg
```

---

## Installation

```bash
git clone https://github.com/r4ymrch/mkv2mp4.git
cd mkv2mp4
chmod +x ./mkv2mp4
```

---

## Usage

### 1. Direct convert
```bash
./mkv2mp4 -s <PATH>
```

---

### 2. Batch/Bulk convert

1. Create new folder named `bulk`
2. Place all your MKV video in that folder
2. Run the script with flag `-b` or `--batch`:
   ```bash
   ./mkv2mp4 -b
   ```

---

## License
Free to use and modify for personal needs.
