# GCODE-buzzer-melodies
midi tunes converted into gcode files ready to play on your printer;]

tested on prusa MK3S+

when you try to convert or sth longest pause before FW crashes is P2000 (maybe more but P9999 is too long)
if it craches it simply stuck with `Recv: echo:busy: paused for user`, then you need push button on printer

```
M300 P[23456789]\d\d\d S0
M300 P1999 S0
```
