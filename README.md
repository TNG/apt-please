
# Please CLI apt repository

This repository contains the apt repository for the Please CLI, an AI helper script to create CLI commands.

## Installation

```bash
echo "deb https://tng.github.io/apt-please/ ./" | sudo tee -a /etc/apt/sources.list
sudo apt-get update

sudo apt-get install please
```