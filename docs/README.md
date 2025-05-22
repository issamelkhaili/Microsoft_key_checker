# WinKeyCheck Documentation

## Overview

WinKeyCheck is a tool designed to validate Windows and Office product keys. This documentation provides detailed information about the tool's functionality, usage, and implementation.

## Table of Contents

1. [Installation](installation.md)
2. [Usage Guide](usage.md)
3. [API Reference](api.md)
4. [Configuration](configuration.md)
5. [Troubleshooting](troubleshooting.md)

## Quick Start

```bash
# Install dependencies
pip install -r requirements.txt

# Check a single key
python -m src.winkeycheck.keycheck pkey <Product Key>

# Check multiple keys
python -m src.winkeycheck.keycheck batch <Keys File>
```

## Contributing

Please refer to the main README.md for contribution guidelines. 