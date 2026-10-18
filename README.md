# Secret Vault — Educational Cryptography Demo

A reference implementation showing nonce generation, message authentication, constant-time MAC comparison and symmetric stream construction.

> **SECURITY WARNING:** This is a custom cryptographic construction for learning only. Do not store real credentials, customer data, tokens or secrets with it. Use a reviewed library such as `cryptography`'s AES-GCM or ChaCha20-Poly1305 in real systems.

## Requirements

Python 3.11+; standard library only.

## Run unit tests

```sh
python -m unittest discover -s . -p 'test_core.py' -v
```

- `core.py` — demo implementation
- `test_core.py` — unit tests
- `.github/workflows/tests.yml` — Python 3.11–3.13 CI
