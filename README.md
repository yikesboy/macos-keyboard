# custom macos keyboard (de)

my custom keyboard layout to follow DIN 2137-01 and make macos atleast somewhat useable

<div align="center">
  <img src="https://github.com/user-attachments/assets/8abeacb2-da6f-4fef-8c23-a88bb2e4d50b" width="400">
</div>

## install
```
git clone https://github.com/yikesboy/macos-keyboard.git
cd macos-keyboard
mv linux-de.keylayout ~/Library/Keyboard\ Layouts/
```
```
open system settings -> keyboard -> input sources 
+ -> others -> add the keyboard (linux-de.keylayout)
```
*note: cmd and ctrl aren't changed, vim motions in the text-editors are sufficent for my usecases. i don't want to interfere with application shortcuts which are dependent on cmd*
