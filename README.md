# Cryostat operating software LabView

Labview VI written to control temperature and sample measuring systems of closed cycle refridgerator (CCR) cryostat in University of Liverpool's mmmlab.

Main VI file = '/Labview_VI/Fridge Software v2.1.vi'

## Devices VI interfaces with
- <strong>Lakeshore 372 AC Resistance bridge</strong> - Performs electric measurements on samples and controls temperature via heater wire and PID
- <strong>3706A-S Keithley System Switch</strong> - Allows automated permuation of the 24 electrical measurement contacts available
- <strong>Arduino</strong> - Reads volage from Hall probe of external magnetic poles (driven from a separate power and computer system)


## VI screenshots

<p float="centre">
  <img src="/screenshots/LABVIEW_screenshot_ANNOTATED.png"/>
</p>
<p align="center"><i>Figure 1.  Front panel of VI. <strong>Section A</strong>:  Live temperature and sample
resistance readings. Also shows any errors with interfacing devices, amongst other features. <strong>Section B</strong>: Measurement and data file setup panels. <strong>Section C</strong>: Live signal plotting of resistance vs temperature and resistance vs magnetic field. <strong>Section D</strong>: Time traces of sample resistance, sample space temperature and magnetic field from external poles.</i></p>

<p float="centre">
  <img src="/screenshots/config_panel_comms.PNG" width="333"/>
  <img src="/screenshots/config_panel_measurements.PNG" width="333"/>
  <img src="/screenshots/config_panel_swithcboard.PNG" width="333"/>
  <img src="/screenshots/config_panel_datasave.PNG" width="333"/>
</p>
<p align="center"><i>Figure 1.  Individual screenshots of each panel within <strong>Section B</strong> of Figure 1.</i></p>

## Photo of cryostat
 
<img src="/screenshots/Fridge_entire setup_annotated_2.jpg"/>





