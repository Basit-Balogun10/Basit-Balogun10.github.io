---
title: About
permalink: /about/
---

I'm an software engineer. it's not like I'm trying to stop being one or anything, I'm basically just trying to get more serious with hardware.

Software (application-level... just started looking into systems programming with Rust more recently) has been my home turf for 3-4 years now, so going into chip design, verification, embedded firmware, all of that... I'm pretty much a beginner again. Basically, satisfying my curiousity on the other side of the spectrum, as I've always been dealing with the application layer, and now want to get as close to the bare metal and silicon as possible.

I've already seen what AI can do in this space too. I've done two AI-assisted chip design/verification competitions and actually won one of them, so I know I could probably get pretty far just leaning on AI and "vibing" my way through the whole thing... but I don't really want to do that.

What I want is the same fluency with hardware that I eventually built up with software. I want to get to the point where I understand what's happening well enough that I can confidently build stuff myself, such that I can then get these LLMs vibe through the implementation details for me while I focus on the systems-level/architectural thinking (yea really, part of the whole thing is so that I can get to build much more interesting stuff I have in plans with AI's heavy assistance in the loop). And getting there means actually learning the stuff. Getting stuck on stupid things, going down the wrong path for three hours, finally figuring it out, and then wondering how I ever didn't understand it.

And that process is exactly what happens on my streams. Although, if I'm being honest, I didn't really plan to stream lol. Just felt the urge to do so on a Friday morning (I had just gotten started with a UART's register bank) and thought "Oh well, I'll just take this thing online". I also had some vague idea that maybe I'd get more done if people were watching, but mostly I think I was just excited about the whole thing and wanted to share it. I mean it's just me on the stream, nobody is really watching (yet) lol.

In another light, it gives the whole thing a bit of a purpose beyond just sitting and learning hardware. I've never really been the one to "build in public" (as it's commonly said) but that's literally what this is turning into lol. The stream is me actually learning the stuff, but then when something is finished, it can turn into a proper project walkthrough, a write-up, a recap post etc. and eventually feed into whatever I'm building next.

That whole loop has started to become how I want to build a presence online anyway (I actually usually do think to myself how I'd ever bring my personality online anyways) rather than trying to sit down and figure out what my "content strategy" is supposed to be.

And the way I'm learning hardware is basically the same way I learned software.

I'd watch some real tutorial (Brad from Traversy Media and many others who ran just so folks like me could walk lol), read some blog/docs (well not so much in my early days), start building something, get completely stuck, search for the exact error or weird behaviour I was seeing on Google, and eventually find some Stack Overflow post from 2014 (or even beyond, as we all know lol) where someone had already suffered through exactly the same thing.

I'm doing the same thing here, except AI is now sitting in that "search the internet and hope someone has already answered this" slot (ugh... 'cause why not? Plus they're pretty smart too).

To be clear, I don't mean having it spit out the RTL, testbenches etc that I don't understand. I'm using it more like a really patient research partner. If I don't understand why a synchronizer is built a certain way, or why some part of a bus protocol behaves the way it does, I can just keep asking questions until I actually understand it. I actually do rely more on getting a broad overview of whatever it is I'm working on is about (like a 5-10 youtube), get the big picture, and then have the AI decompose it into components/sub-components and outline precisely specific actions they do, how they interface with other components. And then also get a well comprehensive design spec and vplan, so I get to focus having myself on translating all of that into code (well, implementing the hardware) - because that's the bit I'm interested in; getting the fluency.

So I'm working through pretty much the whole digital design stack (well Claude and Gemini both agree the coverage is quite solid... trusting them on that lol, don't know jack yet). Starting with the relatively low-speed control stuff - UART, SPI, I2C, I3C - then getting into things like SerDes, on-chip buses, streaming dataflow, memory and caching, hardware compute, display and media, system control, processors, debug... plus the FPGA and embedded firmware side that sits around all of that.

And I'm trying not to treat those things as magic black boxes. If I'm building a UART, for example, merely understanding that it's two wires TX and RX, no clock, serial communication, can be full-duplex etc isn't enough (for real I can barely translate any of those facts into RTL lol). I want to understand that underneath it you've got a register bank, a baud generator, shift registers, FSMs, synchronizers, FIFOs, and all these little pieces that have to fit together correctly. Then you build the thing, verify it, and eventually write the firmware that actually talks to it.

Worth mentioning precisely that the whole thing is really about learning. For example, for verification, I plan on m working my way through self-checking testbenches, assertions, coverage, and eventually UVM and cocotb. For an actual project, could some of these be regarded as being redundant? Maybe but I'm just trying to get familiar with various means/tools for learning sake.

Another thing I'm conscious of is that I'm actually not starting from absolute zero, and curious to see how much is transferrable from my SWE background into this new domain.

I don't really know where this is heading to or where or whn it's going to end yet. That's kind of the fun part (well, I do have some interesting projects in mind to work on or maybe I dwell into more unfamiliar territories like analog design, embedded hardware/pcb design/electronics and the likes). I just know I'm having a lot of fun being new and confused at something again.
