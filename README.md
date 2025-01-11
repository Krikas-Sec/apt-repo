 APT Repository for PortHawk

This repository hosts the APT repository for [PortHawk](https://github.com/Krikas-Sec/PortHawk), a fast and lightweight port scanning tool.

## Usage

To add this repository to your system:

1. Add the repository to your `sources.list`:
   ```bash
   echo "deb [trusted=yes] https://<yourusername>.github.io/apt-repo stable main" | sudo tee -a /etc/apt/sources.list
   ```
Update your package list:

```bash
sudo apt update
```

Install PortHawk:

```bash
sudo apt install porthawk
```