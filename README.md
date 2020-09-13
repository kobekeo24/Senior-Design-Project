# Senior-Design-Project

TNCMCU
Project Members:

David Cain
Kobe Keopraseuth
Kaleb Leon

Project Mentors:

Nolan E.
Rizwan M.
Nick P.
James P.
Project Description
Current implementations of the Terminal Node Controller use a telephone FSK modem to transmit binary data via the APRS system. These FSK modems are outdated, unavailable, and obsolete. The signals are transmitted at 1200 baud using audio signals of 1200 and 2200 Hz.

Project Challenge
Design, implement, build, and test aTNCwith an STM32 or similar microcontroller. The system must accept a string via UART or a similar interface and generate the necessary APRS and HDLC headers/packet data and then produce the correct audio waveform. This audio waveform will then be fed to a speaker, handheld radio, HAM radio set, or dedicated FM modulator (design team not responsible for this portion, only the audio waveform generation).The system must also accept an audio waveform input from a microphone, handheld radio, HAM radio set, or dedicated FM receiver (design team not responsible for this portion, only the audio waveform interpretation) and be able to translate this audio into APRS/HDLC, and transmit a fully translated message to the controlling device via UART or a similar interface.The initial implementation should use COTS development kits as a proof of concept. Once the software and design have been verified and validated, the hardware shall be implemented into a standalone PCB with connections for a PC, Raspberry PI, Arduino, and standard handheld radio.

The team will have to familiarize themselves with the following:
microcontroller C programming and hardware including:

timers
interrupts
ADC
DAC
various comms interfaces
schematic design and PCB layout

analog circuitry design

APRS, HDLC, and other packet radio standards

responsible software development using thorough verification/validation techniques including:

flowcharting
failure analysis
unit testing
etc.

Repo notes
Not a permanent structures, very flexible!

Documentation - Design and implementation of project

Hardware Specs - Documentation for any hardware used in the project. 

Schematic - Contains schematics of board layout design.

Protocol Documentation - Research papers on information about AX.25/KISS/HDLC/etc.

Software - Current code for Stm32 based TNC.
