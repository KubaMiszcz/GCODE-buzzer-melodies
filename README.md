# GCODE-buzzer-melodies
midi tunes converted into gcode files ready to play on your printer;]

# tested on prusa MK3S+

1. find the midi
2. open it in any MIDI editor and find leading track
4. go to [https://alexyu132.github.io/midi-m300/], load your midi, check leading track
5. generate
6. copy paste into gcode
7. test;]

when you try to convert or sth, longest pause before FW crashes is P2000 (maybe more but P9999 is too long)
if it crashes it simply stuck with `Recv: echo:busy: paused for user`, nothing explodes, you just need to push button on your printer

```
M300 P[23456789]\d\d\d S0
M300 P1999 S0
```
