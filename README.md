# apple-typography-for-linux

## Download:
- [SF Pro](https://github.com/sahibjotsaggu/San-Francisco-Pro-Fonts)
- [New York](https://github.com/yell0wsuit/New-York-fonts)
- [SF Mono](https://github.com/supercomputra/SF-Mono-Font)
- [SF Arabic](https://github.com/dpejoh/apple-typography-for-linux/releases)
- [Apple Color Emoji](https://github.com/samuelngs/apple-emoji-linux/releases)
- [fonts.conf](https://github.com/dpejoh/apple-typography-for-linux/releases)

## before applying:
Make sure to disable `Noto Color Emoji` font and other emoji fonts using any font manager or delete them from `/usr/share/fonts/` (I personally use **font-manager**).

## How to apply?
- Extract all fonts (.ttf files) to the `/home/$USER/.local/share/fonts` directory.
- Create `fontconfig` directory in `/home/$USER/.config/` and copy `fonts.conf` file in it.
- Run `sudo cp ~/.config/fontconfig/fonts.conf /etc/fonts/local.conf` to apply the font to the entire system.
- Run `sudo fc-cache -fv` to update the font cache.
- Log out or restart your device
> [!NOTE]
> You need to manually change the font in GNOME Tweaks (for GNOME users) and in some programs like browsers and terminal.
