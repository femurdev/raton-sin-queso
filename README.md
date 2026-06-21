<img width="4032" height="3024" alt="IMG_4938 Background Removed" src="https://github.com/user-attachments/assets/e67c095b-4782-4173-b42b-1fa18bebe03b" />
[https://cad.onshape.com/documents/3eceed79fd8189f0e7238951](https://cad.onshape.com/documents/3eceed79fd8189f0e7238951)
# Ratón Sin Queso
*A mouse without cheese*
# Where is it
A mouse whose hardware was hand-picked to squeeze as much performance out of it as possible. It is not light and not cheap, but I’ve got forearms so that don’t matter. As of writing this, I have it working over a wired connection but plan to implement Bluetooth protocols in the coming days.
## Who is it
I’m Femurdev, a recent high school graduate who’s excited about all things electronics, code, and research.
## Why is it
Back at the end of the school year, my trusty mouse broke. Since then, I have repaired it, but got me wondering if I could build a mouse with top of the line hardware and also make my own pcbs for it. I wanted to see if I could create an ergonomic gaming mouse for people with larger hands.
## Specs
8 side buttons, 3 indicator led, LMB, RMB, standard TTC encoder and MMB switch. Uses an nRF52 module from Seeed Studio for usb and Bluetooth compatibility.

## Usage & construction guide
- Print the 3D models in the repo, one of each. I made mine of PLA.
- Order the parts listed in the BOM.
- Construct the pcbs as according to the BOM.
- Place all parts on the bottom chassis.
- Glue the buttons to the top of them. They should remain about 2.2 mm above the shell when glued. 
- The flexibility of the PLA provides the spring back effect.
- Make connections as described in the kicad files. Connect your in place pcbs via the screw terminals. 
- If you’re using a TTC encoder as recommended, solder these jumpers. 
