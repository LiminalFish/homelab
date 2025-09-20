# Why

I currently have a SuperMicro SYS-6028U-TR. I mostly baught this system because it was fairly cheap and I thought it would be a good chance to get experience with enterprise hardware. The problem is that it just is not very good by modern standards. This system draws a significant amount of power for how much it can actually compute. The workloads that the system will be running will not rely very heavily on multicore performance and many people have been performing said workloads on much weaker systems.

My biggest issue is that since getting the system I have not even been able to set it up. In the README of this project I am much more modest and chalk up my issues to a lack of experience. In reality I am almost certain that the RAID controller in the system is broken. It may not have been broken when the server was shipped to me but it is now. Whenever I enter the RAID controller's BIOS it freezes. This is a real issue that stops any hopes of setting this system. 

## Philosophy

I believe in constsitant, consumer friendly standards; that is not what my SuperMicro server is. My big enterprise server is really cool; I love the redundant hotswap power supplies, I love the hotswap fans, the hotswap drive bays, the IPMI control, the fact that I have 4 usable ethernet ports, and even the dual CPUs. The issue is that, while all of this stuff is cool, I just can't really service or modify this thing. What is the point of this big box if I can't even hack it? You can't swap motherboards and you are locked into a certain PSU.

I cam very new to working with the tech in the server space so maybe there are just reasons that I don't understand. Why does this syetm need it's own proprietary power supply? The power supplies here connect to a power distribution board that then connects to the rest of the system. The cables on the PDB are not standard and will NOT connect to any other motherboard. If I am wrong please let me know but from all of my research this is the conclusion. WHYYYYYYYY??? Is there any reason to do this other than corporate greed? I sure that there are very minor gains to be had by setting up the system this way, and perhaps for the intended market of this product it doesn't really matter. When a business buys a bunch of these servers they barely care how much it cost to keep these things running. They can buy several replacement PSUs and when they want something new they just buy a whole new server, no need to try and hack something new together with their old parts. 

When I face reality I can see that this hardware just is not for me and what I want to achieve. In the furture when I am working for some business running enterprise systems I am sure I will be able to properly appreciate them, but right now I just can't. Perhaps I will one day be able to afford to just buy a server and put my drives in, but right now everything has to be optimized to cost me as little as possible while performing as well as possible.

TL;DR My enterprise server is cool but it is expensive to run and fix, I can't really hack it, and my unit is faulty.

# What

