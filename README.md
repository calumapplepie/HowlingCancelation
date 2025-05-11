# What this is
CALUM COPY PASTE YOUR ABSTRACT HERE

# How To Run
- Install matlab, and probably a whole bunch of toolboxes.  Definitely the ones for:
	- DSP blocks 
	- communication systems.
	- audio toolbox
	- desktop real-time (apparently? its listed as a dependency)
	- Idk, probably some more?
- Open and run WalshCodeCacher.
- Open and run SimV8 or later.  Earlier versions may need you to change from ConfigData.sldd to AllSimData.sldd as the data source.

# Rapid Accelerator
I had to add 
/home/calum/.local/matlab/2024b/bin/glnxa64/libmwdsp_halidesim.so
as a 'custom library' to get the rapid accelerator mode working on my laptop.
No, I don't know why, and no, it doesn't make sense.
