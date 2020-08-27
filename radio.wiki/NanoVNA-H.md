# NanoVNA-H

## Basic operation

- Set the frequency range (STIMULUS>START/STOP or CENTER/SPAN)  
- Calibration (CAL)  
- Select display format and channel (DISPLAY)  
- Save(SAVE)  

## Calibrate  
  
![calibration](https://github.com/bethanysciences/radio/blob/master/nanovna%20calibration.png)

![calibration](https://github.com/bethanysciences/radio/blob/master/NanaVNANibs.png)
  
open - internal empty  
short-circuited - copper needle  
50ohm load - stainless steel shell  

1. CAL→CALIBRATE menu to open the calibration interface  
2. connect open, short and load three loads in turn wait for screen to stabilize
3. click to calibrate CH 0.
  
## Nano Saver

![NanoVNA Saver](https://github.com/mihtjel/nanovna-saver)

```zsh
git clone https://github.com/mihtjel/nanovna-saver  
brew update
cd nanovna-saver  
python3 -m pip install
NanoVNASaver  
```
