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
|Item                               |Description                                                                        |Vendor     |Cost  |Quantity|Total |Link                                                |
|-----------------------------------|-----------------------------------------------------------------------------------|-----------|------|--------|------|----------------------------------------------------|
|Adhesive Cork Sheet 2500x200x1mm   |To cover the bottom and top to prevent sliding                                     |Amazon     |$0.99 |1       |$0.99 |https://www.aliexpress.us/item/3256806952165170.html|
|Dust Filter 300x1000mm             |To filter intake air of dust                                                       |Aliexpress |$0.99 |1       |$0.99 |https://www.aliexpress.us/item/3256809080527961.html|
|M4x12mm Ultra-Low Profile SHCS 20pc|To fasten the polycarb cover and USB hub cover to the body                         |Aliexpress |$0.99 |1       |$0.99 |https://www.aliexpress.us/item/3256806833766304.html|
|M4x25mm Ultra-Low Profile SHCS 20pc|To secure the fans to the body                                                     |Aliexpress |$0.99 |1       |$0.99 |https://www.aliexpress.us/item/3256806833766304.html|
|100x100x1.5mm thermal pad          |To heatsink the CPU to the shell of the computer                                   |Aliexpress |$0.99 |2       |$1.98 |https://www.aliexpress.us/item/3256808001308645.html|
|Noctua NF-A6x15 5V                 |To intake air to cool the bottom shell of the laptop                               |Amazon     |$15.95|2       |$31.90|https://a.co/d/2aiRH9k                              |
|M4 Nylock Nuts 100pc               |For general fastening                                                              |Aliexpress |$0.99 |1       |$0.99 |https://www.aliexpress.us/item/2251832612458814.html|
|Polycarb Cover                     |To interface the laptop shell with the body so it won't melt the 3D printed plastic|SendCutSend|$47.93|1       |$47.93|https://cart.sendcutsend.com/2ysmf3tukrza           |
|USB fan splitter 2 - Dual Fan      |To connect the two fans to one USB A port                                          |Amazon     |$8.95 |1       |$8.95 |https://a.co/d/iWLsJlx                              |
|                                   |                                                                                   |           |      |Total:  |$95.71|                                                    |

BOM Last Updated: 7-27
