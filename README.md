# Belgian azerty macbook keyboard layout file for external Windows keyboards
Mac .keylayout file with Belgian azerty layout.

I created this for my own personal need, to have a proper Belgian azerty keyboard layout on a Macbook 
that matches with the labels on a usb connected Corsair K70 mechanical BE-azerty keyboard.

It will match most of the external Windows keyboards with Belgian azerty layout though.
- Windows key acts as Command Key
- AltGr key acts as Option key

### Example picture of usb-keyboard with BE-azerty layout
![belgiankeyboard.jpg](Mac_keyboard_layouts/belgiankeyboard.jpg)
## How to use
1. Copy .keylayout file from Github to your Mac
   - copy corsairk70_azertyBE.keylayout file from Mac_keyboard_layouts folder to "/Library/Keyboard Layouts/" on your Mac
   - logout or reboot
   - login again
2. Select keyboard layout
   - open "Apple icon" on the top left-> "System settings" -> "Keyboard"
   - click "Input sources" -> "Edit"
   - click "+"
   - choose "Others" -> "BEazertyWinKeyboard"
   - click "Add"

![select input source](Mac_keyboard_layouts/screenshot1.png)
- From now you can switch keyboard to "BEazertyWinKeyboard" from the right top bar.

![select keyboard](Mac_keyboard_layouts/screenshot2.png)

## Tooling used
The keyboard layout is made with [Ukele](https://software.sil.org/ukelele/)
## Inspired by
https://github.com/roelandmoors/azerty
