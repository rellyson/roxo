# Roxo - Gnome terminal

<div align="center">

![gnometerminal](https://img.shields.io/static/v1?message=>=3&logo=gnometerminal&color=231e32&label=gnome%20terminal)
[![License: MIT](https://img.shields.io/badge/License-MIT-97ca39.svg)](https://opensource.org/licenses/MIT)

<img src="../../assets/gnome-term.png" width="150" />
</div>

**Roxo theme** for the gnome terminal application.

## Installation

- Get [roxo-theme.dconf](https://raw.githubusercontent.com/rellyson/roxo/main/resources/gnome-terminal/roxo-theme.dconf)
  and save it to a directory, e.g. `/opt/roxo/roxo-theme.conf`.
- Open gnome terminal and execute the command:

  ```sh
  dconf load /org/gnome/terminal/legacy/profiles:/ < /opt/roxo/roxo-theme.conf
  ```

- Open _Preferences_ and select the `Roxo Theme` profile.
