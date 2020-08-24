This product was featured on the [Tindie Blog](https://blog.tindie.com/2020/07/game-boy-advance-sp-usb-c-charging-port/)!

[![PCB](https://github.com/rorosaurus/gba-sp-usb-c/blob/master/images/pcb-front.jpg)](https://www.tindie.com/products/20612/)

[![Final result](https://github.com/rorosaurus/gba-sp-usb-c/blob/master/images/completed-test.jpg)](https://www.tindie.com/products/20612/)

# [Buy on Tindie](https://www.tindie.com/products/20612/)! [![I sell on Tindie](https://github.com/rorosaurus/esp32-hub75-driver/raw/master/images/tindie.png)](https://www.tindie.com/stores/rorosaurus/)

## The truly universal USB-C dream is finally realized for your Game Boy Advance SP!

*(Also compatible with the original Nintendo DS!)*

Charge your Game Boy Advance SP with USB-C, using any USB-C cable and charger! If it fits, it'll charge! Finally you can stop carrying around that extra proprietary cable!

My design is based off [this existing PCB](https://oshpark.com/shared_projects/I6UOH6gb) that only works with ````USB-A -> USB-C```` cables. In my opinion, if you're gonna future-proof your Game Boy, you shouldn't remain reliant on Type-A!

My PCB works with ````USB-C <-> USB-C```` cables as well, so you can use ANY USB-C cable/charger to charge it! I've also verified it works with ````USB-A -> USB-C```` cables, Quick Charge, and USB-PD! That means if your charger or USB battery pack offers 5V/9V/12V/etc., it will recognize the Game Boy can only accept 5V and charge accordingly.

# Options

* **Unassembled (PARTS ONLY)**: You recieve all the necessary parts: PCB, Type-C female connector, and two 5.1K SMD 0402 resistors. You will assemble it yourself using a steady, experienced hand and fine tip soldering iron. The resistors are VERY tiny (SMD 0402) so keep a close eye on them! I recommend using fine tweezers to position them easily.

* **Assembled**: I will assemble the components for you before shipping. You only have to desolder the exisiting charging port, then solder 3 points to attach to your Game Boy!

* **3D printed bezel**: I will include a small 3D printed part to fill in the gap in the case created by the smaller USB-C port. It will friciton-fit snugly, or you can use glue/epoxy to keep it in place. Some post-processing (sanding) might be necessary for the cleanest look. Alternatively, you can 3D print [the part](https://www.thingiverse.com/thing:4123563) yourself, or skip this optional cosmetic mod.

# Compatibility

I have tested this design on my AGS-001. Based on the AGS-101 pictures I've seen online, and talking with AGS-101 owners, I expect this to work for AGS-101 with zero issues.

This design is compatible with [3.5mm headphone jack mods](https://github.com/rorosaurus/gba-sp-headphone-jack)! That means my PCB will not block the other pins you need from the default charging port pads on the Game Boy's motherboard.

This design is also tested and confirmed working on the original (fat) Nintendo DS, NTR-001. Now your Phat GBA Macro can use USB-C as well! I'm working on a modified design I think will work for the DS Lite, so stay tuned!

# Disclaimer

Modify your console at your own risk! This product is provided "as is", with no warranty - express or implied. That said, if you have any issues or questions, don't hesitate to reach out!

# Installation

Note: your PCB might arrive with some [slight perforations, from the breakaway panelization design](https://github.com/rorosaurus/gba-sp-usb-c/blob/master/images/breakaway-perforations.jpg) during PCB manufacturing. These can be left alone, or optionally filed/sanded away. You probably want to file the top side flat, if you also intend to perform a 3.5mm headphone jack mod.

## - Test before you install!
I test every board before shipping, but you should be certain it still works before you install it! Plug it in to a ````Type-C <-> Type-C```` cable and USB-C power source. **Do not perform this test with a ````Type-A -> Type-C```` cable - that cable won't verify the board works for full USB-C!** Use a multimeter to measure the voltage across any of the grounded holes and the +5V half-circle in the back. Ensure it reads ~5V. Flip your USB-C cable the other way around and verify it still reads 5V! Alternatively, if you have a USB-C multimeter [like this](https://smile.amazon.com/gp/product/B07X3HST7V/) you can simply plug into that and read the display.

## - Installation Video
I highly recommend you watch [makho's video](https://www.youtube.com/watch?v=gBLHvdre-Xg) of installing a similar version of this PCB! This is an *awesome* overview that will be very helpful to reference. The below instructions simply outline what he does in the video.

## - Instructions
1. Carefully desolder and remove existing charging port. Use a solder sucker and solder wick. Take your time and take great care to not get impatient and rip up any pads!
2. Fill in the standoffs on both PCB's (Game Boy and my PCB) with solder.
3. Ensure bottom of USB-C PCB is flat, as well as the top of the Game Boy motherboard. You can use flush cutters and solder wick to help you with this. You might need to gently and carefuly sand the bottom through-hole connections for the USB-C port to ensure they are fully flat.
4. Align the USB-C PCB so that the standoffs are directly above the Game Boy's and solder one joint.
5. Reheat the joint and realign as necessary to ensure the standoffs are aligned properly, and the 5V power line aligns well with the pad it will connect to.
6. Solder the remaining standoff to lock the USB-C PCB in place. Test the strength of this connection and reinforce if necessary. Remember it needs to support the stress of plugging in and pulling out many times!
7. Solder the 5V half circle pad to the 5V pad on the Game Boy motherbaord.
8. Plug in USB-C cable to test! Hooray!

# Thanks
Thank you to [makho](https://www.youtube.com/channel/UC5FYpo9lFqK1Y7wqjPuANFw) and [BlindEye/Hidarite](https://www.tindie.com/stores/hidarite/) for the original PCB design, video, and STL file!