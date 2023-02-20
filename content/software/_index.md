+++
archetype = "default"
title = "Software"
weight = 2
+++

*updated 01/26/2023*

This page lists some of the software you might need when following along with the book. This page will be kept up to date with the latest and greatest.

## IDEs

An Integrated Development Environment, or "IDE" is a piece of software that provides a comprehensive and featureful environment for writing code, including things like autocompletion, folder management, debugging and so on.

### Visual Studio Code
Links

* [Visual Studio Code Homepage](https://code.visualstudio.com/)
* [Download VSCode](https://code.visualstudio.com/download)
* [Download the Go Extension](https://marketplace.visualstudio.com/items?itemName=golang.go)

Visual Studio Code (VSCode)is a powerful free IDE based on Electron, which makes it cross-platform. To set it up, first install VSCode from thw download link above, and then install the Go extension.  Then, once you've opened the app, go to {{< mono >}}File -> Add Folder To Workspace{{< /mono >}} and navigate to your home folder, documents folder, or wherever you want to put the directory, or workspace, for working on code from the book.  Click {{< mono >}}New Folder{{< /mono >}} and create a folder called `goinaction`.

Then open the command palette by hitting {{< mono >}}CMD-shift-p{{< /mono >}}or {{<mono>}}Windows-shift-P{{</mono>}} and type {{<mono>}}go mod{{</mono>}} so it will highlight the **Go: Initialize go mod** option.  hit enter and type `goinaction` when prompted. Save the generated {{<mono>}}go.mod{{</mono>}}, and you should be ready to Go!

## Terminal Emulators

Terminal emulators, are so-called because they "emulate" the experience of using a terminal interface, whether or not your sustem has one built in. But, really, they are often much more than that, and some of them provide a lot of sophisticated functionality to make the experience flexible, powerful and convenient.

The following is a (far from exhaustive) list of some popular terminal emulators you might want to consider when doing work on the command line.

### Terminal Emulators for Windows
* [Windows Terminal](https://apps.microsoft.com/store/detail/windows-terminal/9N0DX20HK701?hl=en-us&gl=us&SilentAuth=1&rtc=1) The official MS Terminal app is actually pretty good! Definitely the best place to start if you're unfamiliar.
* [Cmder](https://cmder.app/) - A well-designed app by a terminal enthusiast. Fully featured and portable with Linux commands integrated into the bundled "Git For Windows", which also comes with Git, so there's that!
* [MobaXterm](https://mobaxterm.mobatek.net/) - If you're looking for batteries-included, this is it, but it might be a little much for most users.

You can also enable [WSL](https://learn.microsoft.com/en-us/windows/wsl/install) if you're feeling a bit more adventurous. This will enable to to run a Linux environment alongside Windows.

### Terminal Emulators for macOS
* [iTerm2](https://iterm2.com/) - The classic is still the best. You can't go wrong with iTerm2. It's what I use every day.
* [Alacrittu](https://github.com/alacritty/alacritty) - Very fast, if that matters to you, thanks to its OpenGL rendering engine. Configuration is done with text files though, and you'll have to locate them on disk, so it's not nearly as easy to get set up as iTerm2. Works on Linux, too.
* [Warp](https://www.warp.dev/) - The new kid on the block, but this is definitely some next-level stuff with advanced views, graphical integration, multi cursors, and the lot. Just make sure you read the [privacy statements](https://www.warp.dev/privacy) and [opt-out of telemetry](https://docs.warp.dev/getting-started/privacy#how-to-disable-telemetry-and-crash-reporting) if you're concerned about it.

### Terminal Emulators for Linux

Let's be honest, you probably know what you're doing when it comes to terminal emulators, but here are some options anyways.
* [Kitty](https://github.com/kovidgoyal/kitty/) - Like Alacritty, it's a hardware-accelerated terminal. Also like Alacritty, you will need to configure it with text, but at least the config file is well-documented and easy to access.
* Alacritty also works on Linux
* [Foot](https://codeberg.org/dnkl/foot) - Fast and featureful with commandline graphics, thanks to libsixel. Also application integration for things like loading links in the browser for you, if you want.
