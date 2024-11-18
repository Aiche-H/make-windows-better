# My Windows Config

**This configuration builds upon the excellent work of [m1chaelwilliams](https://github.com/m1chaelwilliams) in their "make-windows-pretty" project [make-windows-pretty](https://github.com/m1chaelwilliams/make-windows-pretty). I have adapted it for Finnish keyboards and added some additional bindings I deemed beneficial expecially when using kanata homerow mods. My sincere thanks to [m1chaelwilliams](https://github.com/m1chaelwilliams) for the inspiration and foundational configurations.**

**wideo for the visual looks and basic information about the functionality found in

- [My Windows Config](#my-windows-config)
  - [My Terminal Setup](#my-terminal-setup)
  - [Window Manager Setup](#window-manager-setup)
  - [TopBar Setup](#topbar-setup)
  - [Searching](#searching)
  - [Translucent Taskbar](#translucent-taskbar)
  - [wallpaper](#wallpaper)
  - [Homerow mods](#homerow-mods)

## My Terminal Setup

- [Wezterm](https://wezfurlong.org/wezterm/index.html)
- [Wezterm Config File](wezterm.lua)

## Window Manager Setup

- [GlazeWM](https://github.com/glzr-io/glazewm)
- [GlazeWM Config File](config.yaml)

## TopBar Setup

- [Zebar](https://github.com/glzr-io/zebar)

To configure Zebar:

1. Copy [vanilla-clear](./vanilla-clear/) widget to Zebar directory

2. Then disable other widgets in Zebar system tray.

## Searching

- [Powertoys Run](https://learn.microsoft.com/en-us/windows/powertoys/run)
- I primarily rely on the Run functionality provided by PowerToys

## Translucent Taskbar

- [TranslucentTB](https://apps.microsoft.com/detail/9pf4kz2vn4w9?hl=en-US&gl=US)
- Configure the taskbar to be hidden by default. It should only appear when the mouse cursor is moved to the bottom of the screen.

## wallpaper

- [Here](mountain.jpg)
- also found in [uhdpaper](https://www.uhdpaper.com/2020/07/mountain-landscape-scenery-minimalist.html)

## Homerow mods

To make homerow keys work as modifiers when held install [Kanata](https://github.com/jtroo/kanata)

- I am using a finnish keyboard so the config is this [config](kanata.kbd)

To get it running on system tray

- install [Kanata Tray](https://github.com/rszyma/kanata-tray) in addition to the kanata
- config for tray [config](kanata-tray.toml)
- if you are using different paths for the programs update the correct paths to the kanata-tray.toml file!
