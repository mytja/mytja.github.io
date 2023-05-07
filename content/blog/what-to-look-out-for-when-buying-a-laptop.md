+++
author = "Mitja Ševerkar"
title = "What to look out for when buying a laptop"
date = "2023-05-07"
description = "Everyone makes mistakes, with this guide most mistakes can be avoided."
tags = [
    "laptop",
    "specs",
]
+++

**WARNING:** These are only guidelines, based on my experiences. It might not fit everyone's needs, but for most people, it does the trick.

**DON'T BUY CHROMEBOOKS. THEY ARE PURE GARBAGE.**

# CPU

Preferably get a relatively modern CPU (max 3 generations old), for example as of time of writing this, the latest AMD generation is 7th gen (Ryzen 7000), and for Intel it's 13th gen (Core 13xxx), therefore, your preferred CPU should be AMD Ryzen 4000 and above or Intel Core 10000. This ensures longevity of your laptop.

You should target for medium to high ground laptop CPUs. I found out, that Ryzen 5 and Intel Core i5 are great for their price, though Ryzen 7 and Intel Core i7 are also worth looking at.

Avoid especially all laptops that come with ancient processors and those that come with Intel Celeron or low-end AMD processors. These are very very low-end CPUs and can't do much more than basic browsing.

# GPU

Integrated graphics (Intel Iris Xe, AMD Radeon Vega) will do, except if you're an extreme gamer (which I'm not). You can save a lot of money on integrated graphics.

# RAM

Get at least 16GB or buy a laptop with less RAM, but that is upgradeable to at least 16GB of RAM in the future. You'll need it, trust me.

**NOT ALL LAPTOPS SUPPORT UPGRADING TO 16GB. LOOK CLOSELY AT THE SPECIFICATION SHEET FOR YOUR LAPTOP MODEL (EXACT MODEL NUMBER).**

# SSD

**Don't cheap out and get a hard drive (HDD).**

SSDs are getting cheaper and cheaper every single day, therefore it's worth considering buying a laptop with a SSD, especially for the kind of performance you're gaining with them. Make sure you're getting at least 512GB (or 1TB if you have some money to spare) if you're going to single boot (boot one operating system) and at least a terabyte of storage if you're going to boot two operating systems (eg. Windows and Linux).

It's also recommended for your laptop to have another M.2 or SATA slot for having two disks in the same laptop.

# Display

Don't cheap out and make the same mistake as I did with a TN panel. **AVOID TN AT ALL COSTS. IT HAS VERY POOR VIEWING ANGLES.** Go for an IPS panel or an OLED panel.

# Audio card

All audio cards should do the trick, except for Realtek ones. **Realtek audio cards are utter garbage.** Yes, they are cheap, but what you're getting is the shittiest sound in the entire world. External microphone is barely hearable on my laptop because of the Realtek card. If I plug in a USB sound card, the situation massively improves. Shame on you, Realtek.

# Network card

**DON'T BUY REALTEK NETWORK CARDS. THEY ARE UTTER GARBAGE WITH VIRTUALLY ZERO SUPPORT.** WiFi connection randomly drops if you're using Realtek NIC on Linux, because Realtek doesn't provide us with actually functional drivers. You have to opt-in in a [third party driver](https://github.com/lwfinger/rtw88) to improve the situation, but not make it perfect.

You'd be better if you bought an Intel NIC (highly recommended, due to great support for all platforms, including Linux) or a Qualcomm NIC or literally anything else.

# OS

**Don't install Windows 11.** It lags so bad even on modern hardware.

Install Windows 10 or a Linux distribution (I recommend [Fedora Linux](https://fedoraproject.org/)).
