# radeonvii
Radeon VII scripts - alternative to using gui programs

#### radeonvii

All in one control script for setting clocks, setting fan speed and setting fan
curve on your Radeon VII.

```
Usage:
    radeonvii low               : Set lowest powerstate to default clocks.
    radeonvii high              : Set lowest powerstate to max clocks.
    radeonvii undervolt <value> : Manually set clockspeed in Mhz.
    radeonvii info              : Show current clocks.
    radeonvii fan               : Manually set fan speed to value [0 - 255] or auto.
    radeonvii temp              : Auto fan control.
    radeonvii help              : Show this help.
```

#### radeonvii.service

A simple service script example to launch `radeonvii` with systemd. Edit path
as desired && copy to a systemd service directory.

#### lemongpu

An example output script for lemonbar, edit to your desire.

![lemongpu](https://github.com/lwilletts/radeonvii/blob/master/lemongpu.png)
