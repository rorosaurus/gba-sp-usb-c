# Prep

Your PCB might arrive with some [slight perforations, from the breakaway panelization design](https://github.com/rorosaurus/gba-sp-usb-c/blob/master/images/breakaway-perforations.jpg) during PCB manufacturing. These can be left alone, or optionally filed/sanded away. You probably want to file the top side flat, if you also intend to perform a 3.5mm headphone jack mod.

The half-circle pad(s) behind the USB-C connector might have some debris across it. You can safely clear that away with a toothpick or similar - that will make it easier to solder to later.

# Test before you install!

I test every board before shipping, but you should be certain it still works before you install it! Plug it in to a ````Type-C <-> Type-C```` cable and USB-C power source. **Do not perform this test with a ````Type-A -> Type-C```` cable - that cable won't verify the board works for full USB-C!** Use a multimeter to measure the voltage across any of the grounded holes and the +5V half-circle in the back. Ensure it reads ~5V. Flip your USB-C cable the other way around and verify it still reads 5V! Alternatively, if you have a USB-C multimeter [like this](https://smile.amazon.com/gp/product/B07X3HST7V/) you can simply plug into that and read the display.

# Installation Video

I highly recommend you watch [makho's video](https://www.youtube.com/watch?v=gBLHvdre-Xg) of installing a similar version of this PCB! This is an *awesome* overview that will be very helpful to reference. The below instructions simply outline what he does in the video.

# Instructions

1. Carefully desolder and remove existing charging port. Use a solder sucker and solder wick. Take your time and take great care to not get impatient and rip up any pads!
2. Fill in the standoffs on both PCB's (Game Boy and my PCB) with solder.
3. Ensure bottom of USB-C PCB is flat, as well as the top of the Game Boy motherboard. You can use flush cutters and solder wick to help you with this. You might need to gently and carefuly sand the bottom through-hole connections for the USB-C port to ensure they are fully flat.
4. Align the USB-C PCB so that the standoffs are directly above the Game Boy's and solder one joint.
5. Reheat the joint and realign as necessary to ensure the standoffs are aligned properly, and the 5V power line aligns well with the pad it will connect to.
6. Solder the remaining standoff to lock the USB-C PCB in place. Test the strength of this connection and reinforce if necessary. Remember it needs to support the stress of plugging in and pulling out many times!
7. Solder the 5V half circle pad to the 5V pad on the Game Boy motherbaord.
8. Plug in USB-C cable to test! Hooray!

# Troubleshooting

### Did you test the board before installing?

See above instructions! It's critical that you test this to ensure it was not damaged during shipping!

### Try with a different cable and/or charger

This mod should work with all combinations of cables and chargers, but try a different one to help diagnose the problem by eliminating variables.

### Flip the USB-C cable to the other orientation

If it works only in one orientation, then check the two small resistors. Ensure they are oriented properly and soldered to their pads. Reheat the solder joints with your iron and confirm continuity with your multimeter.

If it still only works in one orientation, sadly one of the six USB-C port pins has a bad connection to my PCB (damaged in shipping, most likely).

You can reflow these pins with your soldering iron, adding solder if needed. If you apply too much solder and the pins get bridged, you can use solder wick or a solder sucker to remove some.


### Did you accidentally lift up some of the original charging port's pads?

You can test with your multimeter that you have continuity from the USB-C port to the expected destination. You'll have to follow the traces or look up where they lead. You can often rewire directly to the destination if you've messed up the original charging port's pad.

### You heard a "click" or your console is no longer powering on

You might have just blown a fuse. Check F1 (or similar) for continuity and replace the part if necessary (replacement part list in the [Game Boy Discord](https://discord.gg/gameboy)). After searching for and fixing the short that caused the fuse to blow, of course!

### Still stuck?

If you're still stuck, the friendly folks in #modding on the [Game Boy Discord](https://discord.gg/gameboy) might be able to help you. Make sure you are patient and respectful - and clearly describe the problem and what you have tried to solve it so far.

I'm always available through Amazon/Tindie as well!