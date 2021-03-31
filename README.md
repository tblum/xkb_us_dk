# xkb_us_dk

## Linux
XKB Keyboard Layout for US(€) keyboard with the Danish letters øæåØÆÅ & ß

- Patch /usr/share/X11/xkb/symbols/dk with dk.patch
- Patch /usr/share/X11/xkb/rules/evdev.xml with evdev.xml.patch

```
sudo patch /usr/share/X11/xkb/symbols/dk < dk.patch
sudo patch /usr/share/X11/xkb/rules/evdev.xml < evdev.xml.patch
```

You now have a keyboar called "Danish (US keyboard with Danish letters)"

You may need to run
```
sudo dpkg-reconfigure xkb-data
```
For the changes to take effect

## Windows
Download [Microsoft Keyboard Layout Creator (MSKLC)](https://www.microsoft.com/en-us/download/details.aspx?id=102134)

Load, compile, and install "us_dk.klc"
