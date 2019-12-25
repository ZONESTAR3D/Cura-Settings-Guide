One of the most common problems in 3D printing is that the printer doesn't extrude enough material to produce a nice, solid object. When this happens, we speak of "underextrusion": The nozzle extrudes less material than intended.

Underextrusion can also manifest itself in many ways. In the most extreme case, the object is very brittle and the insides can be seen through the surface. Sometimes it's visible by the line widths being too small, so that they don't connect to the adjacent lines. Sometimes it only manifests as small holes in the top surface or tiny fractures in the walls.

There are myriad possible causes for underextrusion, making it very hard to troubleshoot this. The rest of this article describes some of the most likely causes and how to remedy them.

Clogged nozzle
----
If your printer was previously printing fine, and suddenly exhibits underextrusion without any significant changes to the printed object or settings, it's likely that the problem is somewhere in the extruder train. Usually the weakest link here is the nozzle.

Clogged nozzles are a regular occurrence with any 3D printer. This can happen when the filament is contaminated with things that don't melt well and gets pushed into the nozzle. It may also happen when the filament itself is burnt in the nozzle. That can happen when the plastic is heated too high or kept at a high temperature for too long. The material will degrade, the polymers will crystallize and you're left with a piece of hard plastic that won't melt out of the nozzle. To remedy this, you need to pull the debris out of the nozzle.

There are several techniques to pull out debris from the nozzle. If you have an acupuncture needle or some other thin metal pin you can push it out from the bottom. However the most common technique is known as the "Atomic Pull". To execute this technique, take a piece of filament at least 50cm long, preferably of some material with a high melting point. Heat up the nozzle to the melting point of that filament (e.g. 190°C for PLA), then push the filament in with pliers until some material is coming out of the nozzle. Then let the nozzle cool down towards its glass transition temperature (e.g. 60°C for PLA), all the while pushing the filament down into the nozzle. Just before the glass transition temperature is reached, pull the filament out quickly. If the tip of the filament is dirty with blackened plastic, snip off the tip and try again until it's clean. Try printing something again and hopefully it's extruding better now.

Slipping feeder
----
Sometimes the feeder doesn't get enough grip on the filament to push it down hard enough through the nozzle. During printing, you can hear the filament slip periodically then, with a soft clack every few seconds. This is the feeder trying to push the filament in, but the filament slipping out again once in a while.

Most feeders will have points of adjustments to adjust how much force they exert on the filament. Try adjusting the feeder a bit more tightly onto the filament. If the feeder is pushing too hard against the filament, it might break the filament or cause too much friction and start grinding. If it's too loose, you'll often see some underextrusion.

Inconsistent filament diameter
----
While most filaments are fine, sometimes a batch gets produced where the filament is just a bit too thin. This can have big consequences on the amount of extrusion in your print. Cheaper filaments are often more prone to show this problem. You can use calipers to measure the actual diameter of your filament. Be sure to measure in several different spots along the length of the filament, and don't measure where the feeder has ground down the filament.

If the filament's diameter is too far off (a 50μm difference starts to be seen in the print) then you can adjust the diameter of your filament in the material manager. If you're using a built-in material of Cura, you'll need to duplicate that material before editing it. Cura will then compensate for the new diameter by adjusting the speed of the feeder.