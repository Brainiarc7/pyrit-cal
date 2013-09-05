pyrit-cal
=========

This is a Pyrit Version that comes with CAL ( Compute Abstraction Layer) support out of the box. Pyrit-CAL is much faster than Pyrit-opencl on AMD Radeon GPUs (Redwood/Capilano cores and beyond).
This application requires that you have calpp and AMD APP SDK 2.8+ installed on your machine.

The reason this port was created is because the older Pyrit on code.google.com is no longer actively maintained by the author, Licas Lueg, and that version will not build with the latest AMD APP SDK.
I have modified the original source code and added support for the latest AMD APP SDK, from here and beyond.

The core has also been re-written to allow for proper OpenCL 1.2 Device Partitioning support. What this means is, your X-session will no longer hang in benchmark mode and when pyrit is running.

Build instructions will follow when the commits are done.
