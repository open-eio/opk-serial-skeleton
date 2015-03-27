# opk-serial-skeleton
Skeleton project for using OPK framework with a serial device

Try it out:

- Load opk-serial-skeleton on an Arduino connected to USB port 'USBPort'
- Make 'pull' and 'act' executable on the command line (e.g. 'chmod 755 pull; chmod 755 act')
- Type 'pull -p [USBPort]' on the command line in order to get status of the LED on pin 13 on the Arduino board, where [USBPort] is replaced by e.g. '/dev/ttyUSB0'
- Type 'act -p [USBPort] -c ON' to turn on the LED on pin 13
- Type 'act -p [USBPort] -c OFF' to turn off the LED on pin 13

