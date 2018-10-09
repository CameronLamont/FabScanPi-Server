### FabScanPi 0.6.0 release. (dev)
In this release the Tornado Framework is introduced. This brings more 
stability to the webserver part. The whole webserver code was refactored. 

Changelog for this version: 


### FabScanPi 0.5.0 release. (2018-04-04)
The new release brings a better camera performance and also the USB cam module back. 
We switched to a newer version of OpenCV which leads also to a better performance 
and a more stable calibration process.

Changelog for this version:

  * fixed pykka aktor threading bug in streams
  * fixed bug realated to 400 step motors
  * replaced magic numbers by config values (tnx to jwalt)
  * fixed typo in documentation (tnx to kradrat)
  * new documentation parts (tnx to jens hackel)
  * fixed green cam bug
  * added deleting old calibration data before new calibration
  * refactored camera driver ( much faster than before )
  * added abort sequence when scanner is not calibrated
  * added new handlers for gracefull application shutdown
  * fixed start stop init script and added better logging to it

### FabScanPi 0.4.3 and updated documentation. (2017-07-26)
First of all i would like to thank all FabScanPi builders/users/community members for 
reporting bugs and sharing experiences. Special thanks goes to Jens Hackel for his
awesome job on writing most of the FabScanPi documentation. 

Some users mentioned problems with FabScanPi HAT serial connection. We added a troubleshooting 
guide to the [F.A.Q](http://mariolukas.github.io/FabScanPi-Server/faq/#hardware) section of the 
documentation.

Changelog for this version: 

 * Auto-calibration values are saved and available after a reboot. 
 * Meshing was refactored. 
 * Meshing filters are reduced to two basic filters to prevent confusion 
 * Added new output formats to meshing. Available formats are ply, stl, obj, off, xyz, x3d, 3ds now.

### New FabScanPi release with auto calibration (2017-02-01)
A new release of the FabScanPi software with some new exciting features:

 * Auto-calibration improves the scan results and simplifies the setup process.
 * Read news from the FabScanPi project to stay informed about new features and improvements.
 * Improved updates allow to update your installation with one click.
 * fixed some major BUG's
 * refactored serial communication

Have fun!

### Added some example scans (2017-01-31)

We uploaded some FabScan example scans. You can explore them by visiting the example page. http://mariolukas.github.io/FabScanPi-Server/examples/

### FabScanPi goes slack (2016-07-10)
To improve the communication between FabScanPi users and enhance the support FabScanPi now uses slack. Register at
[https://fabscan.slack.com](https://fabscan.slack.com) and join the FabScanPi community.

**First FabScanPi Workshop (2017-03-30)**

On 1th of april 2017 we will provide the first FabScanPi workshop. 
It will take place at Watterott electronic? . The workshop will include all the 
needed parts to build your own FabScanPi. You will be guided during the whole workshop. 
And finally you will get a sneak preview to the nex release of the FabScanPi 
software which includes autocalibration!

More information can be found at: https://goo.gl/mC9cHs

**Added some example scans (2017-01-31)**

We uploaded some FabScan example scans. You can explore them by visiting the example page. 
[http://mariolukas.github.io/FabScanPi-Server/examples/](http://mariolukas.github.io/FabScanPi-Server/examples/) 


**FabScanPi goes slack (2016-07-10)**

To improve the communication between FabScanPi users and enhance the support FabScanPi now uses slack. Register at
[https://fabscan.signup.team](https://fabscan.signup.team) and join the FabScanPi community.

We look forward to welcoming you!
