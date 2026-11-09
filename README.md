![MIT Beaver Works — Lincoln Laboratory | School of Engineering](docs/images/mit-beaver-works.png)

# AURA: Automated Undercover Risk & Anomaly Detector

MIT Beaver Works Summer Institute (BWSI) — Basics of ASICs  
Team: OpenLane Odyssey  
Platform: Tiny Tapeout · SKY130

## Project goal

AURA is a compact hardware prototype that monitors eight sensor channels and flags readings that differ significantly from an established baseline. It first learns what typical readings look like during a calibration stage. It then checks new readings against that baseline and raises an alert when a channel deviates enough.

The project explores how a useful anomaly-detection task can be implemented in a small, resource-conscious digital chip rather than relying on a larger general-purpose processor.

## At a glance

- 8 sensor channels with signed 8-bit input samples
- Calibration followed by monitoring to identify unusual readings
- SystemVerilog implementation targeting the SKY130 process through Tiny Tapeout
- Resource-conscious architecture that reuses arithmetic hardware across stages

## Full documentation

Read the full documentation [here](docs/info.md). It covers the architecture, algorithms, hardware interface, implementation, verification, and design limitations.

<img width="306" height="86" alt="image" src="https://github.com/user-attachments/assets/1c6a60ca-4a6b-4fd8-b784-ee0b2df1e1d9" />
