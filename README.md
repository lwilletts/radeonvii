# Radeon VII

Radeon VII utilities: terminal script alternative to using GUI programs.

#### radeon

All in one control script for setting clocks, setting fan speed and setting fan
curve on your Radeon VII.

```
Usage:
    radeon clock <Mhz> <mv> : Manually set core clock speed at specific voltage.
    radeon mem <Mhz>        : Manually set memory clock speed.
    radeon power <Watts>    : Manually set the power limit.
    radeon info             : Show current clocks.
    radeon fan              : Manually set fan speed to value [0-255] or auto.
    radeon temp             : Auto fan control.
    radeon help             : Show this help.
```

You'll have to modify the fan curve within the case statement in the script,
but I have set it by default to maximum fan RPM once the hotspot temperature is
above 90 degrees.

#### radeon.service

A simple service script example to launch `radeon` with systemd. Modify to your
preferred clock and voltage. Place in a preferred directory e.g.
`/etc/systemd/system/`.

#### lemongpu

An example output script for lemonbar, edit to your desire.

![lemongpu](https://github.com/lwilletts/radeonvii/blob/master/lemongpu.png)
