# forceguider

Guidance software for use with digital force gauges, provided by:

Dr Alessandro Marco De Nunzio, LUNEX International University of Health, Exercise and Sports, Luxembourg

Dr David William Evans, University of Birmingham, UK


ForceGuider is an application that was built with LabView (TM) systems engineering software, produced by National Instruments (NI), USA. Therefore, before running ForceGuider, the user will need to download and install the following software from NI:
<br>
<a href="https://www.ni.com/en-gb/support/downloads/software-products/download.labview.html">LabView Runtime Engine</a> (the current build of ForceGuider will require either the '2017 SP1' or '2017 SP1 Patch' version).
<br>

ForceGuider is designed to collect analogue force data. Therefore, the application assumes that the user will be using a data acquisition device. To ensure compatibility with the Labview Runtime Engine, the authors would recommend a NI data acquisition device. We have so far tested the <a href="https://www.ni.com/en-gb/support/model.usb-6002.html">16-bit NI USB-6002</a>, which has a USB connection to the desktop computer.
<br>

The data acquisition device will allow other inputs, such as a trigger button or an electronic visual analogue scale (eVAS), to be integrated into ForceGuider in addition to the force gauge signal. Each of these inputs will need to be connected onto its own pair of terminals on the data acquisition device. The force gauge will have it's own power source, but other devices may require a power source, such as the 5V available from the data acquisition device. ForceGuider is currently configured so that a trigger button should be connected to channel (TBC) on the acquisition device, and an eVAS should be connected to channel (TBC).


ForceGuider software is provided as Freeware:

•	The authors grant a free of charge right of use. <br>
•	The authors retain copyright and ownership of all copies of the software. <br>
•	Usage of this software is conditional upon inclusion of the following citation on any website, datafile, report or publication that results from its use:

    Evans DW, De Nunzio AM. 2020 Controlled manual loading of body tissues: towards the next generation of pressure algometer.
    
•	No support or services are provided, although issues and requests can be reported through the <a href="https://github.com/usetheforcegauge/forceguider/issues">Issues</a> area in the GitHub repository. <br>
•	No warranty is provided. <br>
•	No liability is accepted. <br>

Please see the <a href="https://github.com/usetheforcegauge/forceguider/blob/master/LICENSE">license</a> for full terms and conditions of usage.
