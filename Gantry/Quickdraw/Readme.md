Quickdraw mount for VZbot Alu Printhead.

Strip 2 24AWG wires for about 2cm twist the wire so no strands are loose and stick it in the back of the Quickdraw mount. Cut wires flush with magnets after they have been added into the mount and put a dot of glue on the wire where it enters the Quickdraw Mount.

6x3mm Magnets 6x
M3 Heat inserts 8x
15cm 24AWG wire 2x
Omron D2F-5 1x

To use quickdraw a module needs to be added.

SSH into your Pi with a application like Putty and type:

cd ~/klipper/klippy/extras
wget https://raw.githubusercontent.com/Annex-Engineering/klipper/master/klippy/extras/dockable_probe.py
sudo service klipper restart 

For more info go to [Quickdraw](https://github.com/Annex-Engineering/Quickdraw_Probe)
