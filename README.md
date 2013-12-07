# Purpose

Details and video at: http://tinkerish.com/blog/?p=88

This project shows the use of a simple thermistor to measure temperature and
display the temperature graphically on a Nokia 3310 LCD. Thermistors are
incredibly cheap (about 50 cents), and provide fraction of a degree accuracy.
The Nokia 3310 Library originally written by CC Darmini was modified yet
again, this time to use per pixel access while maintaining the ability to draw
text.

## Information

For more information, please see the project blog at:
http://tinkerish.com/

* main.c, Makefile - main project
* mmc_if.c, mmc_if.h - MMC/SD card driver
* diskio.c, diskio.h - lowlevel disk I/O shim between driver and filesystem
* ttf.c, ttf.h - tiny FAT filesystem

## License

This project contains code shared under the GPL v2.  Some files are included
with this project and may be under a different license.  For each of those
files, the original copyright and source information is included, where
applicable.  If you have any questions, please contact me.

