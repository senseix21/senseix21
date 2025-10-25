<!-- Profile README: senseix21 -->
<h1 align="center">Mehedi Hasan Ridoy</h1>
<p align="center">
  <b>Rust & Embedded Systems Engineer</b> · no_std · UEFI · Ed25519/BLAKE3 · Real-time Networking (Space/Defense)
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mehedix21">LinkedIn</a> ·
  <a href="mailto:mehedihasanx2118@gmail.com">Email</a> ·
  <a href="https://github.com/senseix21?tab=repositories&q=&type=&language=rust">Rust Repos</a> ·
  <a href="https://nonos.systems">NØNOS</a>
</p>

---

### 👋 About me
I build **reliable low-level software** for hardware that can’t afford to fail—defense/space systems, secure devices, and high-assurance platforms.

- **Boot & Trust:** UEFI/no_std, measured boot, signed capsules, reproducible boot loops  
- **Embedded & RT:** HAL/driver work, interrupts/DMA, Zephyr/FreeRTOS, bounded latency  
- **Mission Comms:** TCP/UDP/QUIC stacks, DNS security, resilient pipelines  
- **Safety by construction:** Memory safety without GC, deterministic behavior, clean FFI to C/C++

I’m a **Producer Member** of the **Rust Foundation’s Safety-Critical Rust Consortium** (coding guidelines & tooling).

---

### 🚀 What I’m working on
- **NØNOS Systems** — no_std **UEFI bootloader** (x86_64-unknown-uefi), cryptographic capsule verification (**Ed25519 + BLAKE3**), kernel bring-up with phased boot logs and a reproducible QEMU/OVMF loop.  
- **VidOxide** — lightweight **real-time video intelligence** toolkit (local-first). Webcam → **FFmpeg → MediaMTX (RTSP) → Frigate (AI detection) → MQTT**, plus a **Rust CLI** & **agent**. One-command Docker stack, examples, docs.

> If your payload, vehicle, or device needs **deterministic, verifiable behavior**, let’s talk.

---

### 🧰 Tech stack (focused)
**Languages:** Rust, C/C++, Go  
**Firmware/Boot:** UEFI, ACPI, TPM/Secure Boot (wiring), no_std  
**Embedded:** Zephyr, FreeRTOS, probe-rs, OpenOCD, dfu-util, ST-Link  
**Networking:** QUIC, TCP/UDP, libp2p, DNS security, MQTT  
**Crypto:** Ed25519, BLAKE3, detached signatures, trust boot paths  
**Dev & Ops:** Docker/Compose, QEMU/OVMF, LLVM/LLD, mold, CI

---

### 🔬 Featured projects

#### 🦀 NØN-OS Boot & Kernel (selected work)
- **no_std UEFI bootloader** with signed capsule verification (Ed25519 + BLAKE3)  
- Phased boot logs → faster iteration & clearer failure modes  
- Reproducible QEMU/OVMF loop for kernel bring-up

#### 🎥 VidOxide — Real-time video intelligence (MIT)
**Repo**
