# LiquidDispenser
Automatic Liquid Dispenser

In this project, I'm trying to make an Automatic Liquid Dispenser using:

 - An arduino IR Sensor
 - A Water Pump motor
 - A BD140 Transistor
 - A 1K Ohm Resistor
 - A 2 x AA Battery holder

The elctronics is basic and is just a quick soldering which are shown in the pictures.
There is no programming needed.

The main reason of this project is to perform my skills in 3D modelling.
Therefore, using Fusion 360, I made the shell of the Liquid Dispenser which will be 3D  Printed just after.

To make the Liquid Dispenser :

First make the electronic connection as shown in the pictures in the Electronics folder.

  - Follow the elctronics schematic provided in the folder.
    - Connect the BD140 Transistor Emitter pin to the VCC pin of the Sensor
    - Then add some heat shrink tubbing before connecting the Ground pin of the Sensor to the Ground wire of the water pump
    - Connect the positive wire of the water pump to the BD140 Transistor Base pin 
    - Connect the 1K Ohm Resistor to the OUT pin of the Sensor and to the BD140 Transistor Collector pin
    - Finally connect the Ground of the battery holder to the Ground pin of the Sensor and the positive wire of the battery holder to the VCC pin of the sensor.
  - Finally cover everything with heat shrink tubbing added ealrier by heating it.

Then print the 3D Files which are located in the 3D Files folder.

If you have a battery holder skip these 2 steps.
  - If you don't have battery holder, you can make one easily by printing first the Battery Holder by uploading it's file in Cura.
  - Add in some wires as shown in the pictures in the electronics folder, and your battery holder is done.
  
  - Print the Liquid Recipient first by uploading the .obj or .stl files in Cura.
  The Printing settings are specified in the Picture provided in the 3D Files folder

Finally assemble.

