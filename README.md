# Live Map for [FM-DX-Webserver](https://github.com/NoobishSVK/fm-dx-webserver)

This plugin shows the detected reception (PI code/station ID) in realtime on a map.

![screensh](https://github.com/user-attachments/assets/f3c78e84-ea87-4c7d-b1f6-5de4dfbb0c99)


## v2.0

- new layout
- Display of transmitters if no PI code is received
- Filter for distances (100, 250, 500, 750, 1000 km)
- TXPOS button for radius display around the transmitter position (details see LiveMapQuickGuide.pdf!)
- Implemented PI code verification

## Installation notes:

1. 	Download the last repository as a zip
2.	Unpack the LiveMapPlugin.js and the LiveMap folder with the livemap.js into the web server plugins folder (..fm-dx-webserver-main\plugins)
3. 	Restart the server
4. 	Activate the plugin it in the settings
5.	Read the LiveMapQuickGuide.pdf 

## Important notes: 

- In order to display the position correctly, your own coordinates must be entered in the web server!
- A first display occurs as soon as a first PI code has been detected. The display is further specified when a station ID is received and updated dynamically when changes occur.
- The position of the pop-up window can be changed by pressing the border and moving the window. By pressing and dragging the blue triangle in the lower right corner, the size of the window can be adjusted.

## History:

## v1.2a

- Insert close X at the top-right corner

### v1.2

- Enlarged header with additional log information

### v1.1

- The position and size of the window is now variable
- Problems with using the web server button have been fixed

### v1.0

- first edition
