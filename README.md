# enigma2_external_mover

## Description:

`move_to_usb.sh` is a script designed to free up space on Enigma2 devices by moving certain system directories (like Enigma2 and Python folders) to an external drive.

## Usage:

### Without Auto-Confirmation (Interactive):

```bash
wget -qO- https://raw.githubusercontent.com/Kamal-OS/enigma2-scripts/refs/heads/main/external_mover.sh | sh
```

### With Auto-Confirmation (No Prompts):

```bash
wget -qO- https://raw.githubusercontent.com/Kamal-OS/enigma2-scripts/refs/heads/main/external_mover.sh | sh -s -y
```
