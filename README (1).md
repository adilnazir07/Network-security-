# Network Security Lab Experiments

This repository contains Python implementations for various Network Security laboratory experiments.

## Prerequisites

### Python Version

Install Python 3.8 or above.

Check Python version:

```bash
python --version
```

---

## Required Libraries

### 1. PyCryptodome

Used in:

* DES
* AES
* RSA
* Digital Signature

Install:

```bash
pip install pycryptodome
```

Verify Installation:

```bash
python -c "from Crypto.Cipher import AES; print('PyCryptodome Installed Successfully')"
```

---

### 2. PyCipher (Optional)

Used for:

* Playfair Cipher

Install:

```bash
pip install pycipher
```

Verify Installation:

```bash
python -c "from pycipher import Playfair; print('PyCipher Installed Successfully')"
```

---

## Complete Installation

Install all required packages:

```bash
pip install pycryptodome pycipher
```
```
pip install requirements.txt
```
```text
pycryptodome
pycipher
```

Install using:

```bash
pip install -r requirements.txt
```

---

## Experiments

### Experiment 1

Classical Ciphers

* Caesar Cipher
* Vigenère Cipher
* Playfair Cipher

File:
`Experiment1_Classical_Ciphers.py`

---

### Experiment 2

Symmetric Key Cryptography

* DES
* AES

File:
`Experiment2_DES_AES.py`

---

### Experiment 3

RSA Algorithm

File:
`Experiment3_RSA.py`

---

### Experiment 4

Diffie-Hellman Key Exchange

File:
`Experiment4_Diffie_Hellman.py`

---

### Experiment 5

Hash Functions

* MD5
* SHA1
* SHA256

File:
`Experiment5_Hashing.py`

Note:
Uses Python's built-in hashlib module.
No additional installation required.

---

### Experiment 6

Digital Signature using RSA

File:
`Experiment6_Digital_Signature.py`

---

### Experiment 7

Email Security using GPG

Install GPG:

#### Ubuntu/Kali

```bash
sudo apt update
sudo apt install gnupg -y
```

#### Windows

Download and install:

https://www.gpg4win.org

Generate Key Pair:

```bash
gpg --gen-key
```

---

### Experiment 8

Packet Sniffer

File:
`Experiment8_Packet_Sniffer.py`

Requirements:

* Linux Operating System
* Root Privileges

Run:

```bash
sudo python Experiment8_Packet_Sniffer.py
```

No additional Python libraries required.

---

### Experiment 9

MITM Attack Demonstration

Tools Required:

#### Kali Linux

Install Ettercap:

```bash
sudo apt install ettercap-graphical -y
```

Install Wireshark:

```bash
sudo apt install wireshark -y
```

Verify:

```bash
ettercap --version
wireshark --version
```

---

## Running Programs

Example:

```bash
python Experiment3_RSA.py
```

or

```bash
python3 Experiment3_RSA.py
```

---

## Notes

1. Run Packet Sniffer with Administrator/Root privileges.

2. MITM experiments should only be performed in a controlled lab environment.

3. Use CrypTool 2.0 to verify outputs for:

   * Classical Ciphers
   * DES
   * AES
   * RSA
   * Hash Functions
   * Digital Signatures

4. Never perform sniffing or MITM attacks on networks without authorization.

---

## Author

Network Security Lab Experiments
Python-Based Implementations
