# sitelen pona UCSUR guide

## Installing a Font

The fonts offered here all pretend to be **Helvetica Neue**, a common backup font. This means anywhere Helvetica is available as a backup font, sitelen pona should render. This includes Discord!

## Windows

1. [Download this font and install it](./fonts/nasin-nanpa-patched.otf)
2. Done!

## Linux

1. [Download this font](./fonts/nasin-nanpa-patched.otf)
2. Copy it to `~/.local/share/fonts/`
3. Done!

## Android

TODO: kulupu Mimuki once wrote a guide to load UCSUR fonts. It no longer exists. We're looking for a replacement method. But in general, you cannot directly install fonts on Android.

# now what?

[If all else fails, you can always use this web based converter!](https://ilolili.daviesfam.org/)

## Installing an Input Method

**These guides are quick and highly simplified.**

### Windows

1. [Download and install the latest version of ilo Ajemi](https://github.com/dec32/Ajemi/releases/tag/nightly)
2. Press <kbd>Win</kbd> + <kbd>Space</kbd> to switch input methods.
3. [See Ajemi's README for how to use it!](https://github.com/dec32/Ajemi#Use)

### Linux

1. Install `ibus` and `ibus-table`
2. Download [this input table](https://raw.githubusercontent.com/gregdan3/sitelen-pona-ucsur-guide/main/tokipona.txt) (click the link then press <kbd>Ctrl</kbd><kbd>S</kbd>)
3. Create an input table with the following command: `sudo ibus-table-createdb -n /usr/share/ibus-table/tables/tokipona.db -s [path_to_input_table]`
4. Reload the ibus daemon: `ibus-daemon -drxR`
5. Right click the ibus applet -> `Preferences` -> `Input Methods` -> `Add` -> `English` -> `sitelen pona`
6. Press <kbd>Win</kbd> + <kbd>Ctrl</kbd> + <kbd>Space</kbd> to switch input methods
7. [See later in this README for how to use this table!](TODO)

### MacOS

NOTE: Untested as of February 2024:

1. [Download and install jan Tepo's input plugin](https://raw.githubusercontent.com/gregdan3/sitelen-pona-ucsur-guide/main/sitelen-pona.inputplugin) (click the link then press <kbd>Ctrl</kbd><kbd>S</kbd>)
2. Go to `System Preferences` -> `Keyboard` -> `Input Sources` and select the input method. It will be under "Chinese, Simplified".
3. Press <kbd>Ctrl</kbd> + <kbd>Option</kbd> + <kbd>Space</kbd> to switch input methods

### Android

- [jan Komi's (cominixo#5443)](https://github.com/cominixo/tokiponakeyboard/releases/tag/v0.1-sp)
- and [kulupu Mimuki's (rats#0976)](./android_keyboard.zip) which can be used with [this app](https://play.google.com/store/apps/details?id=de.humbergsoftware.keyboarddesigner), but it requires a paid addon to import the file.
