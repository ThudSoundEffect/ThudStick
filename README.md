# ThudStick
Fightstick with fully analog joystick functions as a gamecube controller utilizing a PHOB v2.02 motherboard, a c-pad daughterboard, and a custom designed PCB to host the hall effect sensors to fit a Sanwa-JLF joystick. 
### Features
- Full analog joystick
- Digital face buttons (A,B,X,Y,Z)
- Digital C-Stick
- Digital hard shield and light shield buttons
- Powered by a PHOB v2.02 motherboard
- Utilizes a C-Pad (https://github.com/rana-sylvatica/c-pad/tree/main)
- Housing and PCB for the Sanwa Joystick adapted from the Sharp Analog Snap-In (https://github.com/Sharp-02/JLF-Sharp-Analog-Snap-In/tree/main) to connect the hall effect sensors directly to the PHOB motherboard rather than using a PCB that requires the additional soldering and calibrations of resistors, op-amps, and trimpots to be compatible with an OEM board
- Custom layout files for laser cut acrylic face plates
# Assembly
### Parts
- x1 PHOB v2.02 motherboard without hall effect sensors
- x1 C-Pad by Rana Labs for PHOB v2.X
- x4 12mm M3 screws
- x12 24mm Sanwa snap-in buttons (https://arcadeshock.com/products/sanwa-denshi-pushbutton-24mm-solid-color-obsf-24-xx?_pos=1&_sid=41db96e1b&_ss=r)
- x1 Sanwa JLF joysick (https://www.amazon.com/dp/B01CRQMWEQ?ref=ppx_yo2ov_dt_b_product_details&th=1)
- x1 Gamecube controller cord (https://www.ebay.com/itm/256017929306)
- x12 quick connect cable sets (https://www.amazon.com/dp/B092CW94LK?psc=1&ref=ppx_yo2ov_dt_b_product_details)
- x1 Acrylic face plate
- x1 Acrylic support plate
- x1 Set of 3D printed joystick parts
- x2 Hall effect sensors (https://www.digikey.com/en/products/detail/texas-instruments/DRV5053EAQLPG/5051704)
- x1 Enclosure (https://www.mouser.com/ProductDetail/546-144126BK3)
### Purchasing
Use JLCPCB to purchase PHOB board follow the parts ordering guide from the PHOB gcc github for ordering the boards just make sure to check hall effect sensors off when reviewing the components for assembly. Use JLCPCB to order the C-Pad following the instructions from the C-Pad github from Rana Labs for the board for a PHOB v2 board. 
### Joystick Modification
- Refer to steps 2 and 3 from https://github.com/Sharp-02/JLF-Sharp-Analog-Snap-In#step-2--restrictor-gate-and-trimming
- take the original joystick motherboard and desolder all 4 switches
- open up each of the swithes
- trim the switch housing up to the point where the mechanical pieces begin on the left side (when the red piece is facing you)
- ![image](https://github.com/ThudSoundEffect/ThudStick/assets/130328484/ede32668-bd27-45a6-ac74-9414aacf82cf)

- To properly attach the magnets place them in the slider arms so that when they are held by the linear guide they are on the same side
- Take the joystick motherboard and place the hall effect sensors in the labeled ports so that the smaller face of the sensor is pointing away from the center of the board
- Solder in the hall effect sensors and trim the excess sensor legs and solder on the bottom of the pcb
- connect wires into each of available spots on the outside of the board
- connect the wires to the corresponding spots as marked on the back of the PHOB motherboard for the X, Y, both 5V, and both grounds where hall effect sensors could be directly soldered to the PHOB motherboard.
- put the joystick pcb in its 3d printed holder
- Place the slider arms in the linear guide so that the magnets move in front of the hall effect sensors when the linear guide is screwed in
- Use 20mm
### PCB
- Tin all of the solder pads on the PHOB for the face buttons (A, X, B, Y, Start)
- Prepare the quick connect wires by cutting them to length and stripping the end
- Tin your soldering iron a pair of quick connect wires to each of the face buttons
- Use the available through holes to solder quick connect wires to the C-Pad and the L, R, and Z buttons(either at the top of the controller or on the side next to the holes for the R digital signal
- Solder quick connect cables into a C-pad board (make sure to order the board without any buttons installed)
- Connect the C-pad board to the PHOB board
- Install the PHOB firmware to the board as you would a regular phob
- 
### Final Assembly
- 

  

