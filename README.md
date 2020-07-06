# dvorak-programmer-dpfr
US Dvorak programmer keyboard layout with french accents and few grec letters

This is the usual **Dvorak for Programmers** keyboard layout (initially made by Ronald Kaufmann), first upgraded by Dmitry Prokashev to include West-European characters, but then heavily updated to:
- make french accents easier. main symbol can directly typed using altgr key (level 3)
- make few grec symbols available using altgr key
- artgr - is now a dead key to add ¨ symbol on letter (ie: ö, ë, ï)
- altgr ^, altgr ' and altgr `  can still be used to make symbols like á, í, î, etc ...

keys:
=====
Here is how to get main french accents. Add shift key for uppercase
- ralt e => é
- ralt a => à 
- ralt c => ç
- ralt o => ô
- ralt u => û
- ralt j => è
- ralt q => œ 
- ralt k => ü
- Others letters with ^ or ¨ can be written by using ralt ^ or ralt - 
- few grecs letter added. (for π, use ralt p)

Installation:
=============

If you use sway windows manager, you can copy this file in ~/.xkb/symbols/us-dpfr and put in your sway config file  xkb_layout us-dpfr.
For example:

```java
input "7764:8240:TypeMatrix.com_USB_Keyboard" {
    xkb_model tm2030USB
    xkb_layout us-dpfr
    xkb_options lv3:ralt_switch_multikey
}
```
