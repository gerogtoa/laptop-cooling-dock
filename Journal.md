So full disclosure I highkey didn't realize I needed to submit a journal until July 22nd so most of the stuff is being journalled on the 24th. My "entries" are based off my memory of my thoughts at the time and Onshape's incredibly accurate logging system(which logs EVERYTHING, even stuff as simple as showing/hiding parts down to minute which they happened).

# 7-14 | Determining Requirements

I've finally decided to make a laptop stand after dropping to 10 FPS for the hundreth time or so. Did some research on previous solutions to Macbook Air overheating, and found LLT and Max Tech's videos particularly informative. They both used thermal pads to heatsink the CPU's heat to the metal shell of the laptop. Max went even further by adding a magsafe magnet inside and clipping on a third-party iPhone magsafe fan, which was kinda epic. I want to do something like that too with an active cooling system.

<br>
<p align="center"><img width="940" height="371" alt="image" src="https://github.com/user-attachments/assets/c70720ba-457f-4aaa-b6fd-27d156e17e3d" /></p>
<h6 align="center"><i><small>Max Tech's Magsafe active cooling fan.</small></i></p></h6>
<br>
 
That method would definitely require a stand/housing for everything. I considered a proper heatsink and determined that it probably won't be nessecary given the already impressive performance increase and temperature decrease Max saw with just one baby fan and no proper heatsink as well. I think I will go ahead with two fans, probably from Noctua. A friend reccomended this brand to me and after some research it seems they have some of the best performing fans while also being very quiet, which is pretty cool. I also want to incorperate a USB hub of some kind since Macbook Airs notoriously have negative one ports. Will also need the hub to power the fans off the Macbook. 

So the current requirements are:
- Heatsink to the bottom shell of the laptop
- Use Noctua fans to actively cool the system
- Power the fans off the computer using a USB hub
- Have as many ports of the USB hub accessiable and usable

<br>As for the actual CAD, I made the document and that's about it.

<br>
<img width="2130" height="1712" alt="image" src="https://github.com/user-attachments/assets/fc73bb8a-fd90-4e59-b55c-f230205066eb" />
<h6 align="center"><i><small>And it was all downhill from here.</small></i></p></h6>
<br>

# 7-15 | What the heck

So uh, what the heck were we thinking...??

<img width="3296" height="2547" alt="image" src="https://github.com/user-attachments/assets/4b94b10c-fe0a-4f76-a10d-5082559604e0" />
<h6 align="center"><i><small>What the helly??</small></i></p></h6>
<br>

# 7-16 | Locked In Behavior

Today I decided to lock in and have finally made a kinda style I like. The original idea with the wood top was to match the color pallette of the Noctua fans and also provide a better contact surface for the hot underside of the laptop(since I think it would at the very least warp the 3D printed plastic), and has now been replaced with a bent polycarbonate sheet that I think is pretty cool. 

<img width="3296" height="2547" alt="image" src="https://github.com/user-attachments/assets/dcc88d9e-33b8-41c8-82d7-a7616067694d" />

This currently only supports the back as the angle in theory lines up the front to contact the table as well, so it should be fully supported. However I realized that it would probably be wise to allow more room in the front, since I would actually rather have the usb hub ports near the front instead of all the way at the back. Also I don't think there is enough room for it anyway since I'm trying to keep the width the same as the Macbook itself.

<br>
<p align="center"><img height="350" alt="image" src="https://github.com/user-attachments/assets/c109f87e-c740-497b-b65f-d1dc2f76329d" /> <img height="350" alt="image" src="https://github.com/user-attachments/assets/b69e5273-e9d0-422b-ae11-0b8c4e7e809d" /></p>
<h6 align="center"><i><small>Some genuinely horrific never before seen "surfaces" were created as George attempted to surface model the intake vent for literally no reason at all</small></i></p></h6>
<br>

Eventually, I landed on a nice and simple intake duct, with an extra slot(-ish thing?) to accomodate a grille or dust filter.

<br>
<p align="center"><img width="569" height="263" alt="image" src="https://github.com/user-attachments/assets/f333d138-11f7-42df-8f73-10d11df37ec1" /></p>
<h6 align="center"><i><small>It also proved to be incredibly parametric!</small></i></p></h6>
<br>

I thus began on the outtake ducts. I initally was thinking of ways it could be fuctional yet asthetic at the same time, and decided that having channels exposed on the top of the 3D printed plastic but capped by the polycarb could look super cool. I placed an outtake vent at each side, which I plan on connecting to in some cool fashion.

<br>
<p align="center"><img width="689" height="283" alt="image" src="https://github.com/user-attachments/assets/c1df4611-fcfd-470d-ac39-64b1e2e3f6d4" /></p>
<br>

# 7-17 | Locked Out Behavior

This was truly a traumatic day. I started off by completely redoing the vents for no reason at all which ended up being a huge ugly mess/waste of time that I ended up rolling back anyway.

<br>
<p align="center"><img width="620" height="413" alt="image" src="https://github.com/user-attachments/assets/278b39a9-4808-4e5b-91ec-3979a3202771" /></p>
<h6 align="center"><i><small>Why would he do this?</small></i></p></h6>
<br>

Yeah those were pretty tragic. But what was by far worse than that was my first attempt at the outtake channels...

<br>
<p align="center"><img width="654" alt="image" src="https://github.com/user-attachments/assets/2b23b817-ce6e-4bc3-afbd-d7ee6be5fa5c" /></p>
<h6 align="center"><i><small>Terrible.</small></i></p></h6>
<br>

I eventually moved on to a much more sensible vent/channel design...

<br>
<p align="center"><img width="3296" height="2547" alt="image" src="https://github.com/user-attachments/assets/de1f943c-1bae-4ae5-8c4e-485922795f99" /></p>
<h6 align="center"><i><small>Simplicity is a very beautiful thing! Now with ∞% more fasteners.</small></i></p></h6>
<br>

Another somewhat good outcome was finally getting rid of that dividing line. Since I have an BambuLabs A1 Mini 3D printer, I originally split it to fit on the print bed. But then I realized, I currently have my robotics team's P1S at my house for the summer, so I could just use that. Confirming the viability of a single piece print also essentially locked in the width and height, as literally neither could increase without it going over the print volume constraints.

<br>
<p align="center"><img width="932" height="721" alt="image" src="https://github.com/user-attachments/assets/6a6ea4a0-e2e0-468b-9d00-a80408d31cdd" /></p>
<h6 align="center"><i><small>Yikes...</small></i></p></h6>
<br>

# 7-20 | Adding the USB Hub

With the intake and outtake vent debacles finally sorted out, I started integrating the USB hub. It was actually more challenging to find one than I thought it would be, since a lot of hubs were either too large with too many ports, too small with too little ports, or just right but only having ports on one side; I needed a "double sided" hub since the fans would plug into it as well internally. Eventually a friend reccommended the Sabrent 9 in 1 USB hub which he owned and found to be of high quality. A CAD model also existed in the Onshape public library! Super convenient. However, it did become a challenge to try and package, requiring me to eventually change the size, shape, and angle of the whole dock. Luckily things were pretty parametric and worked out nicely.

<br>
<p align="center"><img width="565" height="338" alt="image" src="https://github.com/user-attachments/assets/b1afdcf0-af79-4710-8f75-c5529c576da0" /></p>
<br>

After some effort, I think I came up with a pretty elegant solution. By flipping the hub upside down, there can be two inwards facing USB A ports to power the fans. On the front, another two USB A ports are present alongside a USB C and HDMI port. Ethernet is accessible on the side.

<br>
<p align="center"><img width="3296" height="2547" alt="image" src="https://github.com/user-attachments/assets/aa122462-623c-4a99-8fea-55970aa7615b" /></p>
<br>

# 7-21 | Internal Routing

Some evil events transpired today. I realized I did not structure my design with internal routing in mind; I started with a billet and subtracted, rather than a hollow shell and added.

<br>
<p align="center"><img width="534" height="470" alt="image" src="https://github.com/user-attachments/assets/0c5b3132-741e-4543-8879-af41a9175b6b" /></p>
<h6 align="center"><i><small>The initial design for the USB A to fan channels.</small></i></p></h6>
<br>

Added the input for the hub from the laptop.

<br>
<p align="center"><img width="534" alt="image" src="https://github.com/user-attachments/assets/d5cf403f-606b-4d2e-9f37-7a6d90f06950" /></p>
<br>

Ended in a nice spot for today. Also somehow managed to squeeze in a top access hole for the inwards facing Micro SD card slot! I think I'm pretty much done, and have started assembling a Bill of Materials! 

<br>
<p align="center"><img width="3296" height="2547" alt="image" src="https://github.com/user-attachments/assets/26c1f564-dd4f-4064-b745-932470988078" /></p>
<h6 align="center"><i><small>Narrator: "He was in fact, nowhere near done..."</small></i></p></h6>
<br>

# 7-23 | Holy Scope Creep

Some friends suggested I add a powerbank, which I think is a super cool and amazing idea. My laptop suffers from abysmal battery health(as a product of the overheating!), so either powering the fans off a powerbank or charging the laptop directly could be pretty awesome.

<br>
<p align="center"><img width="530" height="335" alt="image" src="https://github.com/user-attachments/assets/6ffb3e1c-1b85-4b0c-80d1-2c3f381fdfad" /></p>
<h6 align="center"><i><small>Housing for the iNiu P55-E2 10,000mAh 45W powerbank.</small></i></p></h6>
<br>

I do have a lot of questions of how this whole system would work, though. How would the powerbank power things? I originally wanted it to be able to charge the computer and power the fans through the USB hub, but how would that work if the computer was also meant to power the fans through the hub? If I simply plugged/unplugged the powerbank/laptop depending on which input I desired, then when powered through the powerbank, I would not be able to use the the ports on the hub for data transfer with the computer, which was kind of nessecary if I wanted to have stuff plugged in like a USB A mouse and earbuds simultaneously. I went through dozens of different adapters trying to make this system work, but it was just a huge pain and pretty much impossible without some custom PCB that I am just not ready to design at this point. 

<br>
<p align="center"><img width="2060" height="1468" alt="image" src="https://github.com/user-attachments/assets/638f21ce-882b-4d8a-afa2-a255c6dd0e5e" /></p>
<h6 align="center"><i><small>Wiring diagram for the power flow of the system after realizing it was completely cooked.</small></i></p></h6>
<br>

Eventually after running in circles for literal hours and going nowhere, I finally decided to drop the powerbank idea. I'd imagine the dock will sit at my desk next to my laptop charger most of time anyway, so a portable powerbank would just not be nessecary. Adding a slot to hold one is still on the table for travel.

While talking with a friend on how to approach wiring, I was introduced to the difference between USB 2.0 and Thunderbolt 4, which is, to say the least, a huge difference. It became clear that in order to accommodate Thunderbolt 4 cables(with their thicker wires, beefier connectors, and larger bend radii, etc.), a major redesign of the internal routing would be needed. 

<br>
<p align="center"><img height="450" alt="image" src="https://github.com/user-attachments/assets/6e268dfc-aa5e-4018-bba4-de8f9ccf4800" /><img height="450" alt="image" src="https://github.com/user-attachments/assets/e589e736-ec86-4ecd-abd3-96429830e69d" /></p>
<h6 align="center"><i><small>Before(left) and after(right) of the internal routing redesign. Went through several variations and changes to the actual wires/connectors as well, but main improvements include larger channels, better wiring for the fans, larger bend radii.</small></i></p></h6>
<br>

I've also been absolutely tweaking out over finishing the BOM because of the bent polycarb sheet. When I designed it, I used Onshape's sheet metal model tools, but didn't form the bends properly, and thus the model/.dxf exports were invalid when I uploaded them to quote on SendCutSend. But even before I realized that, the .dxf files were already getting broken for no reason at all either when exported from Onshape or when converted from a .step on SendCutSend's instant quote software. I would have to re-import the .dxf files into Onshape and manually fix them, just for it to again not work because of "unenclosed spaces" when there were zero gaps. I eventually reached out to support and am awaiting a response. 

<br>
<p align="center"><img width="2940" height="1912" alt="image" src="https://github.com/user-attachments/assets/14b3339a-546c-4720-ab84-dde62bafc3d6" /></p>
<h6 align="center"><i><small>Pain. Suffering.</small></i></p></h6>
<br>

That's all for now!

<img width="3296" height="2547" alt="image" src="https://github.com/user-attachments/assets/f189a737-ec12-4811-bc54-c97d85c8ffc4" />


### Future plans:
- Add room for a powerbank that is not hooked up to the rest of the system
- Storage for a mousepad
- Finally realize that the above two bullet points are more scope creeps and will induitably lead to copious amounts of pain and suffering 
