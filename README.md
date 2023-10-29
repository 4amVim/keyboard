# At a glance

## Keymap
![image](https://github.com/4amVim/keybware/assets/4429609/c533dc19-aea2-4012-8f51-aea9f5c1dded)


## Key Matrix:
![image](https://github.com/4amVim/keybware/assets/4429609/06cfb467-3d95-418c-9aa6-bb3ae8573876)


## Building

> [!NOTE]
> Sources:
> 
> [keymap-drawer](https://keymap-drawer.streamlit.app/?zmk_url=https%3A%2F%2Fgithub.com%2F4amVim%2Fkeyboard%2Fblob%2FV3.0%2Fconfig%2Fadv360.keymap)
> 
> [key matrix](assets/key-positions.md)


### Requirements
* Install `make` using `sudo apt-get install make` inside the WSL2 instance.


### Build firmware locally
0. (Optionally) bust the cache with `make clean`
1. Execute `make`.
2. Check the `firmware` directory for the latest firmware build.



#### Other support
> [!IMPORTANT]
> RGB Underglow, backlight and power management sections aren't relevant to the Advantage 360 Pro's custom ZMK fork. For more information see [this note]([#note](https://github.com/KinesisCorporation/Adv360-Pro-ZMK/blob/71a5ba15e5a1e07779d4c9e2af66a13841dd4cb2/README.md#note)

- [ZMK documentation](https://zmk.dev/docs)
- [web based GUI available for editing the keymap](https://kinesiscorporation.github.io/Adv360-Pro-GUI)
- https://kinesis-ergo.com/support/kb360pro/#firmware-updates
- https://kinesis-ergo.com/support/kb360pro/#manuals
