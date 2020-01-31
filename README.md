# Rock101
Rock101 SS8

## Services running in startup
- Display BTN2, BTN3, BTN4, BTN5
- Monitor Mic 3 TB, plays PC if pressed.
- Monitor Mic 4 TB, plays PC if pressed.
- Monitor Delay box state, in or out of Delay.
- Moniotr VoxPro Source change.
- Monitor Control Room monitor (CRX) change.
- Moniotr On-Air lights state, ON or OFF.
- Monitors VoxPro recording.
- Stop VoxPro recording when phone is hung up.
- Check Delay status.
- Check VoxPro Source.
- Check VoxPro Record Tally.
- Check Studio in use.
- Check CRX source.


## BTN1
### BTN1_PRESS
MediatTouch next event button.

## BTN2
### BTN_2PRESS
Vancouver to Calgary Simulcast, changes inputs for Air Chain, Genie and, Audio Console so local market can go to AIR.

## BTN3
### BTN3_PRESS
Vancouver to Calgary Simulcast, changes inputs for Air Chain, Merlin and, Audio Console so local console doesn't go to air.

## BTN4
### BTN4_OVERPRESS 
Sets the Air feed back to C2 PGM, sets the Audio Console back to its default settings. C2 is now live to air. Disconnects sources from the codecs to reduce confusion in Calgary. 

## BTN5
### BTN5_PRESS
Changes inputs for Air Chain, Merlin and Audio Console, Vancouver can go to air with a feed from Calgary.

### BTN5_OVERPRESS
Changes input for Air Chain, Merlin and Audio Console, so local console doesn't go to air. 

## BTN6
Caller Dump
### BTN6_PRESS

### BTN6_RELEASE
Release Dump.

## BTN7
### BTN7_PRESS
Start Delay Unit

### BTN7_RELEASE
Release Delay unit.

## BTN8
### BTN8_PRESS
Ends delay

### BTN8_RELEASE
End delay release
