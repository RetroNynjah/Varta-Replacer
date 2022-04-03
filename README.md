# Varta Replacer

<img src="rev 1\images\bottom_illustration.png" alt="Bottom illustration" width="300"/><br/>

This simple circuit enables use of a coin-cell battery in place of a dangerous leaky Varta battery in your favorite vintage computer. 
This kind of device has many names but is often called Varta Replace. Varta Killer or similar because Varta rechargable batteries were common in many old computers including many of the Commodore Amiga computers. Those old Varta batteries are famous for leaking with severe corrosion as a result.

<img src="rev 1\images\photo_top.jpg" alt="Photo top" width="300"/><img src="rev 1\images\photo_bottom.jpg" alt="Photo bottom" width="300"/><br/>

## Mounting footprint
This is the footprint of the mounting pins. Make sure that they match your installation well enough.  
The mounting pins can be bent a bit to fit other footprints if they are close enough.

<img src="rev 1\images\bottom_measures.png" alt="Mounting footprint"/><br/>

## Soldering
Start by soldering all components on the bottom side. Add whatever mounting pins you need for your installation. If you don't know what you will use the bord for you should install all four pins and trim off the ones you don't need when installing the board.
You normally want to use the current limiting resistor R1 so always include the resistor in your build. If you must skip the resistor later for some reason you can bypass the resistor using solder jumper SJ1.

## BOM
|Pcs|Identifier |Part                 |Value       |Comments                         |
|---|----------	|----------	          |-----       |-----							               |
|1  |R1         |Resistor             |220 Ohm     |                                 |
|1  |D1         |Rectifier diode      |1N4148      |                                 |
|1  |BT1        |Battery holder       |CR2032      |20 mm pitch                      |
|4  |           |Mounting pins        |            |Regular pin headers 4 single pins| 
