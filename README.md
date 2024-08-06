#  Android TV Screenshots

A web application to connect to an Android TV device and capture screenshots remotely.

## Installation

1. **Clone the repository**
   git clone https://github.com/username/android-tv-screenshots.git
2. **Navigate your project**
   cd android-tv-screenshot
3. **install dependencies**
   npm install
   npm start

## connection

1. Enable developer option and allow usb and  wireless debug in your device
2. The device needs to authorize the computer for ADB connections. This usually requires a one-time setup via USB, where you approve the connection.
3. After connection via USB you are able to connect wirelessly in your future connections

   
## usage

Open your web browser and navigate to http://localhost:3002.
Enter the IP address of your Android TV device in the input field.
Click the "Connect" button.
Once connected, click the "Capture" button to take a screenshot.
The screenshot will be displayed on the page, where you can download it
