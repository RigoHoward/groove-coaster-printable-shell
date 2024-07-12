<h1 align="center">Groove-Coaster Printable-Shell by Rigo Howard</h1>
<h3 align="center">A nice 3d printable frame/shell for a DIY Groove Coaster controller</h3>

<h3 align="left">Overview:</h3>
<p align="left">
Here you will find the needed 3d print files and directions to build a nice looking Groove Coaster shell to build your own DIY-ASC controller!</p>
<p align="center"><img align="center" src="https://github.com/RigoHoward/groove-coaster-printable-shell/blob/main/render.png" alt="Groove Coaster Controller" /></p>

<h3 align="left">Finished Controller Sample:</h3>
<p align="left">
Glamour shots</p>
<p align="center"><img align="center" src="https://github.com/RigoHoward/groove-coaster-printable-shell/blob/main/GC1.png" alt="Groove Coaster Controller" /></p>
<p align="center"><img align="center" src="https://github.com/RigoHoward/groove-coaster-printable-shell/blob/main/GC2.png" alt="Groove Coaster Controller" /></p>
<p align="center"><img align="center" src="https://github.com/RigoHoward/groove-coaster-printable-shell/blob/main/GC3.png" alt="Groove Coaster Controller" /></p>

<h3 align="left">Extra parts needed:</h3>
<p align="left">
Apart from the 3d printed parts you will need the following tools and materials (i will add some Aliexpress links):
  <ul>
  <li>1x Arduino Leonardo or clone board.</li>
  <li>2x Arcade sticks (Sanwa JLF clones are good)</li>
  <li>2x Round 60mm white pushbuttons.</li>
  <li>1x 33x33mm square white pushbutton.</li>
  <li>Some QD's to easily connect/disconnect to the arcade stick and pushbuttons.</li>
  <li>2x Small round white pushbuttons.</li>
  <li>2x Soft push microswitches for the Left and Right pushbuttons.</li>    
  <li>1x Neutrik like female USB C to Female USB A panel plug.</li>
  <li>A few M5 bolts and nuts.</li>
  <li>A few M3 bolts.</li>  
  <li>Some M3 heat inserts.</li>
  <li>4x Rubber feet.</li>
  <li>1m of WS2812 ledstrip.</li>
  <li>Solder, Flux and Soldering Iron (and basic soldering skills)</li>
  <li>Some shrink tube for cable joints</li>  
  <li>24awg cable.</li>
  <li>Male dupont cables.</li>  
  <li>2x 5mm leds (color of your preference)</li>  
  </ul>
</p>

<h3 align="left">Parts to print:</h3>
<p align="left">
  <ul>
  <li>1x Left, Center and Right frame.</li>
  <li>1x Bottom Left, Center and Right plate (you could use an accent color for this)</li>
  <li>2x Frame Spacer (you should use an accent color for this)</li>
  <li>1x Left and Right Front plates.</li>  
  <li>1x Logo Plate plates.</li> 
  <li>1x each file on INSERTS folder (you should use an accent color for this)</li>
  <li>2x Joy Tube, Joy Button and Stick Spacer parts.</li>
  <li>2x Joy Base.</li>
  </ul>
</p>

<h3 align="left">Assembly:</h3>
<p align="left">
    <ul>
    <li>Attach the Insert parts to the Left, Center, Right Frame. to the Logo, Front Left and Right plates using some CA glue.</li>      
    <li>Attach the USB c panel plug to the Center Frame and attach it using M3 screws nuts and bolts. Also screw in the 2 small round white buttons and fix them with the washer and its own nuts.</li>   
    <li>Using 4 M5 screws, bolts and nuts put together the Left, Center and Right Frame parts using the 3d printed Frame Spacers between them to build the body of the controller.</li> 
    <li>Attach every JLF like koystick to the Stick Spacer part using 2 M5 screws.</li>    
    <li>Solder the corrresponding 3 wires (DIN, GND and VCC) to each piece of the led strip, then remove the back paper to expose the sticky surface, and pass the cables trough the hole in the inner wall of the Joy Base part and repeat of the othe Joy Base part.</li> 
    <li>Assemble the printed joy_tube on the JLF like arcade sticks using 2 M4 button head screws (do not overtight the screws)</li>  
    <li>>Using 4 M5 screws, bolts and nuts put together the Joy Base with the Left and Righ Frame parts using the corresponding holes.</li>
    <li>Assemble the 60mm buttons on the Joy Button part, and solder the wires to the microswitch and leds.</li>
    <li>Assemble the Joy Button and the Joy tube parts together twisting the recessed part and then add a M3 screw to fix in place.</li>
    <li>Solder each wire to the microswitch on each JLF like joystick.</li>
    <li>Solder every button and LED to the corresponding pins on the Arduino Board (check the pinout section below)</li>
    <li>Assemble the Bottom Plates of each part of the frame using M3 screws and for each of the outer most sides use some rubber feet, connect and confirm everything works before tightening up.</li>
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
    <li>Solder a daisy chained VCC wire to the 5v point on each piece of the ledstrip.</li>
    <li>Solder pins A2 and A3 to the Left and Right ledstrip piece.</li>
  </ul>
</p>

<h3 align="left">Flashing Code:</h3>
<p align="left">
Follow the instructions for the awesome <a href="https://github.com/CrazyRedMachine/LUFAHybridFightstick?tab=readme-ov-file#building-instructions">LUFAHybridFightstick</a> repository made by <b>CrazyRedMachine</b> until the fifth step and then flash the code i leave here (which its actually his code with a different pinout and ledstrip animation effect only).
</p>

<h3 align="left">Current Pinout:</h3>
<p align="left">
Here it is the pinout i use for each stick, button and leds.
</p>
<code>/* PINOUT (follows Nintendo naming (X=up, B=down)) */
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
</code>

<h3 align="left">What about a nice cup of coffee for me?:</h3>
<p><a href="https://www.buymeacoffee.com/rigohoward"> <img align="left" src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="rigohoward" /></a></p><br><br>
