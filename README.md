# send-usb
Simple program for sending data over USB. I use it to simply testing of RF transmitter projects by sending commands to an arduino with and RF24Lo1 attached. The arduino code is  [here](https://github.com/rickspencer3/sketchbook/tree/master/rf_usb_transmitter).

#usage
```
$ ./send-usb --help
usage: send-usb [-h] --string STRING

Send strings over USB

optional arguments:
  -h, --help       show this help message and exit
  --string STRING  The string to send
```
