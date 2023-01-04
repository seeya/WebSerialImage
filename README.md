# Web Serial Image
This project aims to try out the WebSerial API available on the desktop version of Google Chrome browser.

There is a button to connect to a serial device and read data from it.

The data read is supposed to be in a format. The `STX` and `ETX` is used to determine the start and end of a payload.
Where the payload is in hexadecimal.

```
[STX][Payload][ETX]
```
