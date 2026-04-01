# gort-plymouth-theme

Gort is a graphical splash screen animation that runs during the boot-up and shutdown process of Linux systems that support Plymouth

![GitHub Release](https://img.shields.io/github/v/release/richbl/gort-plymouth-theme?include_prereleases&sort=semver&display_name=tag&color=blue)

## Overview

**gort-plymouth-theme** is pretty much what it says on the box: a graphical splash screen animation that runs during the boot-up and shutdown process of Linux systems that support Plymouth. It's clever, and as an added bonus, I've included a startup audio file that can play as the desktop is starting. You really have to like [The Day the Earth Stood Still](https://en.wikipedia.org/wiki/The_Day_the_Earth_Stood_Still) to dig this project.

### Screens of the Gort Plymouth Theme

#### Start Up Screen Composite

<!-- markdownlint-disable MD033 -->
<p align="center">
<img alt="Screenshot showing startup animation" src="https://raw.githubusercontent.com/richbl/gort-plymouth-theme/refs/heads/main/.github/assets/gort_startup.png">
</p>
<!-- markdownlint-enable MD033 -->

#### Start Up Gif Used

<!-- markdownlint-disable MD033 -->
<p align="center">
<img width="300" alt="Screenshot showing startup animation" src="https://raw.githubusercontent.com/richbl/gort-plymouth-theme/refs/heads/main/.github/assets/startup_animation.gif">
</p>
<!-- markdownlint-enable MD033 -->

#### Shut Down Screen Composite

<!-- markdownlint-disable MD033 -->
<p align="center">
<img alt="Screenshot showing startup animation" src="https://raw.githubusercontent.com/richbl/gort-plymouth-theme/refs/heads/main/.github/assets/gort_shutdown.png">
</p>
<!-- markdownlint-enable MD033 -->

#### Shut Down Gif Used

<!-- markdownlint-disable MD033 -->
<p align="center">
  <a href="https://youtu.be/WjaNG7kHTqI"><img width="300" alt="Screenshot showing shutdown animation" src="https://raw.githubusercontent.com/richbl/gort-plymouth-theme/refs/heads/main/.github/assets/shutdown_animation.gif"></a>
</p>
<!-- markdownlint-enable MD033 -->

## Features

* Custom startup animation (with disk encryption password prompt)
* Custom shutdown animation
* Audio file included with the theme for DE startup playback

## Installation

As there are quite a few online resources available depending the Linux distribution you're using, I'll defer to your keen sense of adventure for finding the best way to install this theme. But, in short, here's the procedure at a high level:

1. Download this theme from [GitHub](https://github.com/richbl/gort-plymouth-theme)
2. Copy the project source files into `/usr/share/plymouth/themes/gort` on your system
3. Run `sudo plymouth-set-default-theme gort -R` (this is on a Fedora system), or similar, depending on your distribution
4. Optionally, delete the `README.md` and `LICENSE` files (they're not used by Plymouth)
5. Optionally, move the audio `*.ogg` file into a startup folder for playback during desktop startup (location and mechanism depends on your distribution)
6. Done!

## License

**gort-plymouth-theme** is released under the [MIT License](https://github.com/richbl/gort-plymouth-theme/blob/main/LICENSE).

Enjoy!
