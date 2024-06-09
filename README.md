# Hi!

During my research on Atom S3U capabilities using CircuitPython, I've stumbled upon **_bleio** low-level **Bluetooth Low Energy** module.
Using my two other implementations, one from [Bleach](https://github.com/FLOCK4H/Bleach), second from [Jammy](https://github.com/FLOCK4H/Jammy), 
that were both based on [Sour Apple Attack](https://github.com/RapierXbox/ESP32-Sour-Apple), I was able to broadcast Samsung watch devices BLE Advertisements, 
which consecutively displayed pop-ups on Samsung device with an **Add New Device** request.

This script **does not use any Pin references**, which means - If you have built-in BLE module, feel free to test this out.
