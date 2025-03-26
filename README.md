# WUI-SCS
A model coupling spot fire and fire spread.
1. Directory structure description:
①data：Sichuan Yajiang wildfire case data
dem.tif:Elevation data
slope/aspect.tif:Slope and aspect data
diwu.tif:Land cover data(Remote sensing image semantic segmentation algorithm based on SCTNet)
WIN:Wind speed data file
WIR:Wind direction data file
CLS:Terrain Files(Based on automatic terrain recognition algorithm ATR.py)
fuel.json:Fuel data

②Code
1）Auxiliary code：
find.py
fire_strong.py
neighbor32.py
read.py
Rothermel.py
TandD.py(Used to calculate the transport distance and distribution of firebrand)
ATR.py(Used for automatic terrain recognition to provide terrain data cls)
2)Main function:
main.py

2.Environment and Dependencies
main.py(This code and other referenced codes recommend using Python 3.7 or higher.)
ATR.py(This code recommends using Python 2.X. arcpy is required.)

3.Reproduction method
Just run main.py to verify the case.

4.Experimental Setup and Results
The model parameters can be changed based on different research cases and user needs. The output.log can be viewed during the experiment. The experimental results include visualization images (firebrands landing point map, fire spread map) and ignition judgment results.

5.Disclaimer
This research code and data are provided for reference and educational purposes only. Unauthorized use for academic publications or commercial purposes is not permitted. Any such use may result in legal action. Researchers who are interested in this work are welcome to contact me for further discussion.

 Contact:wuzq23@mails.tsinghua.edu.cn
