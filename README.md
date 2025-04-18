﻿# `external_mover.sh`

## Description:

`external_mover.sh` is a script designed to free up space on Enigma2 devices by moving certain system directories (like Enigma2 and Python folders) to an external drive.

> [!CAUTION]
> This script **may erase data** from your drive. A confirmation message will always be displayed before proceeding, regardless of whether the `-y` argument is used.

## Usage:

### Normal run:

```bash
sh -c "$(wget -qO- https://raw.githubusercontent.com/Kamal-OS/enigma2-scripts/refs/heads/main/external_mover.sh)"
```

### Assume "yes" as answer to all prompts:

```bash
sh -c "$(wget -qO- https://raw.githubusercontent.com/Kamal-OS/enigma2-scripts/refs/heads/main/external_mover.sh)" -- -y
```
