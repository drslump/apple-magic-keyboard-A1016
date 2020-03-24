# Apple Magic Keyboard A1016

Keyboard layout and instructions for running the Apple Magic Keyboard A1016 (1st gen. 4 AA batteries) on Windows 10.

The Keyboard layout is for US International and implement dead keys for Spanish and Catalan's accented letters. It can be customized and compiled with (Microsoft Keyboard Layout Creator](https://www.microsoft.com/en-us/download/details.aspx?id=22339).

For the `Fn` key to work we'll need to install a keyboard driver by Apple, allegedly the last version
supporting the A1016 model is version 5.0.8.0, which is part of [Bootcamp 5.1.5722](https://support.apple.com/kb/DL1836). Download it and manually install `Bootcamp\Drivers\Apple\AppleKeyboardInstaller64.exe`.

In order to have the media keys working we would need the Bootcamp software but it doesn't support non-apple hardware officially, hence it's probably better to look for an alternative solution like
[uxsoft's AppleWirelessKeyboard app](https://github.com/uxsoft/AppleWirelessKeyboard).

