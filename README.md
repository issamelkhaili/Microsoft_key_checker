# 🪟 WinKeyCheck

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

A powerful tool to validate Windows and Office product keys with ease.

## ✨ Features

- Check individual Windows/Office product keys
- Batch validation of multiple keys
- Detailed error reporting
- Support for various Windows versions
- Non-invasive key checking option

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/winkeycheck.git
cd winkeycheck
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## 📦 Requirements

- Python 3.8 or higher
- `requests` package
- A valid pkeyconfig file (included by default for Windows 11 22H2)

## 🎯 Usage

### Check Individual Keys

```bash
python -m src.winkeycheck.keycheck pkey <Product Key>
```

### Batch Check Multiple Keys

```bash
python -m src.winkeycheck.keycheck batch <Keys File>
```

### Additional Options

- Use `-c` flag for comprehensive key checking (may consume one activation)
- Run `python -m src.winkeycheck.keycheck --help` for more options

## 📝 Output

- Individual checks: Shows if the key is valid or displays error information
- Batch checks: Generates a list of valid keys and saves detailed logs to `log.txt`

## 🔧 Configuration

The default pkeyconfig file for Windows 11 22H2 is included. Additional pkeyconfig files can be found in the `licensing_stuff` directory or downloaded from [SimplePidX](https://forums.mydigitallife.net/threads/simplepidx-simple-yet-powerful-product-key-checker.80300/).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Credits

- [asdcorp](https://github.com/asdcorp) for development and testing assistance
- [awuctl](https://github.com/awuctl) for `keycutter.py` and `pkeyconfig.py`
