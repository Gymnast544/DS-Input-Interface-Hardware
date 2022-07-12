# DS-Input-Interface-Hardware


These are the hardware files I used to make the DS Input Interface. The files are a bit messy but the Flex PCB is in my opinion a pretty good way to connect a microcontroller to all the DS inputs and mount it nicely on the back of the DS. There's also some hardware notes and drawings about touchscreen control.

I did all of the drawing for the PCB in Inkscape, as it was easy to have a correctly scaled image of the DS motherboard and measure the positions of the pads from that image. I believe I used svg2shenzhen (https://github.com/badgeek/svg2shenzhen) to convert from the inkscape drawing to KiCad. I then used KiCad for exporting gerber files. There are gerbers already exported in one of the folders, if you want to simply order another batch of the flex cables. Tip for ordering: order in bulk, as when ordering <5 the prices are enormous - it cost me just under 1/2 as much to order 3 of my test PCBs as it did to order 15. I ordered from PCBway, I think I went with 2 layers of copper, though the traces are routed such that a single layer flex PCB should work fine.

I've included the 3d printer files for the covers. The Pro Micro board is what I used in the kits I sold, as they're very cheap and easy to use and install. For my DS with touchscreen capability, I used a Teensy 4.0, which is far more powerful and makes touchscreen emulation a lot easier to program, as emulating the SPI interface using the microcontroller's builtin SPI mode wasn't something I was successful at.

There are more details on the Notion page I wrote: https://www.notion.so/gymnast544mods/DS-Input-Interface-784026d380254c439d2e0b6848e682f9
For software setup of a Pro Micro board (easiest install) look here: https://github.com/Gymnast544/DS-Input-Interface-Software/tree/master/Pro%20Micro%20Code/ds_tas_master 

I sold them on my Tindie (https://www.tindie.com/products/gymnast544mods/ds-input-interface/), not sure if I'll ever do that again.
