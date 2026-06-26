# Bitcoin-Key-Compression-Tool

A simple Python 2.7 toolkit for Bitcoin developers and researchers.

This repository contains utilities for:

- Extracting **R**, **S**, and **Z** values from raw Bitcoin transactions.
- Working with Bitcoin public key compression.
- Learning and analyzing Bitcoin ECDSA signatures.

> **Educational & Research Purpose Only**

---

## Features

- Extract R, S, and Z values from Raw Bitcoin Transactions
- Bitcoin Public Key Compression utility
- Supports legacy Bitcoin transactions
- Built with Python 2.7

---

## Online Tools

### Get R, S and Z from Raw Transaction

https://2coin.org/getRSZfromRawTX.html

---

### Bitcoin Key Compression

https://iancoleman.io/bitcoin-key-compression/

---

## Requirements

- Python 2.7
- pip2

---

## Installation

Clone the repository:

```bash
git clone https://github.com/spyschools/Bitcoin-Key-Compression-Tool.git
cd Bitcoin-Key-Compression-Tool
```

Upgrade pip:

```bash
pip2 install --upgrade pip
```

Install required packages:

```bash
pip2 install bitcoin
pip2 install ecdsa
pip2 install utils
pip2 install base58
pip2 install blockchain
pip2 install cryptography
```

Or install everything at once:

```bash
pip2 install bitcoin ecdsa utils base58 blockchain cryptography
```

---

## Usage

Run the script:

```bash
python2 RawTX_RSZ.py
```

Follow the prompts and provide the Raw Bitcoin Transaction when requested.

---

## Example Workflow

1. Obtain a Raw Bitcoin Transaction.
2. Run:

```bash
python2 RawTX_RSZ.py
```

3. The script extracts:

- R
- S
- Z

4. Use the extracted values for Bitcoin signature analysis or educational research.

---

## Project Structure

```
Bitcoin-Key-Compression-Tool/
│
├── RawTX_RSZ.py
├── README.md
└── LICENSE
```

---

## Dependencies

- bitcoin
- ecdsa
- base58
- blockchain
- cryptography
- utils

---

## Compatibility

- Python 2.7
- Linux
- Windows
- macOS

---

## Disclaimer

This software is provided for educational, interoperability, and research purposes only.

Users are solely responsible for complying with all applicable laws and regulations. The author assumes no responsibility for misuse of this software.

---

## License

MIT License

---

## Author

**SpySchools**

GitHub:
https://github.com/spyschools
