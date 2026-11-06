# Lamp SAOs
A few lamp-related SAOs. 

## HPL Lamp SAO

### Build Notes
- Requires 2x 28mm LED filaments and 2x ??mm 0.8mm dia. "jewelery wire" (tinned copper? not sure)
- Bend the longer wire so that it has a ?-shape on top and a very slight jog to the left (front view) towards the bottom
- Using the smaller jig, solder the non-hole side to the ? shape to form the filament assembly
- Using the larger jig, solder to SAO
- Bend another wire that makes a complicated shape. It's hard to explain in words. Solder this to the SAO. 
- Solder the other end to the bottom of the filaments. MAKE SURE THE TWO WIRES AREN'T BRIDGED. 

### Changelog
**V0 -> V1**
- Flip NPN footprints to be correct
- Reduce R5 to 30ohm
- Thermal relief on GND wire pad
- Replace 2N3904 with dual 3904 package
- Be a bit less hacky with the external PWM buffer
- Replace 555 diodes with a dual diode package

## C9 Lamp SAO
A SAO based on a C9 holiday lamp. 

### Build Notes
- Requires 2x 28mm LED filaments and 1x 28mm 0.8mm dia. "jewelery wire" (tinned copper? not sure)
- Using the C9 jig, solder the two filaments and the wire to the PCB
    - The hole-side of the filament should be on the top of the SAO, and the side of the filament that has a white rectangle peeking through should be on the back side of the SAO
    - For white filaments, the side that looks more orange should be facing the front of the SAO
- Remove from jig, and then solder the tops of the filaments to the wire on the front side
    - May need to bend the wire forward a bit to be coplanar with the filament leads
- Trim top of wire

### Changelog
- Schematics the same as HPL v1
