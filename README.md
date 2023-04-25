# XBT-BinaryDecoder
Single file binary decoder, plotter and ascii export Python script

Download all the files to the same directory and run it from there (the .bin and .csv are not necessary).

The main script is *xbt2ascii.py* -> RUN this script on a terminal or Visual Studio Code.
Go to the directory where the scripts are located with cd path and then execute 
python xbt2ascii.py or python3 xbt2ascii.py or py xbt2ascii.py

If using a terminal with no graphic interface or running the script in the cloud, make *enableBrowse = False* since this will trigger an error when trying to open the browser GUI.

Edit the xbt2ascii.py file to enter the binary file path manually. 
Edit the xbt2ascii.py file to change the configuration:
-	Enable/disable plots (profile and map)
-	Select type of map to display
-	Edit xbtxxxxx.bin full path (if browse GUI is disabled)
-	Enable/disable terminal print of all T vs D values
-	Set number of datapoints to display in the terminal
-	Enable/disable export to TXT file


Necessary libraries that may be needed to install with pip install libraryname before running the script (use pip3 if pip doesn’t work):
pip install bitstring
pip install matplotlib
pip install basemap
pip install numpy
pip install tkinter  >> Tkinter usually comes with the latest Python versions so may not be necessary to install.

<img width="468" alt="PlotsPython" src="https://user-images.githubusercontent.com/89260258/234389419-32ae1c72-3316-45f3-bff6-c65475ec6fe6.png">
<img width="468" alt="terminalMetadata" src="https://user-images.githubusercontent.com/89260258/234389420-53f7f68b-d2ad-4894-a8c0-3d0cfb1a1c9b.png">
