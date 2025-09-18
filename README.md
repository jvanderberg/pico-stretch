# Pico Stretch

This is an RP2350B Dev board that breaks out all 48 GPIO pins.

It follows the original footprint of the RP2040 dev board, but adds 12 pins on each side.

Pinout:

```
1	GPIO0	        64	VBUS
2	GPIO1	        63	VSYS
3	GND	            62	GND
4	GPIO2	        61	3v3
5	GPIO3	        60	3v3_EN
6	GPIO4	        59	ADC_VREF
7	GPIO5	        58	GPIO28
8	GND	            57	GND
9	GPIO6	        56	GPIO27
10	GPIO7	        55	GPIO26
11	GPIO8	        54	RUN
12	GPIO9	        53	GPIO22
13	GND 	        52	GND
14	GPIO10	        51	GPIO21
15	GPIO11	        50	GPIO20
16	GPIO12	        49	GPIO19
17	GPIO13	        48	GPIO18
18	GND	            47	GND
19	GPIO14	        46	GPIO17
20	GPIO15	        45	GPIO16
21	GPIO23	        44	GPIO47/ADC7
22	GPIO24          43	GPIO46/ADC6
23	GPIO25	        42	GPIO45/ADC5
24	GPIO29	        41	GPIO44/ADC4
25	GPIO30	        40	GPIO43/ADC3
26	GPIO31	        39	GPIO42/ADC2
27	GPIO32	        38	GPIO41/ADC1
28	GPIO33	        37	GPIO40/ADC0
29	GPIO34	        36	GPIO39
30	GPIO35	        35	GPIO38
31  GND             34  GND
32  GPIO36          33  GPIO37
```

## Production files for JLCPCB

The production files for JLCPCB are in the 'production' directory.

pico-stretch.zip is the zipped Gerber files.

bom.csv and positions.csv are the Bill of materials and placements files respectively.
