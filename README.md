<!-- ASCII Art Header Animation 24fps -->
```
 ████████╗██╗   ██╗███████╗██████╗     ██╗     ███████╗
 ╚══██╔══╝██║   ██║██╔════╝██╔══██╗    ██║     ██╔════╝
    ██║   ██║   ██║█████╗  ██████╔╝    ██║     █████╗  
    ██║   ██║   ██║██╔══╝  ██╔══██╗    ██║     ██╔══╝  
    ██║   ╚██████╔╝███████╗██║  ██║    ███████╗███████╗
    ╚═╝    ╚═════╝ ╚══════╝╚═╝  ╚═╝    ╚══════╝╚══════╝
                                                        
    ██████╗ ██████╗ ██╗███╗   ██╗ ██████╗███████╗
   ██╔══██╗██╔══██╗██║████╗  ██║██╔════╝██╔════╝
   ██████╔╝██████╔╝██║██╔██╗ ██║██║     █████╗  
   ██╔═══╝ ██╔══██╗██║██║╚██╗██║██║     ██╔══╝  
   ██║     ██║  ██║██║██║ ╚████║╚██████╗███████╗
   ╚═╝     ╚═╝  ╚═╝╚═╝╚═╝  ╚═══╝ ╚═════╝╚══════╝
```

---
# Gleb Shirikov

**Security Researcher · Pentesting · Reverse Engineering · Systems**

I build things, break things, and investigate what happens underneath.

My main interests are:

- Vulnerability Research
- Binary Exploitation
- Reverse Engineering
- Embedded & IoT Security
- Network Protocol Analysis
- Security Tooling
- Low-Level Systems

---

## Selected Work

### `crashbandicoot`
**Pre-authentication security research on Hikvision DVR/NVR**

Independent black-box research targeting a legacy Hikvision DVR/NVR platform based on HiSilicon Hi3531 / ARMv7-A.

Research includes:

- RTSP and HTTP attack-surface analysis
- Pre-authentication memory corruption
- Stack and heap corruption
- Crash analysis and reproducibility
- ARMv7 control-flow investigation
- Firmware analysis
- Custom Python research tooling
- Exploration of potential control-flow primitives

The research distinguishes confirmed denial-of-service findings from exploratory attempts at obtaining code execution.

**Research publication:**  
[DOI: 10.5281/zenodo.22768612](https://doi.org/10.5281/zenodo.22768612)

---

### `tuerlegram`
**Custom Telegram Desktop research fork**

A personal Telegram Desktop fork with an amber CRT / terminal aesthetic and an embedded JavaScript scripting environment.

Features include:

- QuickJS-ng scripting runtime
- Event-driven scripts
- Per-chat script attachment
- Persistent script state
- HTML side panels
- Custom `tg.*` host API
- Message/history automation
- Privacy and power-user features
- Custom desktop client modifications

---

### `rabbitrack-r1-simulator`
**SDL2 simulator for embedded music-player firmware**

A desktop simulator designed to reproduce the Rabbitrack R1 firmware UI without requiring the physical device.

Built around:

- C
- SDL2
- LVGL
- CMake
- miniaudio
- stb_image

The simulator reproduces the 480×320 interface, audio playback, album artwork, waveform visualization, mascot animations and hardware-control input.

It also integrates with Rabbitrack Manager through a local simulator-detection mechanism.

---

### `xiro-benz`
**CS2 tooling / experimentation**

A separate repository containing the `velocity-cs2` project together with tests, documentation and an ImGui-based preview environment.

---

## What I Work With

```text
Security
├── Vulnerability Research
├── Binary Exploitation
├── Reverse Engineering
├── Network Security
├── Embedded / IoT Security
└── Pentesting

Systems
├── C / C++
├── Python
├── Rust
├── ARM
├── Linux
├── Qt
└── SDL2

Research
├── Protocol Analysis
├── Fuzzing
├── Crash Analysis
├── Firmware Analysis
└── Exploit Development
```

## Research

I am particularly interested in the intersection of **security research and low-level systems**:

> protocols → memory corruption → crash analysis → reverse engineering → exploitation

Less dashboards. More reversing, weird protocols, memory corruption, embedded devices and figuring out why something breaks.

My current research work includes the analysis of pre-authentication attack surfaces in embedded network devices and documenting findings as reproducible technical research.

## Publication

**Pre-authentication Security Research on Hikvision DVR/NVR**

DOI: [10.5281/zenodo.22768612](https://doi.org/10.5281/zenodo.22768612)

---

## Projects

- [crashbandicoot](https://github.com/oliviaisntcringe/crashbandicoot)
- [tuerlegram / Telegram Desktop fork](https://github.com/oliviaisntcringe/tdesktop/tree/amber-crt-client)
- [Rabbitrack R1 Simulator](https://github.com/oliviaisntcringe/rabbitrack-r1-simulator)
- [xiro-benz](https://github.com/oliviaisntcringe/xiro-benz)
