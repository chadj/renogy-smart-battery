# Renogy Smart Battery Data Read
Web application to monitor the Renogy 200ah LiFePO4 Battery over bluetooth (w/ Web Bluetooth API).  No server needed.  All client side javascript.  This is a simple app to demonstrate the code and protocol needed to read battery states such as temperature, volts and current.  Feel free reuse and adapt this code for your own project.

This code has only been tested with the Renogy 12V 200Ah Lithium Iron Phosphate Battery w/ Bluetooth.  That's the only one I own.  I developed this code to learn how to read the temperature off of the battery.  Ultimately I want to build a battery warmer driven off of an ESP32 microcontroller.

See this code in action at: https://chadj.github.io/gpedal/

This web app will only work in Chrome (android / desktop / derivatives).  On Apple devices you can use WebBLE (https://apps.apple.com/us/app/webble/id1193531073) or Bluefy (https://apps.apple.com/us/app/bluefy-web-ble-browser/id1492822055).
