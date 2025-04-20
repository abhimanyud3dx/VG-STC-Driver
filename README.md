# Samsung TV Camera Firmware Loader (Windows)

## Download the Zip file "VG-STC-FWLoader v1.0.zip"

Supported Cameras:
- VG-STC2000
- VG-STC3000
- VG-STC4000
- VG-STC5000

Instructions:
1. Plug your Samsung camera into a USB port.
2. Install the driver from https://zadig.akeo.ie/ for all the USB Id that starts with 04e8 
3. After extracting the files from the "VG-STC-FWLoader v1.0.zip", run FirmwareLoader.exe as Administrator.
4. The message should show that your camera is detected.
5. Firmware will automatically upload if a supported camera is detected.
6. Now use the application that requires Camera, like Windows Camera App or Zoom, and it should detect both the Mic and Camera.

Make sure the 'firmware' folder is in the same directory as the EXE.

Requirements:
- Windows
- libusb-1.0.dll (included)

Credits:
- Based on Ondrej Zary’s original Linux firmware loader
- Windows version by Abhimanyu

## source code : https://github.com/abhimanyud3dx/samsung-tvcam-fwloader
