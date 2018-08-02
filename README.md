# RPLIDAR-MATLAB
Getting data from an RPLIDAR A1 into MATLAB and visualizing it in MATLAB. Will attempt basic detection &amp; SLAM on the received data.

<Section_1> - Steps to get the RPLIDAR connected and running on OSX:

1. Download the appropriate CP2102 USB to UART driver from Silicon Labs: https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers. Unzip the package, open the .dmg file and follow the installation instructions.

2. Download the RPLIDAR SDK from SLAMTEC's website: https://download.slamtec.com/api/download/rplidar-sdk/1.7.0?lang=netural

3. Unzip the package. Open a terminal window. Change to the directory in which the package was unzipped into. 'cd' into the 'sdk' directory. Type 'make all' at the prompt.

4. Change to the directory <SDK_HOME>/sdk/output/Darwin/Release. Type './ultra_simple /dev/tty.SLAB_USBtoUART' at the prompt to see the RPLIDAR data being acquired and displayed in the terminal window. 

</Section_1>


