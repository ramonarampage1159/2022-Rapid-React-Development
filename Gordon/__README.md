Notes for FRC robots:

Firmware Update and Loading Image:
Install firmware on your roboRIO via only USB cable and Windows Explorer and the firmware file.
For formatting and loading image by reformatting, use only the USB cable again along with the roboRIO Imaging Tool. 
Follow the instructions explicitly. 
https://mililanirobotics.gitbooks.io/frc-electrical-bible/content/roboRIO/configuring_the_roborio.html

Disable Windows Fast Startup:
Windows Start button/Settings/System/Power & Sleep, Additional power settings, Choose what the power buttons do. 
Under Shudown settings below, uncheck the box for "Turn on fast startup (recommended)" and "Save changes".

FRC Support Forum:
You do not need to pay for NI support. Please use the NI FRC forums to get in touch with our FRC-dedicated support team. 
https://forums.ni.com/t5/FIRST/ct-p/first

This is what I did to fix our RIO:
1. Download the NI MAX Application here: NI CompactRIO 5 (use version 21.0)
2. Re-run the FRC Game Tools installer after installing this driver to ensure your system remains configured for FRC.
* Plug the RIO into your computer via the USB cable
* Locate the RIO in NI MAX (it should show up under the “Remote Devices” tab)
* From there you should be able to upgrade the firmware of the device to the latest one: Upgrading or Downgrading Firmware on an NI Linux Real-Time Device 5
    Note: NI MAX will ask you to sign in, and to sign in you need to use
      Username: admin
      Password:
    (Password is intentionally left blank, unless your team has changed the admin password on the RIO)
* Once the firmware is flashed and the RIO has rebooted, try to image the roboRIO with the latest FRC Image using the FRC RoboRIO imaging tool.

