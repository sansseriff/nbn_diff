## Detector Packages with sapphire rods

Here's CAD files and engineering drawings that specify the design of the SMA package:

[diff_pixel_sma_package.zip](./attachments/diff_pixel_sma_package.zip){:download="diff_pixel_sma_package.zip"}

Alternatively, view the design PDFs here:

![Main package](./attachments/main_package.pdf){ type=application/pdf style="min-height:25vh;width:100%" }

![Cap](./attachments/cap.pdf){ type=application/pdf style="min-height:25vh;width:100%" }

## Install SMA ports

### Installing center pin

For soldering the SMA center pin parts (part 142-1000-004, [Digikey](https://www.digikey.com/en/products/detail/cinch-connectivity-solutions-johnson/142-1000-004/4864611?s=N4IgTCBcDaIIwBYwFo4AYPIwkBdAvkA)) into the detector package.

Take some solder that is **1.55 mm** thick, a wrap it around a **#35** drill bit (diameter 0.11 inch). This creates a sort of helicoil structure. Cut along the length of the coil to create a series of solder rings with the same inner diameter as the outer diameter of the drill bit. Flatten each ring, and drop one each into the SMA holes on the gold plated SMA package.

<iframe width="560" height="315" src="https://www.youtube.com/embed/moFOLqQ5Ais?si=26eJrzLEOWp0P7-Z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Then, drop the _spark plug_ piece into each SMA hole, over the solder ring. Take the structure to the solder oven. Place the mounts **with the SMA holes facing up** on the oven plate, and begin a heating cycle.

### Screwing in the SMA ports after soldering center pin

NOTE: We have tried installing the SMA ports before and after the step where the shunt PCB is mounted to the package by heating it up in the solder oven. The benefit of installing the SMA ports first is that you can be sure the the soldered center pins will not dislodge in the 2nd round of oven heating. The potential downside is you're heating up the plastic material inside the SMA port. As the diagram on the main page is laid out, the shunt PCB package is installed before adding the SMA ports. With this order, we haven't observed the center pins to dislodge much. You can still screw on the port after. So while heating the SMA ports also wasn't observed to damage them significantly, we don't see a major downside to installing them after the shunt PCB heating step.

<iframe width="560" height="315" src="https://www.youtube.com/embed/jsAHK2aODkM?si=ksNBcjVCz038-kgO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

[This](https://www.hasco-inc.com/tools/thread-in-install-tool-sma-2-92mm-and-3-5mm/) is the installation tool shown in the video. Though, it's out of stock at the time of writing. We found that using two hex nuts with the same threading as the SMA connector could be used to achieve the same result. Also, with two nuts, it may be more clear how the installation process works:

1. Thread both nuts onto the SMA connector
2. Tighten the nuts onto each other tightly using two wrenches. This way, they can be used to exert torque onto the SMA insert itself, without damaging the threads of the insert by directly using a wrench or pliers on it.
3. Use a wrench on one of the nuts to screw it into the gold-plated package. Exert more force/torque than you would normally use to screw SMA connectors together. We don't want these inserts coming out when someone unscrews a cable from the SNSPD package.
4. Unscrew the nuts from each other using two wrenches.
