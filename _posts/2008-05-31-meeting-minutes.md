Hello, this is Joel, the current Vice Chair of NDSU's Association for Computing Machinery. As you may or may not have noticed, our primary webserver has been down for a few weeks now over the summer, but that's changed now and we are back in action!

There are still a few kinks to work out, but we should be back up to full speed this fall. If you are a current customer, please contact me soon about restoring your old files.

Some technical details about what the heck happened!
A few weeks ago there was a power outage and while we were using a UPS, we were not using the monitoring software that went with it. What happened is that the power went out as both hard drives were in the middle of writing data. What then happened was a 'head crash' where the drive head physically makes contact with the drive and scratches the platter. it was later determined that it possibly landed somewhere on the stored database file.
On top of that, the system was running BSD with a software raid. (The system had a hardware raid, who knows why it wasn't using that) Much thanks to admin Adam, who had the patience to figure out gmirror and recover some of the data.

So, now we got 2 new killer 'western digital' 160 gb drives, and an OS that can read a UPS and shutdown safely.

So, thanks for your patience, and if you haven't contacted me or gotten my email, if you are a currently paying cusomer, please email me soon, Joel.Longanecker@NDSU.edu. Thanks!