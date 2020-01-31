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
**BTN1_PRESS** </br>
MediatTouch next event button.

## BTN2
**BTN_2PRESS** </br>
Vancouver to Calgary Simulcast, changes inputs for Air Chain, Genie and, Audio Console so local market can go to AIR.

## BTN3
**BTN3_PRESS** </br>
Vancouver to Calgary Simulcast, changes inputs for Air Chain, Merlin and, Audio Console so local console doesn't go to air.

## BTN4
**BTN4_OVERPRESS** </br>
Sets the Air feed back to C2 PGM, sets the Audio Console back to its default settings. C2 is now live to air. Disconnects sources from the codecs to reduce confusion in Calgary. 

## BTN5
**BTN5_PRESS** </br>
Changes inputs for Air Chain, Merlin and Audio Console, Vancouver can go to air with a feed from Calgary.

**BTN5_OVERPRESS** </br>
Changes input for Air Chain, Merlin and Audio Console, so local console doesn't go to air. 

**BTN5_RELEASE**
BTN5_PRESS runs when released. 

## BTN6
Caller Dump 
</br>
**BTN6_PRESS**

**BTN6_RELEASE** </br>
Release Dump.

## BTN7
**BTN7_PRESS** </br>
Start Delay Unit

**BTN7_RELEASE** </br>
Release Delay unit.

## BTN8
**BTN8_PRESS** </br>
Ends delay

**BTN8_RELEASE** </br>
End delay release
