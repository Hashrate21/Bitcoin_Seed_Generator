https://www.youtube.com/watch?v=aAxBcWxZH60&t

Video outlines everything you need to know. It's simple, basic, lightweight.

# Seed Phrase Generator

A simple, offline desktop tool for working with BIP-39 seed phrases (12 or 24 words).

It lets you build, complete, and validate mnemonic phrases using numbers, BIP-39 words, or raw 11-bit binary values.

---

## Features

- Support for **12-word** and **24-word** mnemonics
- Accepts three input formats:
  - Integers from `1` to `2048`
  - BIP-39 English words
  - Exactly 11 binary digits (e.g. `11001011100`)
- **Roll Number** – generate a random valid index/word
- **Roll Bits** – generate a random 11-bit binary value
- **Find Valid Last Words** – calculates all checksum-valid final words
- **Validate Full Phrase** – checks the BIP-39 checksum
- Live entry counter with color feedback
- Multiple themes with live switching:
  - Light
  - Dark
  - Neon Night
  - Python
- Completely offline – no network access required

## Security Notice
- This tool is intended for educational and testing purposes.
- Never use it to generate real wallet seed phrases on an online or compromised computer. Make sure you are offline.
- The author assumes no responsibility for any loss of funds.

---

## Requirements

- Python 3.8+
- `tkinter` (included with most Python installations)
- `english.txt` – the official BIP-39 English wordlist (2048 words)

The wordlist file must be in the same folder as the script (or next to the executable if frozen with PyInstaller).

---

## How to Run

```bash
python seed_phrase_generator.py
