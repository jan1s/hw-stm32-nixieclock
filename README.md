# hw-nixieclock

The firmware running on the clock: [Firmware](https://github.com/jan1s/fw-clock)

A small Gist to configure a STM32 toolchain on Mac: [Toolchain](https://gist.github.com/jan1s/d2cafa13cdc2b2f5d7b3)

To flash the controller a STM32 Programmer is needed, just get the cheapest one on [Aliexpress][aliexpress].

The host software to configure the clock via serial port: [Host Software](https://github.com/jan1s/cpp-nchron)


## PCBs

The clock has seperate control and display pcbs. Those pcbs do not only form a basic case for the electronics, but also allow for flexible use with different tubes.

[Control PCBs](layout/control)

[Display PCBs](layout/display)

[Source PCBs](layout/source)