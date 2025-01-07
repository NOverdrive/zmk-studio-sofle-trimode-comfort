# Fixes and updates

-2025/12/08 
1. zmk reserved layers added - you can now add extra layers within zmk studio, if you need more than 4, just copy the code in the keymap file and add extra reserved layers
2. bluetooth connectivity issues fixed by changing 2phy to 1phy in zmk code experimental
3. soft off added for boards with hardware reset keys and bootloader key for the both split boards
4. enabled use during boot and bios if using usb cable
5. nkro support added
6. added easy rgb options using encoder for brightness and knob for color changes and speed, please see the keymap for details, all zmk options available
7. added custom status screen and different image screen to use as combo
8. fixed issue with using nice gem module incompatibility
9. added a duplicate custom layer to allow for a quick toggle to a second layout, currently hands down
10. symmetrical layers and shortcuts added in line with miryoku layout but without the home row mod due to extra keys on this board
11. symmetrical layer for numpad added for right handed mousing and left handed numpad use
12. keymap editor and zmk studio functionality and compatibility fixed for simultaneous use

>if you need bluetooth functionality for use within zmk studio, please turn off 1phy support in config, currently you can only edit in zmk studio offline application if you connect using a cable
>zmk toggle layer needs a second press of the toggle key to turn off the layer unlike via where you can switch directly to different layers even if toggled
>


# Sofle Keymap


<img src="keymap-drawer/eyelash_sofle.svg" >
