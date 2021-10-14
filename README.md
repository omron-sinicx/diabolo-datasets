This repository contains the recorded positions of the diabolo and each stick during play.

![](recording_setup.jpg)

Six Optitrack Flex cameras were recording the diabolo and sticks from the front. The raw data contains the rigid body defined in the Motive motion tracking software. We apply an offset to these rigid bodies, so that the origin of the diabolo is at its center, with the x-axis pointing along the axis of rotation, and origin of the stick frame is at the sticks' tip. 

![](coordinate_frames.jpg)

These files should go into the `diabolo_play/experiments` folder in order to use them with the `diabolo-play` repository. To use (replay) them, the offsets need to be applied as described above.
