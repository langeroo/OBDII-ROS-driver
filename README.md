# OBDII-ROS-driver
OBDII interface ROS driver

# RUN

Simply type:

```
python obdii-publisher.py
```

It will connect to OBDII USB interface (the first one for now): `/dev/ttyUSB0`

# TODO

- [ ] Port as parameter instead of default `/dev/ttyUSB0`
- [ ] ROS package (there is ROS node already)
- [ ] Automaticaly publish all available data
- [x] Add udev rules

# Tested

Cars:
- [x] Seat Alhambra 2016

OS:
- [x] Ubuntu 16.04

ROS:
- [x] ROS Kinetic
