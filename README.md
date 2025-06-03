# scripts

## About

`scripts` is a repo to host a collection of small scripts written for various purposes.

## minecraft

| File                                                                                                   | Description                                                                                                         | Notes                                                                                                                      |
| ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| [server.py](https://raw.githubusercontent.com/megabyte6/config/main/minecraft/server.py)               | A Python script used to simplify the management process of Minecraft Java servers running PaperMC.                  |                                                                                                                            |
| ~~[tmux.py](https://raw.githubusercontent.com/megabyte6/config/main/archive/minecraft/tmux.py)~~       | A Python script used to mange `tmux` sessions for Minecraft servers.                                                | **Not maintained**<br>Replaced by [server.py](https://raw.githubusercontent.com/megabyte6/config/main/minecraft/server.py) |
| ~~[server.ps1](https://raw.githubusercontent.com/megabyte6/config/main/archive/minecraft/server.ps1)~~ | A PowerShell script used to automate the setup and backup processes of a Minecraft Java server set up with PaperMC. | **Not maintained**                                                                                                         |
| ~~[tmux.ps1](https://raw.githubusercontent.com/megabyte6/config/main/archive/minecraft/tmux.ps1)~~     | A PowerShell script used to manage `tmux` sessions for Minecraft servers.                                           | **Not maintained**                                                                                                         |

---

# Unmaintained

## linux

### asus

| File                                                                                                           | Description                                                                                                                      | Notes                                                                                                                                                                                                                                                                                                                                                                |
| -------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ~~[limit-battery.py](https://raw.githubusercontent.com/megabyte6/scripts/main/linux/asus/limit-battery.py)~~   | A Python script used to set the battery's charge threshold for ASUS laptops since the MyASUS utility is not available for Linux. | **Not maintained, but should still work**<br>Replaced by [asusctl](https://asus-linux.org/)<br>To run, make sure this script is set to auto-run with the system. Then, run `sudo visudo` and add `yourusername ALL=(ALL) NOPASSWD: /bin/sh -c echo * > /sys/class/power_supply/BAT0/charge_control_end_threshold` where yourusername is replaced with your username. |
| ~~[limit-battery](https://raw.githubusercontent.com/megabyte6/scripts/main/archive/linux/asus/limit-battery)~~ | A Python script used to set the battery's charge threshold for ASUS Laptops since the MyASUS utility is not available for Linux. | **Not maintained**<br>Replaced by [limit-battery.py](https://raw.githubusercontent.com/megabyte6/scripts/main/archive/linux/asus/limit-battery.py)<br>To run, copy the file to `/usr/local/bin/` and run `sudo limit-battery <max charge percent>`                                                                                                                   |

| File                                                                                                              | Description                                         | Notes              |
| ----------------------------------------------------------------------------------------------------------------- | --------------------------------------------------- | ------------------ |
| ~~[setup.py](https://raw.githubusercontent.com/megabyte6/scripts/main/linux/setup.py)~~                           | For setting up new linux installations.             | **Not maintained** |
| ~~[setup.ps1](https://raw.githubusercontent.com/megabyte6/scripts/main/archive/linux/setup.ps1)~~                 | For setting up new linux installations.             | **Not maintained** |
| ~~[ugreen-driver.ps1](https://raw.githubusercontent.com/megabyte6/scripts/main/archive/linux/ugreen-driver.ps1)~~ | For installing the drivers for ugreen wifi adapter. | **Not maintained** |

## ubuntu

| File                                                                                                               | Description                                                 | Notes              |
| ------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------- | ------------------ |
| ~~[setup-headless.sh](https://raw.githubusercontent.com/megabyte6/scripts/main/archive/ubuntu/setup-headless.sh)~~ | Setup script for a fresh install of headless Ubuntu server. | **Not maintained** |
| ~~[setup.sh](https://raw.githubusercontent.com/megabyte6/scripts/main/archive/ubuntu/setup.sh)~~                   | Setup script for a fresh install of Ubuntu                  | **Not maintained** |
