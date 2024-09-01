
# Honkers Launcher for Ubuntu

## Installation

### Launchpad PPA (Recommended)
To install the launcher via the unofficial PPA, first add the PPA to your system's Software Sources.
```bash
sudo add-apt-repository ppa:thundergemios10/honkers-launcher
sudo apt update
```

Then install the launcher with:
```bash
sudo apt install honkers-launcher
```

### Manual
To install the launcher via terminal run:
```bash
sudo dpkg -i honkers-launcher_1.8.0_all.deb
```

## Uninstall

To uninstall the launcher via terminal run:
```
sudo apt remove honkers-launcher
```

If you wish to remove the Launchpad PPA, you can run:
```bash
sudo add-apt-repository --remove ppa:thundergemios10/honkers-launcher
sudo apt update
```