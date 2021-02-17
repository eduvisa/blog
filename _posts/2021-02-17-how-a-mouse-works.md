---
layout: post
title:  "How a Mouse Works"
author: briant
categories: [ How It Works, Productivity, Learn Something New ]
image: assets/images/how-a-mouse-works.jpg
featured: false
hidden: false
---

Here’s a question for you, dear reader: what’s roughly elliptical, tactile, and smooth all around that’s connected to your computer? If you’ve haven’t lived under a rock your entire life, the answer should be easy: your trusty computer mouse. Being possibly the most used computer accessory(along with the keyboard), life on the net would be unimaginable without it. Touchpads and touchscreens are certainly useful instruments for human-computer interaction, but they lack the versatility or speed of the small but punctual mouse. Before we dissect and attempt to understand how your computer mouse works, let’s just take a trip through computing history to understand how we got here. 

## Mouse History

Back in 1946, after the end of World War 2, Professor Ralph Benjamin, was working for the British Royal Navy’s technology-related department, and in his work on creating a better tool for targeting aircraft, invented the very first trackball:

![Kenyon Taylor's trackball. It is probable that Prof. Benjamin's trackball looked similar to this one.](https://i.imgur.com/XgaGtEg.png)

A similar trackball invented for Canadian military purposes by Kenyon Taylor, a British electrical engineer. Sadly, no photos of Benjamin’s original invention are available, but this trackball was said to be similar to his.

The trackball used several discs to read motion, two for both the X and Y axes. When someone rolled the ball, the discs at the bottom spun and contacts on the rim of the ball-holding mechanism made connections with the wire, sending brief pulses of output. When the mechanism counted up the number of pulses, the movement could be determined and read. Although the navy decided to stick with utilizing a joystick for targeting, Prof. Benjamin’s creative efforts and invention played a substantial role in the creation of the mouse and the modern trackball. 

The invention of what we would now call the modern mouse dates back to the maverick Douglas Engelbart, an electrical engineer who was employed at NACA Ames Laboratory(which would later be known as NASA.) Right after he was married to his wife, a realization struck him - he had no other goals other than having a steady job and “living happily ever after.” Hence, he then embarked on a self-declared mission on increasing human productivity and hence humanity’s capability on solving the pressing issues of the day. After having read Vannevar Bush’s article “As We May Think”, calling for making global scientific knowledge more widely accessible to the masses, and having remembered his experience as a radar technician during World War II, he then had an epiphany: computers - then behemothic machines prone to failure and overheating - could visually display information in the form of a Graphics User Interface(a GUI), which, as he predicted correctly, would be shrunk down into reasonably-sized displays that would have people whizzing by, transferring and sharing information at breakneck speeds. Then, after completing his PhD at Berkeley and staying as an assistant professor for a year, he left after realizing that he would never achieve his vision there. Hence, he then took up employment at SRI International(then known as the Stanford Research Institute) and began working on dozens of miniaturized electronics in his very own lab, taking in dozens of research assistants. ARPA, the military-scientific research agency of the government, took heed of his discoveries, and supplied him with cash to keep his research going. Eventually, after recruiting a new research team at the Augmentation Research Center, the specialized lab he founded at SRI, he began to design and create the oN-Line System, the very first computer system to possess hypertext links, the mouse, video monitors, window management, and various other precursors to the GUI. 

![](https://i.imgur.com/p3k94R0.png)

The oN-Line System, along with a keyboard and mouse, 1964

![](https://i.imgur.com/9sz7Epl.png)

Doug Englebart at the Community Society Conference

![](https://i.imgur.com/n2EnjkM.png)

Engelbart's mouse

Then, at the ACM/IEEE’s Computer Society Fall Computer Conference, Doug Engelbart and his team spent 90 minutes demonstrating their work on the oN-Line System, featuring editing, text and graphics displayed on a screen, screen videoconferencing, version control, and context-sensitive help at a time when most electrical engineers envisioned computers as nothing more than just titanic beasts that would output reams of data after one would slam a few punch cards into them. But perhaps most relevant and innovative was his computer mouse - which manipulated what he then called the “bug”(or the cursor.) It had two potentiometers on the bottom, which both had wheels orthogonal to each other attached to their shafts. As the mouse was moved across a surface, the wheels move and the potentiometer shaft begins to turn, thus changing the amount of voltage sent, which was interpreted by the computer as motion in the x and y axes. This method of motion interpretation was not too dissimilar to the disks in Prof. Benjamin’s early trackball. Additionally, Engelbart’s mouse had three buttons - right, middle, and left - which is still present in modern mouse design.

![](https://i.imgur.com/hTYPDZJ.png)

The **potentiometer**, a small electrical component that can control the amount of voltage sent via rotation of its shaft.

Hence, the very first pseudo-modern computer mouse came into existence. However, in parallel with Engelbart’s developments, a German company, Telefunken, also designed a different mouse, but with a 3-dimensional mechanism. They decided to invert the trackball so that it would “roll” across the desk and that its movements would be tracked by two friction wheels - hence inventing the very first ball mouse. The company coined it with the name *Rollkugel*. Since then, the ball-mouse design has become common, though it has become relatively less common with the advent of the optical mouse.

![](https://i.imgur.com/C1TwlBZ.png)

The **Rollkugel**, the world’s first ball mouse. Now common, along with the optical mouse.

## Types of Computer Mice

There are a plethora of mouse mechanical designs out there, but the two big ones that you’ll see on a trip to your local technology hardware shop are the mechanical ball mice(though less popular in recent years) and the optical mice. So let’s cover them.

### Mechanical Mouse

![(A tear-down of a mechanical mouse, along with labeled parts(courtesy of me))](https://i.imgur.com/QDTb2DE.png)

Ah, the good old mechanical mouse. I’ve taken a picture of a mechanical mouse and labelled its parts, so let’s learn how all these parts work in tandem to give a mouse its functionality.

1. Moving the mouse moves the **rubber wheel**, which is exposed on the bottom.
2. The **mouse rollers**, positioned at right angles to each other, catch X and Y motion.
3. Each roller is on the same plane **as an small encoder wheel** with jagged edges located in the black boxes. 
4. These edges interrupt the **IR beams** from the lasers(located in the white boxes), generating electrical pulses.
5. Said electrical pulses are shrunk down in current by the **resistors**(so the mouse doesn’t blow up!), and are interpreted by the **microprocessor**.
6. The **microprocessor** analyzes these pulses, and sends a data signal encoding the motion of the mouse.
7. Your computer decodes these data signals and moves your mouse cursor.

All this happens in a matter of a 100 milliseconds or less, which is pretty impressive. Despite this, they suffer from many irritating flaws, including not working on soft or rough edges, and picking up grime on the ball through years of use, which may cause jittering of the cursor. Hence, they have been increasingly replaced in favor of the…

### Optical Mouse

![](https://i.imgur.com/Fs8Txt4.png)



You’ll first notice that the optical mouse contains virtually no moving parts, as compared to his mechanical brethren. They are also far more innovative(and advanced) in interpreting the motion of the mouse - so let’s learn how they work!	Instead of employing a rubber ball and rollers to measure the distance travelled in the X and Y direction, a light from the LED reflects onto the surface and a small, low-resolution camera located underneath the prism takes thousands of pictures of the mouse’s surface - and compares the images to each other by “overlapping” the images and determining the relative offset.

![](https://i.imgur.com/fyJ22i7.png)

(A diagram roughly explaining the process of how the optical mouse compares images to determine distance travelled)

The mice’s processing chip then sends off the encoded distance to the computer, which decodes it and moves the cursor. The right, left, and middle click buttons remain unchanged from the mechanical mouse. Same goes for the scroll wheels in both mice - they use a spring and a potentiometer attached to the wheel which changes voltage, and the computer interprets these changes as motion. In more modern mice, both the mechanical and optical mice might use lasers and an encoder wheel that “interrupts” the laser to send pulses of motion, which is also interpreted as motion by the computer. 

Optical mice are generally preferred by most people, due to its higher resilience because of its lack of moving parts. It also requires relatively less cleaning, and it is more sensitive to motion than a ball mouse because of its use of a highly precise laser. However, the optical mouse does have a few downsides. Its laser means that it uses more electricity, and it cannot work on glossy or transparent surfaces, because those surfaces refract or reflect the laser in such a way that the mouse’s chip is fooled into thinking that the mouse is not moving. Some optical mice developers have made substantial developments and have fixed the glossy surface issue, though.

No matter what kind of mouse you use for your daily computer adventures, be thankful to Prof. Benjamin and Engelbart for their remarkable innovations in the fields of human-computer communication - without it, we might have been stuck with trackpads and scroll balls! 