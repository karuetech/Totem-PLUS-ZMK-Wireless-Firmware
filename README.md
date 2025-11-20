<h1>Wireless Totem PLUS ZMK Config</h1>

It's a totem with an extra key like the Konrad with a side switch to turn on a gaming mode. Tried to include every ZMK dongle in this repository. Thanks to Eiga for the reference and all the dongle creators.

<img src="https://github.com/karuetech/Totem-PLUS-1-ZMK-Wireless-Firmware/blob/master/keymap-drawer/20251119_102100.jpg">


### Steps

## Fork or Clone Repository
   - Click **Fork** in the top right to copy this repo to your GitHub account, or
   - Run `git clone` locally.

   > Forking is recommended, because GitHub Actions will automatically build your firmware.

## Keymap Editing
   -  use the [ZMK Keymap Editor](https://nickcoutsos.github.io/keymap-editor/):
   - Map your repository to the editor to see the current settings
   - Make changes on the site and save
   - your repository will be compiling the build with your new configuration
   - read below on flashing your keyboard

## Dongle Flashing
   - Turn all devices off
   - go to **Actions → your latest run → Artifacts** and download the firmware (`.uf2`) files.
   - Flash the dongle with the **appropriate** `settings_reset` file.
   - Flash the dongle controller with the `dongle` file.
   - Flash the first half with the the `settings_reset` file.
   - Flash the first half with the `left` or `right` files.
   - Repeat last two steps for the other half.

> [!WARNING]  
> When using both Nice!Nano and Seeed XIAO microcontrollers, make sure you are flashing them with the correct files!


<img alt="image" src="https://raw.githubusercontent.com/karuetech/Totem-PLUS-ZMK-Wireless-Firmware/68c322bc7786d50d86c63f3ac38f8f288e61f105/keymap-drawer/my_keymap.svg" />
