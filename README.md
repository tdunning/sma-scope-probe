* SMA Oscilloscope Probes

It is pretty common that I am working on a project and I want to leave my 10x probes connected to an electronic circuit project. This can be for 10 minutes while I mess with something in the circuit or it might be for 10 weeks, especially if I am working on the software part of a project, but need to check periodically on the effect on the hardware side.

Leaving conventional scope probes connected is often a problem because they are big and often slip out of place. They're great when you are moving from point to point in the design, but when you want something stable they aren't nearly as good.

Lots of time, I can design in some 50 ohm outputs that can be semi-permanently connected by setting the oscilloscope to 50ohm termination, but then the question is what happens if I disconnect the oscilloscope? Or if my scope doesn't have a 50ohm termination option?

What I really want in these moments is a high impedance 10x probe that has SMA connections instead BNC on one end and a scope probe on the other.

This directory contains two KiCAD designs that allow you to have just that. These circuits are a very conventional 10x divider with capacitors that allow you to tune the compensation on probe for flat response. There is no provision for calibration.

The overall circuit including both parts looks like this:

