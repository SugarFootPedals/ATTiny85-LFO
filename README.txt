This board uses an ATTiny85 to Generate Low Frequncy Oscillations
and can output either a Sinewave, Ramp Up, Ramp Down or Triangle Wave by adjusting VR2.
VR1 varies the Frequency.

Two signal outputs are available : the PWM output and/or a filtered Waveform LFO signal.

LED indicates the speed (and to a certain extent) the type of waveform.

Included is the Sketch to be uploaded to the Attiny85, using the Arduino IDE. 
It was taken from (and renamed for clarity) the open source "Arduino Component Sketches-master" folder, subtitled "ACS-85 ATTiny85 sketches" code written by Rob Stave .

A schematic is included, but the component reference numbers may be different from what is acually on the circuit board, however the drawing is otherwise accurate.

The Circuit Board is verified and working.

Do Not use voltages above +10vDC because the tiny Voltage Regulator
will fail otherwise. a +9 volt battery is sufficient !
