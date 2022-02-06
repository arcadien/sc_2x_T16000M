# Double T16000M configuration for Star Citizen

Based on the work of  BuzZzKiller [here](https://www.youtube.com/watch?v=pqmb0Zp-S2E), you will find in this repository:
* one configuration file for [T.A.R.G.E.T](https://support.thrustmaster.com/fr/product/t16000mfcs-fr/). This file named `double-t16000m.tmc` will allow to:
  * keep joystick configuration across reboot and USB port switch
  * create macros
  * map josytick button on keyboard shortcut _or_ Directx buttons

<br />

* One mapping for Star Citizen, using mappings from thr T.A.R.G.E.T script above. The mapping file, `layout_2xT16k-G25.xml`, has to be copied in `C:\Program Files\Roberts Space Industries\StarCitizen\LIVE\USER\Client\0\Controls\Mappings`. To use the mapping in game, it has to be configured, once. In game, open the game console (`²`) and type the following command: 
`pp_rebindkeys layout_2xT16k-G25.xml`. I used [SCJMapper](https://github.com/SCToolsfactory/SCJMapper-V2) to know available mappings.

I also use Logitech [G25 pedals](https://i.pinimg.com/originals/99/03/99/99039982060964b3628512aaf9572f65.jpg) to control mining laser power, backward and forward speed. That's why "G25" appears in the layout file name.

Used together, these two files provides the following mapping:

![T16kmapping](https://github.com/arcadien/sc_2x_T16000M/blob/main/Dual%20T16000%20mapping.png)
