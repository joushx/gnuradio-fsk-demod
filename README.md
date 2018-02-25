![block](https://i.imgur.com/RHQsBfB.png?1)

This blocks takes a frequency modulated signal, filters out other frequencies, demodulates it, recovers the clock and outputs the result as bit stream

## What is this about?

[Frequency Shift Keying](https://en.wikipedia.org/wiki/Frequency-shift_keying) is a way to transmit information over radio waves. By sending radio waves a bit faster and slower, two states can be encoded that are used of zeros and ones.

## Install

1. Open `fsk-demod.grc` in GNU Rradio Companion
2. Execute the Flowgraph

## Use

The block is now available in the category `GRC Hier Blocks`. 

### Parameters

| Parameter | Unit |Description |
|-----------|------|------------|
| Center frequency | Hz | The frequency around the signal moves up and down |
| Multiplication | 1 | `1`: high frequency = 1, `-1`: high frequency = 0 |
| Sample rate | Hz | The sample rate of the input signal |
| Frequency deviation | Hz | The amount the signal deviated from the center frequency |
