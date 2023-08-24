# My Pico C SDK libraries

## Warning
I have no idea what I am doing.

## Contents

### pico_sleep_utility
Utility to help put the pico into deep sleep and wake up when either of two GPIOs is high. Useful if you have an external RTC and a button. Requires the pico extra stuff.

### pico_sht45
Very basic support for the SHT45, can just run the measure command.

### pico_sgp40
Ported code from Paul Clark @ SparkFun Electronics to work on the pico.

### pico_pcf8523
Library for the PCF8523 RTC. Just supports my use cases (Read & Write time, alarm & countdown timer, interrupts to wake up my board).

### pico_ntp_sync
Syncs the local RTC of the pico with the network time.
