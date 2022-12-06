My custom ZMK config for the Almn40

---

_From the Almn40 Repo_

# ALMN40 Keyboard

Based on Polarity Works CRBN

![ALMN40 Keyboard](https://user-images.githubusercontent.com/7244488/187102496-6a5a9021-7ee4-4d41-9ac1-a0a9f1ebefd9.jpg)

### Default keymap

<img width="1011" alt="Screen Shot 2022-08-30 at 9 38 34 PM" src="https://user-images.githubusercontent.com/7244488/187573972-68675b9a-258e-49f9-91fb-f9536801a64f.png">
<img width="1011" alt="Screen Shot 2022-08-30 at 9 38 43 PM" src="https://user-images.githubusercontent.com/7244488/187573990-01ebc3bf-9586-4878-a5f1-a637f17f9220.png">
<img width="1008" alt="Screen Shot 2022-08-30 at 9 38 51 PM" src="https://user-images.githubusercontent.com/7244488/187573999-8b8d073f-ccaa-4f3b-99df-d0974dbec47a.png">
<img width="1010" alt="Screen Shot 2022-08-30 at 9 38 58 PM" src="https://user-images.githubusercontent.com/7244488/187574001-72c8ba75-f3f8-4259-95ee-3f83fc75b7be.png">

# Build Guide

**Important Notes**

- The top pin on the switch that goes above the USB-C port must be clipped because of the height tolerance!
- On V1 of the PCB, the bottom three diodes on the V1 PCB must be soldered on the underside of the PCB because of the height tolerance!

### Kit Contents

- 1x ALMN40 PCB
- 1x Bead Blasted Anodized Aluminum Case with rubber feet
- 1x Bead Blasted Stainless Steel Plate
- 1x Nice!Nano v2
- 2x 1x12 Header Pins
- 48x 1N4148 Diodes
- 1x 1500mAh Lithium Ion Battery
- 1x JST PH 1.25 Battery Cable
- 6x Stainless Steel Screws
- 1x 3M Battery Tape

### Parts Required

- 48x Switches
- 48x Keycaps
- Optional 1x EC11 / EC12 Rotary Encoder and Knob
- Optional 96x Mill-Max 3305 Hot Swap Sockets

### Tools Required

- Soldering Iron
- Cutters
- Philips Screwdriver
- Electrical Tape

![Parts](https://user-images.githubusercontent.com/7244488/187102521-add77e6e-206d-450e-b206-9b18f44b4a46.jpg)

## Soldering PCB

### 1. Optional - Mill-Max Hot Swap Sockets

Press Mill-Max Hot Swap Sockets tightly into each switch pin hole
![Sockets](https://user-images.githubusercontent.com/7244488/187102526-0fa0fe7f-e8fd-47b5-8a6b-5efd80657e84.jpg)

Tape the top of each row with electrical tape and solder the underside
![DSCF3901](https://user-images.githubusercontent.com/7244488/187102547-942bf670-26b6-4a11-a742-99c3cb39275c.jpg)

I am using Mill-Max 3305-0-15-80-47-27-10-0

### 2. Diodes

- **Ensure the polarity of the diodes is correct before soldering!**
- **On V1 of the PCB, the three bottom diodes must be soldered on the underside of the PCB, otherwise they will hit the switches!**

Bend the diode pins along the edge of the PCB
![Diodes](https://user-images.githubusercontent.com/7244488/187102600-065db567-5149-4f03-bdd2-d64e92c8ea30.jpg)

Insert diodes into PCB, then tape the top of each row with electrical tape, then clip the pins on the underside and solder.
![Diodes](https://user-images.githubusercontent.com/7244488/187102632-dc3f09f5-90d9-4323-9d6d-12fabc31f81f.jpg)

### 3. PCB Header Pins

- **Do not solder the Nice! Nano yet if you are not using hot swap sockets**
- **You must use 2.4mm-2.5mm tall headers or else the USB port won't line up with the case!**

Insert the header pins such that the shorter pins go into the PCB, and solder the header pins to the PCB. The Nice! Nano can be inserted and oriented so that the chip and logo are no longer visible for alignment, but DO NOT solder it yet, otherwise the switches will be blocked from soldering. You can optionally use Mill Max Ultra Low Profile hot swap sockets which are 2.4mm tall https://www.littlekeyboards.com/products/ultra-low-profile-sockets
![Headers](https://user-images.githubusercontent.com/7244488/187102887-9389d253-c4dc-4804-afdd-01a7777e58cc.jpg)

### 4. Optional - Rotary Encoder

Solder the Rotary Encoder and clip the pins

### 5. Switches and Plate

- **The switch pin directly above the USB-C port must be clipped!**

Clip one switch pin for the switch above the USB-C port, and insert the switches into the plate and PCB. Solder the switches if you are not using hot swap sockets.
![Switch](https://user-images.githubusercontent.com/7244488/187102925-4780b92d-b6ae-43fe-8960-e5e5593ae57d.jpg)

### 6. Battery Wires

- **The red wire goes on the positive (+) terminal!**
- **The wires should be inserted from the side where the chips are visible with the Nice! Nano logo!**

Solder the battery wires so that they can be tucked in between the Nice! Nano and the PCB later.
![Wires](https://user-images.githubusercontent.com/7244488/187102948-51552f37-a22c-4856-98b8-1b135192f6a7.jpg)

Solder the charge boost jumper with one of the cut diode pins on the Nice! Nano for batteries above 500mAh. The included battery is 1500mAh.
![Jumper](https://user-images.githubusercontent.com/7244488/187103229-0766e9b2-aa29-4a53-9fa8-3acc8143a2af.jpg)

### 7. Nice! Nano

- **The Nice! Nano must be oriented so that the chips with the Nice! Nano logo face inside toward the PCB! They should not be visible.**

Insert the Nice! Nano into the longer bottom header pins oriented so that the logo and chips are no longer visible and tuck in the battery wires in between the Nice! Nano and the PCB.
![Nice! Nano](https://user-images.githubusercontent.com/7244488/187103008-0b34dbe0-68cd-4e9c-9e3d-9220b9658601.jpg)

Clip the bottom pins so that they are flush with the Nice! Nano, then solder the header pins to the Nice! Nano.
![DSCF3952](https://user-images.githubusercontent.com/7244488/187103024-51cb4928-2204-4752-ac66-581ac5369d98.jpg)

### 8. Battery

- **Make sure the red wire plugs into the red wire!**

Knot the excess battery cable, and plug it in as shown.
![Battery](https://user-images.githubusercontent.com/7244488/187103062-96039a6e-e82f-46bf-88e3-96b60bfbe0b0.jpg)

The cables coming out of the controller should be taut against the end of the controller so that they don't hit the edge of the battery cavity in the case.
![Battery](https://user-images.githubusercontent.com/7244488/187103078-d0f9610d-079f-43b9-8bc9-28533ffb0dcd.jpg)

Tape the battery to the case.
![Battery](https://user-images.githubusercontent.com/7244488/187103096-464e790a-98db-429f-84de-cad24088f8a4.jpg)

### 9. Case

Drop the PCB into the case, ensuring that the battery wires are tucked neatly into the battery cavity, and the USB-C port on the Nice! Nano is aligned with the opening in the case. Assemble the case with screws.
![Case](https://user-images.githubusercontent.com/7244488/187103123-ef0161d5-52a6-48b5-8820-13ef42053544.jpg)

### 10. Keycaps

Add keycaps and enjoy your new ALMN40!
![Keycaps](https://user-images.githubusercontent.com/7244488/187103128-31e252ca-4ef6-44a9-bafe-59fc1ebf9e7e.jpg)

### References

- Customizing your keymap with ZMK https://zmk.dev/docs/user-setup
- Nice! Nano docs https://nicekeyboards.com/docs/nice-nano/getting-started

### Troubleshooting Connections

- Resetting and Pairing Bluetooth https://github.com/zmkfirmware/zmk/issues/278#issuecomment-898619280
- ZMK Connectivity Issues https://zmk.dev/docs/troubleshooting#connectivity-issues
- ZMK Discord https://discord.com/invite/sycytVQ
