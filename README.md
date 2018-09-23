# pi3-poe-fan
A fan script modification for the Pi 3 PoE  hat to match what I want

---

***Stolen from: [https://www.raspberrypi.org/forums/viewtopic.php?f=45&t=219050&start=50#p1356682](https://www.raspberrypi.org/forums/viewtopic.php?f=45&t=219050&start=50#p1356682)***

---

Once the overlay script is copied onto your Pi you simply compile:

    dtc -@ -I dts -O dtb -o rpi-poe.dtbo rpi-poe-overlay.dts

and copy the `dtbo` file into `/boot/overlays`, while making a backup of the original (just in case)
