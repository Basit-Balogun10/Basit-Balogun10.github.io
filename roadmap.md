---
title: Roadmap
permalink: /roadmap/
---

# Roadmap

So I'm working through pretty much the whole digital design stack (well, Claude and Gemini both agree the coverage is quite solid... trusting them on that lol, don't know jack yet). Going pillar by pillar, and for each one, breaking it down into its actual components first instead of treating the whole thing as one big black box — build the components, wire it up, then verify it (self-checking testbenches, assertions, coverage, working up to UVM and cocotb), then firmware where it applies.

Here's the list, roughly in the order I'm going through it:

1. Low-speed control — UART, SPI, I2C, I3C
2. High-speed SerDes
3. On-chip bus fabrics
4. Streaming dataflow
5. Memory and caching
6. Hardware compute
7. Display and media
8. System control
9. Processors and debug

Plus the FPGA implementation side and embedded firmware, sitting alongside all of that wherever it's relevant.

## Right now

UART. Register bank, baud generator, shift registers, FSMs, synchronizers, FIFOs, all wired together. First one on the list, so also kind of the first time actually doing any of this for real lol.

Everything past that is just... next, whenever I get there. No fixed timeline, not trying to rush it.

Live builds happen on stream, finished stuff turns into a [write-up](/blog/) eventually, and if you're wondering why any of this exists at all, that's the [about page](/about/).
