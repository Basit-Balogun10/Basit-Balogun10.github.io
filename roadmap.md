---
title: Roadmap
permalink: /roadmap/
---

# Roadmap

So I'm working through pretty much the whole digital design stack (well, Claude and Gemini both agree the coverage is quite solid... trusting them on that lol, don't know jack yet). Going pillar by pillar, and for each one, breaking it down into its actual components first instead of treating the whole thing as one big black box - build the components, wire it up, then verify it (self-checking testbenches, assertions, coverage, working up to UVM and cocotb), then firmware where it applies.

Here's the list, roughly in the order I'm going through it:

1. Low-speed control - UART, SPI, I2C, I3C
2. High-speed SerDes - 8b/10b encoding, 10G Ethernet MAC/PCS, PCIe endpoint, USB3 PIPE
3. On-chip bus fabrics - AXI4-Lite slave, AXI4 multi-master interconnect, APB/AHB bridges, TileLink
4. Streaming dataflow - AXI4-Stream skid buffer, scatter-gather DMA
5. Memory and caching - async CDC FIFO, SRAM/SDRAM controller, DDR4 PHY, L1/L2 cache (MESI)
6. Hardware compute - AES-128, SHA-256, pipelined FIR filter, systolic NPU engine
7. Display and media - VGA pattern/text engine, HDMI 2.0 framebuffer, MIPI CSI-2 camera ISP
8. System control - timers, PWM core, NVIC/PLIC interrupt controller, clock gating units
9. Processors and debug - RV32I pipelined CPU core, JTAG TAP controller, hardware breakpoints

And for each core, there are two branches: an ASIC path (synthesis, place and route, all the way to a real GDSII) and an FPGA path (down to an actual bitstream) - plus firmware, wherever a core actually needs something driving it from software.

## Right now

UART. Register bank, baud generator, shift registers, FSMs, synchronizers, FIFOs, all wired together. First one on the list, so also kind of the first time actually doing any of this for real lol.

Live builds happen on stream ([Twitch](https://www.twitch.tv/basitbalogun10) and [YT](https://www.youtube.com/@basitbalogun10)), finished stuff turns into a [write-up](/blog/) eventually (and maybe a walkthrough video on YouTube as well), the actual code lives in the [repo](/digital-soc-eng/), and if you're wondering why any of this exists at all, that's the [about page](/about/).
