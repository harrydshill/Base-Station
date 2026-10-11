## Base-Station
PCB for an RTL-SDR basestation I am working on. Ideal is to have an SDR with QRH antenna for talking to NOAA satellites. An Arduino UNO Q is used to allow for linux - makes life easier with using GPredict and such to track the satellite. 

## PCB Features

# Main PCB
- RS485 (for controlling PELCO mount to rotate antenna to track satellite)
- USB hub (to split the single USB-C port of the UNO Q into two ports)
- Temperature and current sense
- PoL converters for each USB port

# LDO PCB 
- Ultra high performance inline LDO board to condition the power supply for the RTL-SDR

##Status
Wip 😱
