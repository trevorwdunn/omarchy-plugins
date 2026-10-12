# My Omarchy plugins and contributions

An index of what I have made or changed for the [Omarchy](https://omarchy.org) bar and shell. Each plugin lives in its own repository so it can be installed on its own; this page is only the map.

> **A note on how these were made:** I am not a software engineer or programmer. Everything here was built with an AI assistant (Claude) for my own setup and is shared as is. All of it was tested on one machine: Omarchy 4.0.4, Hyprland 0.56.2.

## Plugins I made

| Plugin | What it does | Status |
|---|---|---|
| [Shelf](https://github.com/trevorwdunn/omarchy-shelf) | A drawer that hides bar widgets until you hover or click, with SUPER + drag to rearrange and no visible reload on a move | Experimental |
| [Glass Bar](https://github.com/trevorwdunn/omarchy-glass-bar) | Liquid glass behind the whole bar | Experimental |
| [Control Center](https://github.com/trevorwdunn/omarchy-control-center) | A macOS-style card behind one bar icon: Wi-Fi, Bluetooth, LocalSend, Do Not Disturb, Night Light, brightness, volume and peripheral batteries | Experimental |

The plugins are GPL-3.0-or-later. All three carry the `omarchy-plugin` topic, so they can also be found with a [topic search](https://github.com/search?q=user%3Atrevorwdunn+topic%3Aomarchy-plugin&type=repositories).

## Fixes sent to other people's plugins

| Plugin | Fix | Pull request |
|---|---|---|
| [omarchy-hw-monitor](https://github.com/meviusisback/omarchy-hw-monitor) by meviusisback | Stop an idle Intel dGPU being kept awake by sampling; ignore `nvidia-smi` error text when there is no NVIDIA card | [#4](https://github.com/meviusisback/omarchy-hw-monitor/pull/4) |
| [Omarchy_RustDeskPassthrough](https://github.com/kaaldev73/Omarchy_RustDeskPassthrough) by kaaldev73 | Stopping the plugin removed the user's global Super+F binding | [#1](https://github.com/kaaldev73/Omarchy_RustDeskPassthrough/pull/1) |

My forks of those repositories exist only to carry these pull requests.
