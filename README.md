# Ice-Cream-3D-Printer
A Octoprint plugin where I scream at you when a print starts, pauses, fails, or finishes.

In my head these seems like a good project for someone new to Python. I want to make this a good enough plugin where it can be shared on the official Octoprint repo for plugins.

I will be using a raspberry pi 3B+ with this and my printer is on an SKR board. Though ideally the printer wouldn't matter as Octprint on the pi is the one that picks up when a print fails, starts, pauses and finishes. And from pause I mean if you were to add a pause in the g-code for say a color change.

I'm hoping to use a small speaker that doesn't need extra power (or usb if that) that will work off the 3.5mm jack on the raspberry pi. From within Octoprint I want to be able to turn off which sounds I want on or off (For me personally it would be nice to know right when a print finishes without waiting for an email from the spaghetti detective plugin)


Sample of how lovely it will be when this plugin is done:
https://youtu.be/mvz3LRK263E?t=211

Resources for later:
https://docs.octoprint.org/en/master/plugins/gettingstarted.html
