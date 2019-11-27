# Tosh System

A fluxbox style inspired by classic macos. ⚠️ Work in progress! Working on a script to automate color choice and modify other files. Possibly expand to configuring a linux (probably) minimal install.

![Screenshot of style in use.](/screenshots/tosh-system-screenshot.png)

## Dependencies

- fluxbox
- ChicagoFLF font

## Usage

```bash
cd ~/.fluxbox/styles
git clone https://github.com/violetcraze/tosh-system.git
```

For the time being you need to change the following to `~/.fluxbox/init`.

```none
session.screen0.toolbar.placement: TopCenter
session.screen0.titlebar.left: Close Minimize Maximize
session.screen0.titlebar.right: Shade # optional
```
