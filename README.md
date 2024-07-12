<h1 align="center">Groove-Coaster Printable-Shell by Rigo Howard</h1>
<h3 align="center">A nice 3D printable frame/shell for a DIY Groove Coaster controller</h3>

<h3 align="left">Overview:</h3>
<p align="left">
Here you will find the needed 3D print files and directions to build a nice looking Groove Coaster shell and get your own DIY-ASC controller!</p>
<p align="center"><img align="center" src="https://github.com/RigoHoward/groove-coaster-printable-shell/blob/main/render.png" alt="Groove Coaster Controller" /></p>

<h3 align="left">Finished Controller Sample:</h3>
<p align="left">
Some glamour shots</p>
<p align="center"><img align="center" src="https://github.com/RigoHoward/groove-coaster-printable-shell/blob/main/Pictures/GC1.jpg" alt="Groove Coaster Controller" /></p>
<p align="center"><img align="center" src="https://github.com/RigoHoward/groove-coaster-printable-shell/blob/main/Pictures/GC2.jpg" alt="Groove Coaster Controller" /></p>
<p align="center"><img align="center" src="https://github.com/RigoHoward/groove-coaster-printable-shell/blob/main/Pictures/GC3.jpg" alt="Groove Coaster Controller" /></p>

<h3 align="left">Extra parts/tools needed:</h3>
<p align="left">
Apart from the 3D printed parts you will need the following tools and materials (there are some Aliexpress links as reference):
  <ul>
  <li>1x Arduino Leonardo or clone board.</li>
  <li><a href="https://www.aliexpress.com/item/1005006560397920.html?spm=a2g0o.cart.0.0.67ac38daT6iGZ6&mp=1">2x Arcade sticks (Sanwa JLF like clones are good, there are 5 pin header and microswitch versions)</a></li>
  <li><a href="https://www.aliexpress.com/item/4000959586079.html?spm=a2g0o.cart.0.0.67ac38daT6iGZ6&mp=1">2x Round 60mm white pushbuttons.</a></li>
  <li><a href="https://www.aliexpress.com/item/33057798976.html?spm=a2g0o.cart.0.0.67ac38daT6iGZ6&mp=1">1x 33x33mm square white pushbutton.</a></li>
  <li>Some female quick disconnects to easily connect/disconnect wires to the sticks and pushbuttons.</li>
  <li><a href="https://www.aliexpress.com/item/1005002669156285.html?spm=a2g0o.cart.0.0.46e638da38WDFw&mp=1">2x Small round white momentary pushbuttons.</a></li>
  <li><a href="https://www.aliexpress.com/item/1005003082350902.html?spm=a2g0o.cart.0.0.67ac38daT6iGZ6&mp=1">2x Soft microswitches for the Left and Right pushbuttons.</a></li>    
  <li><a href="https://www.aliexpress.com/item/1005003307588072.html?spm=a2g0o.cart.0.0.389a38daMdQKNv&mp=1">1x Neutrik like female USB C to Female USB A panel connector.</a></li>
  <li>A few M5 bolts and nuts.</li>
  <li>A few M3 bolts.</li>  
  <li>Some M3 heat inserts.</li>
  <li>4x Rubber feet.</li>
  <li>1 meter of WS2812 ledstrip.</li>
  <li>1x short USB micro to USB-A wire to connect Arduino Leonardo to the USB-C panel connector.</li>
  <li>Solder, Flux and Soldering Iron (and basic soldering skills)</li>
  <li>Some wire cutter and a crimping tool for the quick disconnects.</li>      
  <li>Some shrink tube for cable joints.</li>  
  <li>About 3 meters of 24awg cable.</li>
  <li>Male dupont cables.</li>  
  <li>2x 5mm leds (colors of your preference)</li>  
  </ul>
</p>

<h3 align="left">Parts to print:</h3>
<p align="left">
  <ul>
  <li>1x Left, Center and Right frame.</li>
  <li>1x Bottom Left, Center and Right plate (you could use an accent color for this)</li>
  <li>2x Frame Spacer (you should use an accent color for this)</li>
  <li>1x Left, Right, Logo and Front plates.</li>  
  <li>1x each file on INSERTS folder (you should use an accent color for this)</li>
  <li>2x Joy Base, Joy Tube, Joy Button and Stick Spacer parts.</li>
  </ul>
</p>

<h3 align="left">Printing settings:</h3>
<p align="left">I used the following parameters on my slicer profile:
 <ul>
   <li>Layer Height 0.2 (i use a 0.4mm nozzle)</li>
   <li>3 or 4 walls/perimeters.</li>
   <li>15-20% infill is enough.</li>
   <li>Enabled normal supports on build plate only for Joy Tube and Joy Button parts.</li>
   <li>You really should use a brim or mouse ear brim for the Frame Parts (because they are big and take a long time to print)</li>
 </ul>  
</p>

<h3 align="left">Printing orientation:</h3>
<p align="left">All the Plate parts having some logo/letters engraved on them, must face up its engraving marks.
  For the rest, Please check the <a href="https://github.com/RigoHoward/groove-coaster-printable-shell/tree/main/Print_Orientation">Print_Orientarion</a> folder for pictured details.
</p>

<h3 align="left">Assembly:</h3>
<p align="left">
    <ul>
    <li>Attach the Insert parts to the Left, Center, Right Frame, the Logo Plate, Front Left and Right plates using some CA glue or whatever you use to glue your 3D printed parts.</li>      
    <li>Attach the USB-C panel to the back of the Center Frame and attach it using some M3 screws nuts and bolts. Also screw in the two small round white momentary pushbuttons and fix them with its own washer and nuts.</li>   
    <li>Using 4 M5 screws, washer and nuts put together the Left, Center and Right Frame parts using the 3D printed Frame Spacers between them to build the body of the controller.</li> 
    <li>Put 4 heated M3 inserts on the tiny holes on the top of the Center Frame to screw in the Logo plate later.</li>     
    <li>Using 4 M3 screws attach the Logo plate on top of the center Frame. Also with some M3 screws, washers and nuts fix the Front Left and Right Plate to the front of the Left and Right Frame parts.</li>      
    <li>Attach every JLF like joystick to the Stick Spacer part using two M5 screws on each Spacer.</li>    
    <li>Solder the corrresponding 3 wires (DIN, GND and VIN) to each piece of the ledstrip, then remove the back layer of the ledstrip to expose the sticky surface, and then pass the cables trough the hole in the inner wall of the Joy Base part and slide your ledstrip to glue it in place (leds should be facing outwards) repeat for the other Joy Base part.</li> 
    <li>Assemble the printed Joy Tube parts on the JLF like arcade sticks shafts using two M4 button head screws (do not overtight the screws)</li>  
    <li>Using 4 M5 screws, washer and nuts put together the Joy Base over the Left and Right Frame parts using the corresponding guide holes.</li>
    <li>Change the default microswitch on the 60mm buttons if you got the lighter ones before the next step.</li>      
    <li>Assemble the 60mm buttons on the Joy Button part, and solder the wires to the microswitch and leds.</li>
    <li>Assemble the Joy Button and the Joy Tube parts together routing the cables and twisting the recessed part into its lock position and then add a M3 screw to avoid unlocking.</li>
    <li>Solder each wire to the microswitchs or th 5 pin header (depending on what version you got) on each JLF like joystick.</li>
    <li>Solder the Center frame back momentary pushbuttons and the PLUS button LED to the corresponding pins in the Arduino Board (check the pinout section below)</li>
    <li>Put the heated M3 inserts on all the holes for the supporting Plate tabs for every Frame part at the bottom.</li>      
    <li>Assemble the Bottom Plates of each part of the frame using M3 screws and for each of the outer most sides use some rubber feet, confirm everything works before tightening up.</li>
  </ul>

</p>

<h3 align="left">Soldering:</h3>
<p align="left">
  <ul>
    <li>Solder a daisy chained GND wire to all leds, joysticks, buttons and ledstrips.</li>
    <li>Solder pins 4, 5, 6, 7, 8, 9, 10 and 11 to the left and right joysticks.</li>
    <li>Solder pins 0 and 1 to Left and Right buttons.</li>
    <li>Solder pins A0, A1 and 13 to the Minus, Home and Plus buttons.</li>
    <li>Solder pins 2, 3 and 12 to the Left, Right and Plus led buttons.</li>
    <li>Solder a daisy chained VCC wire to the VIN point on each piece of the ledstrip.</li>
    <li>Solder pins A2 and A3 to the DIN point on the Left and Right ledstrip piece.</li>
  </ul>
</p>

<h3 align="left">Flashing the Code:</h3>
<p align="left">
Follow the building instructions for the awesome <a href="https://github.com/CrazyRedMachine/LUFAHybridFightstick?tab=readme-ov-file#building-instructions">LUFAHybridFightstick</a> repository made by <b>CrazyRedMachine</b> until the fifth step and then flash the code i leave <a href="https://github.com/RigoHoward/groove-coaster-printable-shell/tree/main/Software/GC_RH">HERE</a> (which its actually his code with a different pinout and a rainbow animation effect for the ledstrip only)
</p>

<h3 align="left">Current Pinout:</h3>
<p align="left">
Here it is the pinout i used for each stick, button, led and ledstrip.
</p>

```
/* PINOUT (follows Nintendo naming (X=up, B=down)) */
#define PIN_UP    4
#define PIN_DOWN  5
#define PIN_LEFT  6
#define PIN_RIGHT 7
#define PIN_A     11          //XBOX B
#define PIN_B     9           //XBOX A  
#define PIN_X     8           //XBOX Y
#define PIN_Y     10          //XBOX X     
#define PIN_L     0           //XBOX LB
#define PIN_R     1           //XBOX RB
#define PIN_PLUS  13          //XBOX START
#define PIN_MINUS A0          //XBOX BACK
#define PIN_HOME  A1
#define PIN_L_LED  2
#define PIN_R_LED  3
#define PIN_PLUS_LED 12
#define DATA_PIN1 A2         //ledstrip Left
#define DATA_PIN2 A3         //ledstrip Right
```

<h3 align="left">Thanks to:</h3>
<p align="left">All the work done here was possible with the help of these awesome fellows:
<ul>
  <li><a href="https://github.com/CrazyRedMachine">CrazyRedMachine</a>: for the LufaHybridStick code and constant help on coding.</li>
  <li><a href="https://github.com/paatchii">Patchii</a>: for the initial STL files i used as reference to work on my remixed parts.</li>
  <li>Thomas (from C&S discord): for his modular 3D cases for rythm controllers inspiration.</li>
  <li>All the Cons & Stuff discord community for being so cool and nice.</li>
</ul>
</p>

<h3 align="left">Do you think i do cool stuff?, what about a nice cup of coffee for me?!:</h3>
<p><a href="https://www.buymeacoffee.com/rigohoward"> <img align="left" src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="rigohoward" /></a></p><br><br>
