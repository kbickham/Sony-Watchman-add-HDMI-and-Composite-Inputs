# Adding HDMI/Composite inputs to Sony Watchman

Who doesn't love CRTs? I do... Electron guns are cool. It's gonna be a while before I get to this, 
but I found this Sony Watchman Radio/TV at the thrift store for $3.77. Out of one of my old TVs,
I scaveneged this board that breaks out the inputs from an HDMI and Composit connectors. I've looked around 
online, and am thinking I might be able to convert the signal on an FPGA. I'm not concerned about quality loss
as I have to convert it into RF to use the signal on the CRT. 

This may not be feasible. If it isn't I'll go buy an adapter from the hardware store..but this little breakout board is just screaming "USE ME FOR SOMETHING!"

![Sony Watchman and HDMI interface from a Coby TV](https://github.com/kbickham/Sony-Watchman-add-HDMI-and-Composite-Inputs/blob/master/sony%20watchman.jpg)

I've had experience working on Sparta 3 boards, but right now that's a little out of my price range. Aside from banggood and aliexpress... amazon has some cheaper clones on sale for around 20$ that have decent shipping times. This is what I'm looking at: the RioRand EP2C5T144 Altera Cyclone II FPGA Mini Development Board., but I'm not sure if theres enough data bandwidth/bit width to process the signal, but if there is... I'm going to try.


![Cyclone II FPGA Board](https://github.com/kbickham/Sony-Watchman-add-HDMI-and-Composite-Inputs/blob/master/fpga.PNG)
 
