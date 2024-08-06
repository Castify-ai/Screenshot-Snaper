#  Android TV Screenshots

A web application to connect to an Android TV device and capture screenshots remotely.

## Installation

1. **Clone the repository**
   git clone <repo url>
2. **Navigate your project**
   cd <repo name>
3. **install dependencies**
   npm install
4. **start application**   
   npm start

## connection

1. Enable developer option and allow USB and  wireless debug in your device
   **Authorize ADB Connections**
2. Connect your device to your computer via USB for the first-time setup.
3. While connected via USB, run the following commands in your terminal:
   adb tcpip 5555
   adb connect <device_ip_address>:5555
After this setup, the user is able to connect wirelessly in future connection   


   
## usage

Open your web browser and navigate to http://localhost:3002.
Enter the IP address of your Android TV device in the input field.
Click the "Connect" button.
Once connected, click the "Capture" button to take a screenshot.
The screenshot will be displayed on the page, where you can download it
