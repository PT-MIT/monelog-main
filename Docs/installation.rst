Installation
============

Software vs. Hardware
---------------------

Strictly speaking, MonELOG began as a software project
with no specific hardware platform in mind.
That objective was soon supplanted by an open hardware 
design based on the ESP8266. Typical MonELOG installations 
use a commercially manufactured unit that is certified to 
UL and CE safety standards and complies with FCC requirements.

The MonELOG firmware is factory installed and 
can be automatically and securely updated over WiFi.
This section of the documentation deals with the physical 
installation of the commercial MonELOG unit with factory 
installed firmware.

Components
----------

MonELOG has 15 input channels.  
One is reserved for monitoring voltage, 
and the remaining 14 can be used to monitor power *or* voltage.
The minimum requirements for operation are:

    * MonELOG
    * USB power supply
    * AC voltage reference transformer
    * Current Transformer (one or more)


Voltage and Frequency
---------------------

MonELOG can work with all common line voltages at 50Hz/60Hz.
Additionally, it can use multiple voltage references for 
polyphase measurement.
The most common environments are 120/240V 60Hz and 230V 50Hz.
The USB power supply and AC transformer must be appropriate for the power system.

Connections
-----------

Setup is simple:

 #. Connect the USB power supply to the ``5V DC USB``
 #. Connect the AC transformer to the ``9V AC REF``
 #. Plug the power supply and AC transformer into a wall socket

That's it.

Next step: `connecting to WiFi <connectWiFi.html>`__

 