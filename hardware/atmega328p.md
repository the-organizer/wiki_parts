 High Performance, Low Power Atmel®AVR® 8-Bit Microcontroller Family
 Advanced RISC Architecture
̶ 131 Powerful Instructions – Most Single Clock Cycle Execution
̶ 32 x 8 General Purpose Working Registers
̶ Fully Static Operation
̶ Up to 20 MIPS Throughput at 20MHz
̶ On-chip 2-cycle Multiplier
 High Endurance Non-volatile Memory Segments
̶ 4/8/16/32KBytes of In-System Self-Programmable Flash program memory
̶ 256/512/512/1KBytes EEPROM
̶ 512/1K/1K/2KBytes Internal SRAM
̶ Write/Erase Cycles: 10,000 Flash/100,000 EEPROM
̶ Data retention: 20 years at 85C/100 years at 25C(1)
̶ Optional Boot Code Section with Independent Lock Bits
 In-System Programming by On-chip Boot Program
 True Read-While-Write Operation
̶ Programming Lock for Software Security
 Atmel® QTouch® library support
̶ Capacitive touch buttons, sliders and wheels
̶ QTouch and QMatrix® acquisition
̶ Up to 64 sense channels
 Peripheral Features
̶ Two 8-bit Timer/Counters with Separate Prescaler and Compare Mode
̶ One 16-bit Timer/Counter with Separate Prescaler, Compare Mode, and
Capture Mode
̶ Real Time Counter with Separate Oscillator
̶ Six PWM Channels
̶ 8-channel 10-bit ADC in TQFP and QFN/MLF package
 Temperature Measurement
̶ 6-channel 10-bit ADC in PDIP Package
 Temperature Measurement
̶ Programmable Serial USART
̶ Master/Slave SPI Serial Interface
̶ Byte-oriented 2-wire Serial Interface (Philips I2
C compatible)
̶ Programmable Watchdog Timer with Separate On-chip Oscillator
̶ On-chip Analog Comparator
̶ Interrupt and Wake-up on Pin Change
ATmega48A/PA/88A/PA/168A/PA/328/P
ATMEL 8-BIT MICROCONTROLLER WITH 4/8/16/32KBYTES
IN-SYSTEM PROGRAMMABLE FLASH
DATASHEET
ATmega48A/PA/88A/PA/168A/PA/328/P [DATASHEET] 2
Atmel-8271J-AVR- ATmega-Datasheet_11/2015
 Special Microcontroller Features
̶ Power-on Reset and Programmable Brown-out Detection
̶ Internal Calibrated Oscillator
̶ External and Internal Interrupt Sources
̶ Six Sleep Modes: Idle, ADC Noise Reduction, Power-save, Power-down, Standby, and Extended Standby
 I/O and Packages
̶ 23 Programmable I/O Lines
̶ 28-pin PDIP, 32-lead TQFP, 28-pad QFN/MLF and 32-pad QFN/MLF
 Operating Voltage:
̶ 1.8 - 5.5V
 Temperature Range:
̶ -40C to 85C
 Speed Grade:
̶ 0 - 4MHz@1.8 - 5.5V, 0 - 10MHz@2.7 - 5.5.V, 0 - 20MHz @ 4.5 - 5.5V
 Power Consumption at 1MHz, 1.8V, 25C
̶ Active Mode: 0.2mA
̶ Power-down Mode: 0.1µA
̶ Power-save Mode: 0.75µA (Including 32kHz RTC)
ATmega48A/PA/88A/PA/168A/PA/328/P [DATASHEET] 3
Atmel-8271J-AVR- ATmega-Datasheet_11/2015
1. Pin Configurations
Figure 1-1. Pinout ATmega48A/PA/88A/PA/168A/PA/328/P
1
2
3
4
5
6
7
8
24
23
22
21
20
19
18
17
(PCINT19/OC2B/INT1) PD3
(PCINT20/XCK/T0) PD4
GND
VCC
GND
VCC
(PCINT6/XTAL1/TOSC1) PB6
(PCINT7/XTAL2/TOSC2) PB7
PC1 (ADC1/PCINT9)
PC0 (ADC0/PCINT8)
ADC7
GND
AREF
ADC6
AVCC
PB5 (SCK/PCINT5)
32
31
30
29
28
27
26
25
9
10
11
12
13
14
15
16
(PCINT21/OC0B/T1) PD5
(PCINT22/OC0A/AIN0) PD6
(PCINT23/AIN1) PD7
(PCINT0/CLKO/ICP1) PB0
(PCINT1/OC1A) PB1
(PCINT2/SS/OC1B) PB2
(PCINT3/OC2A/MOSI) PB3
(PCINT4/MISO) PB4
PD2 (INT0/PCINT18)
PD1 (TXD/PCINT17)
PD0 (RXD/PCINT16)
PC6 (RESET/PCINT14)
PC5 (ADC5/SCL/PCINT13)
PC4 (ADC4/SDA/PCINT12)
PC3 (ADC3/PCINT11)
PC2 (ADC2/PCINT10)
32 TQFP Top View
1
2
3
4
5
6
7
8
9
10
11
12
13
14
28
27
26
25
24
23
22
21
20
19
18
17
16
15
(PCINT14/RESET) PC6
(PCINT16/RXD) PD0
(PCINT17/TXD) PD1
(PCINT18/INT0) PD2
(PCINT19/OC2B/INT1) PD3
(PCINT20/XCK/T0) PD4
VCC
GND
(PCINT6/XTAL1/TOSC1) PB6
(PCINT7/XTAL2/TOSC2) PB7
(PCINT21/OC0B/T1) PD5
(PCINT22/OC0A/AIN0) PD6
(PCINT23/AIN1) PD7
(PCINT0/CLKO/ICP1) PB0
PC5 (ADC5/SCL/PCINT13)
PC4 (ADC4/SDA/PCINT12)
PC3 (ADC3/PCINT11)
PC2 (ADC2/PCINT10)
PC1 (ADC1/PCINT9)
PC0 (ADC0/PCINT8)
GND
AREF
AVCC
PB5 (SCK/PCINT5)
PB4 (MISO/PCINT4)
PB3 (MOSI/OC2A/PCINT3)
PB2 (SS/OC1B/PCINT2)
PB1 (OC1A/PCINT1)
28 PDIP
1
2
3
4
5
6
7
8
24
23
22
21
20
19
18
17
32
31
30
29
28
27
26
25
9
10
11
12
13
14
15
16
32 MLF Top View
(PCINT19/OC2B/INT1) PD3
(PCINT20/XCK/T0) PD4
GND
VCC
GND
VCC
(PCINT6/XTAL1/TOSC1) PB6
(PCINT7/XTAL2/TOSC2) PB7
PC1 (ADC1/PCINT9)
PC0 (ADC0/PCINT8)
ADC7
GND
AREF
ADC6
AVCC
PB5 (SCK/PCINT5)
(PCINT21/OC0B/T1) PD5
(PCINT22/OC0A/AIN0) PD6
(PCINT23/AIN1) PD7
(PCINT0/CLKO/ICP1) PB0
(PCINT1/OC1A) PB1
(PCINT2/SS/OC1B) PB2
(PCINT3/OC2A/MOSI) PB3
(PCINT4/MISO) PB4
PD2 (INT0/PCINT18)
PD1 (TXD/PCINT17)
PD0 (RXD/PCINT16)
PC6 (RESET/PCINT14)
PC5 (ADC5/SCL/PCINT13)
PC4 (ADC4/SDA/PCINT12)
PC3 (ADC3/PCINT11)
PC2 (ADC2/PCINT10)
NOTE: Bottom pad should be soldered to ground.
1
2
3
4
5
6
7
21
20
19
18
17
16
15
28
27
26
25
24
23
22
8
9
10
11
12
13
14
28 MLF Top View
(PCINT19/OC2B/INT1) PD3
(PCINT20/XCK/T0) PD4
VCC
GND
(PCINT6/XTAL1/TOSC1) PB6
(PCINT7/XTAL2/TOSC2) PB7
(PCINT21/OC0B/T1) PD5
(PCINT22/OC0A/AIN0) PD6
(PCINT23/AIN1) PD7
(PCINT0/CLKO/ICP1) PB0
(PCINT1/OC1A) PB1
(PCINT2/SS/OC1B) PB2
(PCINT3/OC2A/MOSI) PB3
(PCINT4/MISO) PB4
PD2 (INT0/PCINT18)
PD1 (TXD/PCINT17)
PD0 (RXD/PCINT16)
PC6 (RESET/PCINT14)
PC5 (ADC5/SCL/PCINT13)
PC4 (ADC4/SDA/PCINT12)
PC3 (ADC3/PCINT11)
PC2 (ADC2/PCINT10)
PC1 (ADC1/PCINT9)
PC0 (ADC0/PCINT8)
GND
AREF
AVCC
PB5 (SCK/PCINT5)
NOTE: Bottom pad should be soldered to ground.
Table 1-1. 32UFBGA - Pinout ATmega48A/48PA/88A/88PA/168A/168PA
1 2 3 4 5 6
A PD2 PD1 PC6 PC4 PC2 PC1
B PD3 PD4 PD0 PC5 PC3 PC0
C GND GND ADC7 GND
D VDD VDD AREF ADC6
E PB6 PD6 PB0 PB2 AVDD PB5
F PB7 PD5 PD7 PB1 PB3 PB4
ATmega48A/PA/88A/PA/168A/PA/328/P [DATASHEET] 4
Atmel-8271J-AVR- ATmega-Datasheet_11/2015
1.1 Pin Descriptions
1.1.1 VCC
Digital supply voltage.
1.1.2 GND
Ground.
1.1.3 Port B (PB7:0) XTAL1/XTAL2/TOSC1/TOSC2
Port B is an 8-bit bi-directional I/O port with internal pull-up resistors (selected for each bit). The Port B output
buffers have symmetrical drive characteristics with both high sink and source capability. As inputs, Port B pins
that are externally pulled low will source current if the pull-up resistors are activated. The Port B pins are tristated
when a reset condition becomes active, even if the clock is not running.
Depending on the clock selection fuse settings, PB6 can be used as input to the inverting Oscillator amplifier
and input to the internal clock operating circuit.
Depending on the clock selection fuse settings, PB7 can be used as output from the inverting Oscillator
amplifier.
If the Internal Calibrated RC Oscillator is used as chip clock source, PB7...6 is used as TOSC2...1 input for the
Asynchronous Timer/Counter2 if the AS2 bit in ASSR is set.
The various special features of Port B are elaborated in ”Alternate Functions of Port B” on page 82 and ”System
Clock and Clock Options” on page 27.
1.1.4 Port C (PC5:0)
Port C is a 7-bit bi-directional I/O port with internal pull-up resistors (selected for each bit). The PC5...0 output
buffers have symmetrical drive characteristics with both high sink and source capability. As inputs, Port C pins
that are externally pulled low will source current if the pull-up resistors are activated. The Port C pins are tristated
when a reset condition becomes active, even if the clock is not running.
1.1.5 PC6/RESET
If the RSTDISBL Fuse is programmed, PC6 is used as an I/O pin. Note that the electrical characteristics of PC6
differ from those of the other pins of Port C.
If the RSTDISBL Fuse is unprogrammed, PC6 is used as a Reset input. A low level on this pin for longer than
the minimum pulse length will generate a Reset, even if the clock is not running. The minimum pulse length is
given in Table 29-11 on page 305. Shorter pulses are not guaranteed to generate a Reset.
The various special features of Port C are elaborated in ”Alternate Functions of Port C” on page 85.|
1.1.6 Port D (PD7:0)
Port D is an 8-bit bi-directional I/O port with internal pull-up resistors (selected for each bit). The Port D output
buffers have symmetrical drive characteristics with both high sink and source capability. As inputs, Port D pins
that are externally pulled low will source current if the pull-up resistors are activated. The Port D pins are tristated
when a reset condition becomes active, even if the clock is not running.
The various special features of Port D are elaborated in ”Alternate Functions of Port D” on page 88.
ATmega48A/PA/88A/PA/168A/PA/328/P [DATASHEET] 5
Atmel-8271J-AVR- ATmega-Datasheet_11/2015
1.1.7 AVCC
AVCC is the supply voltage pin for the A/D Converter, PC3:0, and ADC7:6. It should be externally connected to
VCC, even if the ADC is not used. If the ADC is used, it should be connected to VCC through a low-pass filter.
Note that PC6...4 use digital supply voltage, VCC.
1.1.8 AREF
AREF is the analog reference pin for the A/D Converter.
1.1.9 ADC7:6 (TQFP and QFN/MLF Package Only)
In the TQFP and QFN/MLF package, ADC7:6 serve as analog inputs to the A/D converter. These pins are
powered from the analog supply and serve as 10-bit ADC channels.