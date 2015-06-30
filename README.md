Overview

Emulator supports event-injection via ECP(Emulator-Control-Panel). However, injecting sensor events via ECP is less intuitive and less convenient. Moreover, while developers inject event, simultaneously touching emulator screen is impossible. The EventCast enables developers to inject sensor and touch events more intuitively by means of real target.

EventCast App in the target gathers those events and passes them to emulator controller, which converts and hands them over to Tizen Platform. It is useful for App developers who do not have a Tizen mobile device.

EventCast provides three features.
 - Touch : M aximum touch point is 10.
 - Sensors : Accelerometer / Gyroscope / Geo-Magnetic / Proximity / Light Sensor
 - Display: Get images of Tizen Emulator and draw them when using touch feature


How to use EventCaster

EventCaster which is the App on target communicates with Tizen Emulator (PC) by TCP/IP . It can connect to Emulator via Wi-Fi.


Prerequisites
 1.In case of Wi-Fi , make sure that your iOS devices and PCs are with in the same AP.


Install EventCaster App

You can install the Tizen EventCaster from App Store. please install it manually.


Connection between App and Emulator


Wi-Fi

 1. Enable Wi-Fi on device and select Wi-Fi network
 2. Connect iOS devices to the network that Tizen emulator is connected.
 3. Launch ‘Tizen EventCaster’ application and then click 'Start’ button.
 4. An ip address and port will be displayed.
 5. Select a WiFi checkbox of EventCast tab on the Tizen Emulator Control Panel
 6. Input IP address and port number using ‘Tizen EventCaster’ application,
    and then click ’Connect’ button on the Tizen Emulator Control Panel.
 7. If the emulator connects to app successfully , 
    you can see green lights of touch and sensor in the Tizen Emulator Control Panel.
 8. You can deliver sensor or touch value to an Tizen Emulator in each tabs.
