# hw-nixieclock

The firmware running on the clock: [Firmware](https://github.com/jan1s/fw-clock)

A small Gist to configure a STM32 toolchain on Mac: [Toolchain](https://jan1s.github.io)

To flash the controller a STM32 Programmer is needed, just get the cheapest one from China.

## Initial Configuration

Before the clock will actually start working, it is necessary to set the type:

```bash
nixie_settype <type>
nixie_settype <type(0-4)>
```

Where `<type>` is a number defining the nixie clock type.

1. ZM1000
2. Z570M, IN-8
3. ZM1325
4. IN-14, ZM1020

It is also required to set the mode of operation:

```bash
nixie_setmode <mode>
nixie_setmode <mode(0=NONE|1=HHMMSS|2=HHMM|3=MMSS|4=YYYY)>
```

Where `<mode>` is a number defining the nixie operation mode.

1. HH:MM:SS
2. HH:MM
3. MM:SS
4. YYYY

## PCBs

The clock has seperate control and display pcbs. Those pcbs do not only form a basic case for the electronics, but also allow for flexible use with different tubes.

[Control PCBs](layout/control)

[Display PCBs](layout/display)

[Source PCBs](layout/source)

