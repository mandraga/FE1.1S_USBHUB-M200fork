# FE1.1S_USBHUB

## Description:
This is an working USB HUB using the FE1.1S ic. It has low transfer speed, but it\`s working.<br>
The board has 5 led\`s(one to show each port activity and one for general working), 4 decoupling capacitors (for the 1.8V, 3.3V and 5V internal regulators), an 2.7kohm (+- 1%) resistor between pin 14 and GND and an  12MHz oscilator between pins 2 and 3.

<table>
  <tr>
    <td><img src="https://github.com/Tonikiller10000/FE1.1S_USBHUB/blob/main/Usb_Hub_Pictures/2.jpg"></td>
    <td><img src="https://github.com/Tonikiller10000/FE1.1S_USBHUB/blob/main/Usb_Hub_Pictures/5.jpg"></td>
  </tr>
</table>

## My schematic
<img src="https://github.com/Tonikiller10000/FE1.1S_USBHUB/blob/main/Usb_Hub_Pictures/4.jpg">

## Results:
As you can see, the USB hub is recognised and it\`s working. 
One ["mistake"](https://github.com/Tonikiller10000/FE1.1S_USBHUB/blob/main/Usb_Hub_Pictures/12.jpg) I connected the GND trouth the USB ports mounting pins, witch needs that all the ports to be connected, or to connect the mounting boles of the ports with an wire.
The thing I don\`t like is it\`s transfer speed, but in the future I think I can experiment with it to make it work at the USB2.0 full speed(480MHz) and to use it`s pins to be controlled by a microcontroller.
<img src="https://github.com/Tonikiller10000/FE1.1S_USBHUB/blob/main/Usb_Hub_Pictures/8.png">

## Links:
- FE1.1sDatasheet: https://cdn-shop.adafruit.com/product-files/2991/FE1.1s%20Data%20Sheet%20(Rev.%201.0).pdf
- The schematic from witch I did mine: https://github.com/Tonikiller10000/FE1.1S_USBHUB/blob/main/Usb_Hub_Pictures/3.png 




