# laptop-cooling-dock
My laptop tends to get very hot sometimes, so I decided to design a cooling dock that will hopefully help performance under sustained loads and save the battery from further damage.

Whenever I have multiple applications/tasks running, am playing games, or just have been using my laptop for a while, the heat buildup can eventually cause immense throttling of the CPU, and eventually even make the metal shell of the computer too hot to touch. For example, most of the time gaming I can reach 100 FPS; This will plummet to a mere 15 FPS after 20 minutes or so as the heat forces the computer to throttle, loosing up to half its performance. This is a known issue with Macbook Airs(especially since they lack any active or passive cooling systems). 

So here is my solution:

<img width="3296" height="2547" alt="image" src="https://github.com/user-attachments/assets/26c1f564-dd4f-4064-b745-932470988078" />

It addresses a few issues:

###  Heat Transfer 
- Macbook Airs have no cooling system, and even are designed to keep heat confined to the motherboard. While it helps with not burning your hands, it does cause throttling and immense heat buildup over time, which can still leak to the shell of the computer anyway.
- I plan to add thermal pads inside to help transfer heat from the motherboard to the bottom shell of the laptop. It might seem counterintuitive, however with a cooling system, heatsinking to the shell will allow heat to be taken out of the laptop.

###  Cooling
- My dock uses two Noctua NF-A6x15 5V fans to intake air and blast it against the bottom shell of the laptop, right where the motherboard is the hottest and heat will be localized. It is admittedly a little overkill, but something something the more CFM the merrier or something and two 60mm fans look cool and proportional.
- The fans intake from a large vent at the lower rear of the dock, which ensures most of the air is cold. The outtake vents are small in order to maintain high positive pressure. 

###  Ports
- The newer Macbook Airs notoriously have two USB-C ports and, more recently, a magsafe charging port. While it's not always a huge deal, adapters and dongles aways suck to use when they do become nessecary. I've included a Sabrent USB hub inside the dock that plugs into a USB-C port on the Macbook.
- The hub powers the two fans via two inwards-facing USB-A ports, with a further two facing outwards alongside an HDMI and USB-C port. An ethernet port is also accessible, and a Micro SD card slot as well.

###  User Experience
- Most consumer laptop stands are tall, ugly, and/or expensive. Also, what's with every laptop stand being so tall and/or angled? I don't understand the appeal and find it uncomfortable(when I tested it with placeholder wedges on my laptop).
- The goal of this dock was to be a thin and portable dock, and I'd say I've done a decent job with it. 

## Bill of Materials
|Item                           |Description                                                                                                                    |Vendor       |Cost  |Quantity|Total  |Link                               |
|-------------------------------|-------------------------------------------------------------------------------------------------------------------------------|-------------|------|--------|-------|-----------------------------------|
|Adhesive Cork Sheet 15.7x19.7" |To cover the bottom and prevent sliding                                                                                        |Amazon       |$9.99 |1       |$9.99  |https://a.co/d/iCnySqv             |
|Sabrent USB Hub 9 in 1         |To power the fans using the laptop as a source, as well as add ethernet, additional USB A and C ports, and a micro SD card slot|Amazon       |$49.99|1       |$49.99 |https://a.co/d/fTbal9V             |
|Dust Filter 400x300mm          |To filter intake air of dust                                                                                                   |Amazon       |$8.99 |1       |$8.99  |https://a.co/d/0loqiyE             |
|M4x12mm BHCS 100pc             |To fasten the polycarb cover and USB hub cover to the body                                                                     |McMaster-Carr|$12.58|1       |$12.58 |https://www.mcmaster.com/91239a148/|
|M4x25mm Low Profile SHCS 25pc  |To secure the fans to the body                                                                                                 |McMaster-Carr|$9.37 |1       |$9.37  |https://www.mcmaster.com/93070A109/|
|100x100x1.5mm thermal pad      |To heatsink the CPU to the shell of the computer                                                                               |Amazon       |$9.99 |1       |$9.99  |https://a.co/d/asofRSC             |
|Noctua NF-A6x15 5V             |To intake air to cool the bottom shell of the laptop                                                                           |Amazon       |$15.95|2       |$31.90 |https://a.co/d/2aiRH9k             |
|Thunderbolt 4 USB C 1.6FT Cable|To get power from the laptop to distribute to the USB hub                                                                      |Amazon       |$14.90|1       |$14.90 |https://a.co/d/geJOPQc             |
|M4x0.7mm 120 pack Nylock Nuts  |For general fastening                                                                                                          |Amazon       |$6.99 |1       |$6.99  |https://a.co/d/bJx2qE7             |
|Polycarb Cover                 |To interface the laptop shell with the body so it won't melt the 3D printed plastic                                            |SendCutSend  |QUOTE |1       |QUOTE  |LINK QUOTE                         |
|                               |                                                                                                                               |             |      |Total:  |$147.71|                                   |

BOM Last Updated: 7-22
