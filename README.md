# LiquidDispenser
Automatic Liquid Dispenser

In this project, I'm trying to make an Automatic Liquid Dispenser using:

 - An arduino IR Sensor
 - A Water Pump motor
 - A BD140 Transistor
 - A 1K Ohm Resistor

The elctronics is basic and is just a quick soldering which are shown in the pictures.

The main reason of this project is to perform my skills in 3D modelling.
Therefore, using Fusion 360, I made the shell of the Liquid Dispenser which will be 3D  Printed just after.

To make the Liquid Dispenser :

First make the electronic connection as shown in the pictures in the Electronics folder.

  - Follow the elctronics schematic provided in the folder.
    - Connect the BD140 Transistor Emitter pin to the VCC pin of the Sensor
    - Then add some heat shrink tubbing before connecting the Ground pin of the Sensor to the Ground wire of the water pump
    - Connect the positive wire of the water pump to the BD140 Transistor Base pin 
    - Finally Connect the 1K Ohm Resistor to the OUT pin of the Sensor and to the BD140 Transistor Collector pin
  - Finally cover everything with heat shrink tubbing added ealrier by heating it.

Then print the 3D Files which are located in the 3D Files folder.

  - Print the Liquid Recipient first by uploading the .obj or .stl files in Cura.
  The Printing settings are specified in the Picture provided in the 3D Files folder

Finally assemble.

