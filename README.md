# photoGPS
Do you own a Jobo Photo GPS or a Bilora Geotagger 118 Photo-GPS? 

After shutting down the U-BLOX server (http://www.jobo.com/support) the device is not usable anymore.

The goal of this project is to create an open source software that does the job... 

Jobo claims, the functionality of the server that is down now would have been providing the GPS correction data to the given time.
Even without any GPS correction log, the data should not be usable. 

## Planned steps

* Reverse engineering the USB protocol. A USB sniffer in combination with the Taggr software could be of use here...
* Setting the time in the GPS and possibly deactivating the "disabled" state the devices have when you sync now.
* Capturing data and reading them out.
* Understanding the functionality required to transform the satellite captures to positions.
* Implementing the mapping in the new software.
* Saving the result in a kml file.
* Checking if the GPS correction signal from the given time is required.

## Required

* You!
* Who wants to join?
