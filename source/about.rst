About
=====

OpenDCS is a collection of software tools used primarily for gathering hydrologic data.
It is used extensively by the US Army Corps of Engineers Water Management Community 
and the US Bureau of Reclimation
to retrieve and remote field data from satellites and other sources such as direct 
Serial, Modem, or Ethernet based connections.

The project originated under the US Geologic Survey with the Namne "DECODES".
It was initialy created to process data
from the NOAA GOES satellites (https://dcs1.noaa.gov/ for more informatoin.)

Over time additional sources for data collection were added. Eventually a "real-time" computation engine was added
to the project.


At this time OpenDCS consists of the following elements:

LRGS
####

Local Readout Ground Station. This component is responsible for listening for data from various sources. 
Such as an HRIT receiver (https://www.noaasis.noaa.gov/GOES/HRIT/about_hrit.html), 
A DRGS system (https://noaasis.noaa.gov/pdf/DRGS_Overview.pdf&usg=AOvVaw0621_eNI-dX-DjlIh9hoGv),
or another LRGS.

DECODES
#######

Originally created for processing GOES satellite data into human and machine readable engineering units, DECODES is a 
generic language for processing input data from almost any type of source.


Computation Processor
#####################

Originally Instigated by the US Bureau of Reclimation, this component facilitates automated screening,
 conversions, other calculations. Data can be processed as instantaneous values or two types of aggragate windows.

Algorithms can be written in Jython, or custom algorithms can be created directly in Java. At this type there are no 
concrete plans for additional scripting languages.
