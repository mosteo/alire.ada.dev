---
layout: crate
crate: "virtapu"
authors: []
maintainers: ["fabien.chouteau@gmail.com"]
licenses: ["MIT"]
websites: []
tags: ["nostd", "audio", "synth", "game"]
version: "0.1.1"
short_description: "A virtual Audio Processing Unit to simulate 8-bit era game sounds"
dependencies: [{crate: "hal", version: "^0.1.0"}]
---
# VirtAPU
A virtual Audio Processing Unit to simulate 8-bit era game sounds 

 - 4 voices:
   - Pulse
   - Triangle
   - Noise1 (LFSR 1)
   - Noise2 (LFSR 6)
 - Pulse witdth modulation
 - Decay
 - Frequency sweep
 - Sequencer


