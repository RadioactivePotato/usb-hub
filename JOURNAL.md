---
title: "krunch's usb-hub"
author: "slack: krunch"
description: "A 4 Port USB 2.0 Hub "
created_at: "2025-07-19"
---

# July 19 - Schematic and Parts (2 hour)

I designed the schematic today, the IC I am using is the [CoreChips SL2.1A](https://lcsc.com/product-detail/USB-HUB-Controllers_CoreChips-SL2-1A_C192893.html), it supports up to 4 extra USB connection.

I also added a diode at 5V input from the USB-A male connector to prevent backpower.

<img width="594" height="484" alt="image" src="https://github.com/user-attachments/assets/aa2d00ed-c1ec-424a-9f93-859bef93a0e7" />

I originally chose a USB-A female connector that have 2 ports, but I realised that might be too heavy and might break the USB port on my laptop.

So I chose one with only 1 port and used 4 of them.

<img width="501" height="411" alt="image" src="https://github.com/user-attachments/assets/068116f7-3d2a-43c8-8dba-f079d2479e6b" />

**Time spent this session: 2 hours**

# July 20 (Morning) - PCB Layout (1.5 hours)

Today I made the PCB layout, I wanted to make it as compact as possible so I decided to put 2 usb ports on each side, and to keep it as short as possible to avoid breaking the laptop's USB port. 

I also wanted to be able to hang this on a keychain/lanyard to I made a plated M3 hole at the end of the USB hub.

<img width="504" height="427" alt="image" src="https://github.com/user-attachments/assets/09df987d-c41e-45a5-b9f9-2899011abb65" />

For the 5V and ground traces, I made them to be 0.8mm thick, which should be fine for 2.5A to 3.5A (1oz copper), which is more than enough for a USB hub.

<img width="686" height="485" alt="image" src="https://github.com/user-attachments/assets/841beb0a-e26c-4383-b201-770a80e5c1c5" />

And I routed most of the ground traces on the back.

<img width="484" height="402" alt="image" src="https://github.com/user-attachments/assets/86b80624-f68e-4ad6-9efd-f8d58d7494b3" />

The traces around the IC is a bit tricky to wire up, but with a few vias it looks good now.

**Time spent this session: 1.5 hours**

# July 20 (Afternoon) - Case (2 hours)

I made the case today, the case is printed in 2 parts, the base and the lid, the lid snaps onto the base with these notches

<img width="693" height="408" alt="image" src="https://github.com/user-attachments/assets/673fb447-b487-43c6-8214-48da95a74ab5" />

<img width="668" height="472" alt="image" src="https://github.com/user-attachments/assets/6aeece41-04f8-486f-974f-2b215d8bb3c3" />

The PCB sits on the edges and the base have a bit of space to allow the through-hole componants to sit on.

<img width="718" height="420" alt="image" src="https://github.com/user-attachments/assets/093e4236-819d-4183-8abd-7e23db1a5eee" />

In the front of the case, the USB male connector will be held together by the lid.

