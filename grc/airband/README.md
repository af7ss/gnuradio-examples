# GNURadio Companion (GRC) Airband Flowgraph

[Airband](https://en.wikipedia.org/wiki/Airband) (aka Air Band) is a [Very High Frequency](https://en.wikipedia.org/wiki/Very_high_frequency) (VHF) waveform used for communications in civil aviation.

Airband uses [Amplitude Modulation](https://en.wikipedia.org/wiki/Amplitude_modulation) (AM) with a maximum bandwidth of 8.33 kHz (kilo-Hertz). Since it's a double sideband waveform (using both sides of the center frequency equally), the maximum audio frequency is 1/2 of that (i.e., 4.166 kHz).

This flowgraph uses [Waveform Audio File Format](https://en.wikipedia.org/wiki/WAV) (.wav) as its source and transforms it to Airband using a two (2) megasample per second (2Msps) [Open Source Mobile Communications](https://osmocom.org) (osmocom) sink.

The source audio is from [Beethoven's 7th symphony, 2nd movement (Allegretto)](https://en.wikipedia.org/wiki/Symphony_No._7_(Beethoven)#II._Allegretto) obtained from [archive.org](https://archive.org/details/BEETHOVENSymphonyNo.7InAMajorOp.92-NEWTRANSFER/02.Ii.Allegretto.mp3).

