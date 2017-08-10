# ambiled-hd
Alternative firmware for the Ambiled HD product sold by Flytron.

# info
- Adalight compatible
- Maximum brightness limited in firmware. No need to limit brightness in hyperion/boblight/etc.
- Runs at high baudrate for long strips and fast refresh rate. Seems stable enough for me.

# How to use with Hyperion
- Change amount of leds in main.ino.
- Compile and upload to your device.
- Use hyperion.config.example as a starter for your own config.

I have included a platformio.ini with the right settings. Don't forget to install the fastLED library.
