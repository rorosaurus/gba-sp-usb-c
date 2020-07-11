This product was featured on the [Tindie Blog](https://blog.tindie.com/2020/07/game-boy-advance-sp-usb-c-charging-port/)!

[![PCB](https://github.com/rorosaurus/gba-sp-usb-c/blob/master/images/pcb-front.jpg)](https://www.tindie.com/products/20612/)

[![Final result](https://github.com/rorosaurus/gba-sp-usb-c/blob/master/images/completed-test.jpg)](https://www.tindie.com/products/20612/)

# [Buy on Tindie](https://www.tindie.com/products/20612/)! [![I sell on Tindie](https://github.com/rorosaurus/esp32-hub75-driver/raw/master/images/tindie.png)](https://www.tindie.com/stores/rorosaurus/)

## The truly universal USB-C dream is finally realized for your Game Boy Advance SP!

Charge your Game Boy Advance SP with USB-C, using any USB-C cable and charger! If it fits, it'll charge! Finally you can stop carrying around that extra proprietary cable!

The [existing PCB](https://oshpark.com/shared_projects/I6UOH6gb) that my design is based on only works with ````USB-A -> USB-C```` cables. In my opinion, if you're gonna future-proof your Game Boy, you shouldn't remain reliant on Type-A!

My PCB works with ````USB-C <-> USB-C```` cables as well, so you can use ANY USB-C cable/charger to charge it! I've also verified it works with ````USB-A -> USB-C```` cables, Quick Charge, and USB-PD! That means if your charger or USB battery pack offers 5V/9V/12V/etc., it will recognize the Game Boy can only accept 5V and charge accordingly.

# Options

DIY Kit - You recieve all the necessary parts: PCB, Type-C female connector, and 2x 5.1K SMD 0402 resistors. You will assemble it yourself using a fine tip soldering iron or solder paste and reflow.

Assembled - I will assemble the components for you before shipping. You only have to desolder the exisiting charging port, then solder 3 points to attach to your Game Boy!

3D printed bezel - I will include a small 3D printed part to fill in the gap in the case created by the smaller USB-C port. Alternatively, you can 3D print [the part](https://www.thingiverse.com/thing:4123563) yourself, or skip this optional cosmetic mod.

# Compatibility

I have tested this design on my AGS-001. Based on the AGS-101 pictures I've seen online, and talking with AGS-101 owners, I expect this to work for AGS-101 with zero issues.

This design is compatible with 3.5mm headphone jack mods! [[1](https://imgur.com/a/mqhpRvp)][[2](https://hackaday.io/project/173427-gba-sp-headphone-jack-mod)][[3](https://imgur.com/a/aFbhm)] That means my PCB will not block the other pins you need from the default charging port pads on the Game Boy's motherboard.

# Instructions
1. Watch [makho's video](https://www.youtube.com/watch?v=gBLHvdre-Xg) of installing a similar version of this PCB! This is an awesome overview that will be very helpful to reference. The below instructions simply outline what he does in the video.
2. Carefully desolder and remove existing charging port. Use a solder sucker and solder wick. Take your time and take great care to not get impatient and rip up any pads!
3. Fill in the standoffs on both PCB's (Game Boy and my PCB) with solder.
4. Ensure bottom of USB-C PCB is flat, as well as the top of the Game Boy motherboard. You can use flush cutters and solder wick to help you with this. You might need to gently and carefuly sand the bottom through-hole connections for the USB-C port to ensure they are fully flat.
5. Align the USB-C PCB so that the standoffs are directly above the Game Boy's and solder one joint.
6. Reheat the joint and realign as necessary to ensure the standoffs are aligned properly, and the 5V power line aligns well with the pad it will connect to.
7. Solder the remaining standoff to lock the USB-C PCB in place. Test the strength of this connection and reinforce if necessary. Remember it needs to support the stress of plugging in and pulling out many times!
8. Solder the 5V half circle pad to the 5V pad on the Game Boy motherbaord.
9. Plug in USB-C cable to test!

# Thanks
Thank you to [makho](https://www.youtube.com/channel/UC5FYpo9lFqK1Y7wqjPuANFw) and [BlindEye/Hidarite](https://www.tindie.com/stores/hidarite/) for the original PCB design, video, and STL file!