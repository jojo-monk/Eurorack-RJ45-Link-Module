# Eurorack-RJ45-Link-Module
Eurorack RJ45 Link Module (Passive)

# 🔌 Eurorack RJ45 Link Module (Passive)

A simple passive Eurorack module that allows you to route up to **8 analog signals** through a single **RJ45 (Ethernet) cable**.

## ✨ Features

- 8 independent signal channels
- Passive design (no power required)
- Uses standard RJ45 / Ethernet cables (Cat5e, Cat6…)
- Compact and easy to build
- Perfect for:
  - Case-to-case signal routing
  - Reducing cable clutter
  - Live performance setups

## 🧠 Concept

This module is essentially a **breakout**:

- Front panel: 8 jack inputs/outputs  
- Rear: RJ45 connector  
- Each jack is directly wired to one conductor of the Ethernet cable  

⚠️ No buffering, attenuation, or protection is included — signals are passed **as-is**.

## 📦 Hardware

### Required components

- 1 × RJ45 connector (through-hole or PCB mount)
- 8 × 3.5mm mono jacks (Thonkiconn or similar)
- PCB (provided in this repo)
- Front panel
- Passive wiring only (no ICs)

### Optional

- Shielded RJ45 connector
- ESD protection (if you want to improve robustness)


## ⚠️ Important Notes

- Eurorack signals can range typically from **-10V to +10V**
- Ethernet cables are not designed for analog modular signals:
  - Possible crosstalk
  - Noise over long distances
- Keep cable lengths reasonable (recommended < 5–10m)

🚫 **Do NOT connect this to network equipment** (switches, routers, computers)

## 🛠️ Build Instructions

1. Solder the RJ45 connector to the PCB  
2. Solder the 3.5mm jacks  
3. Mount the PCB to the front panel  
4. Verify continuity for all 8 channels  
5. Test with low-level signals first  

## 🧪 Usage

Use two identical modules: [Synth Case A] ── RJ45 Cable ── [Synth Case B]

✅ Tested and fully functional
