# laptop-cooling-dock
My laptop tends to get very hot sometimes, so I decided to design a cooling dock that will hopefully help performance under sustained loads and save the battery from further damage.

Whenever I have multiple applications/tasks running, am playing games, or just have been using my laptop for a while, the heat buildup can eventually cause immense throttling of the CPU, and eventually even make the metal shell of the computer too hot to touch. For example, most of the time gaming I can reach 100 FPS; This will plummet to a mere 15 FPS after 20 minutes or so as the heat forces the computer to throttle, loosing up to half its performance. This is a known issue with Macbook Airs(especially since they lack any active or passive cooling systems). 

So here is my solution:

<img width="3296" height="2547" alt="image" src="https://github.com/user-attachments/assets/26c1f564-dd4f-4064-b745-932470988078" />

It addresses a few issues:

1) Heat Transfer 
- Macbook Airs have no cooling system, and even are designed to keep heat confined to the motherboard. While it helps with not burning your hands, it does cause throttling and immense heat buildup over time, which can still leak to the shell of the computer anyway.
- I plan to add thermal pads inside to help transfer heat from the motherboard to the bottom shell of the laptop. It might seem counterintuitive, however with a cooling system, heatsinking to the shell will allow heat to be taken out of the system.

2) Cooling
- My dock uses two Noctua NF-A6x15 5V fans to intake air and blast it against the bottom shell of the laptop, right where the motherboard is the hottest and heat will be localized. It is admittedly a little overkill, but something something the more CFM the merrier or something and two 60mm fans look cool and proportional.
- The fans intake from a large vent at the lower rear of the dock, which ensures most of the air is cold. The outtake vents are small in order to maintain high positive pressure. 

3) Ports
- The newer Macbook Airs notoriously have two USB-C ports and, more recently, a magsafe charging port. While it's not always a huge deal, adapters and dongles aways suck to use when they do become nessecary. I've included a Sabrent USB hub inside the dock that plugs into a USB-C port on the Macbook.
- The hub powers the two fans via two inwards-facing USB-A ports, with a further two facing outwards alongside an HDMI and USB-C port. An ethernet port is also accessible, and a Micro SD card slot as well.

4) Power
- The USB hub is connected to the computer, but powering the fans off the computer battery can cause excess drain as my laptops battery is already at the "service recommended" percentage of battery health.
- I(haven't as of Monday, July 21st) plan on adding space for a powerbank that can either power the USB hub directly, charge the laptop, or power external devices. This adds more functionality to the dock, and can help with prolonging my laptop's battery health.

5) Portability
- Most consumer laptop stands are tall, ugly, and/or expensive. Also, what's with every laptop stand being so tall and/or angled? I don't understand the appeal and find it uncomfortable(when I tested it with placeholder wedges on my laptop).
- The goal of this dock was to be a thin and portable dock, and I'd say I've done a decent job with it. The powerbank also will help with utility when it's not stationed on a home desk. 
