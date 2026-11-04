<div align="center">

# ⚡ Mikhail (`@MikhaelCat`)
### Systems Engineer • Rust Developer • AppSec & DevSecOps

```text
╭────────────────────────────────────────────────────────────────────────────╮
│  user@box:~# whoami --verbose                                              │
│  OS: Linux x86_64                                                          │
│  Core: Rust (Systems, Linux Drivers, eBPF & Low-Level Observability)       │
│  Security: Binary Exploitation, Reverse Engineering, CTF, DevSecOps        │
│  Track Record: T-Bank Engineering Intensives & Hackathons                  │
╰────────────────────────────────────────────────────────────────────────────╯
```

[![GitHub Stars](https://img.shields.io/github/stars/MikhaelCat?style=flat-square&color=ffb86c&labelColor=1e1e2e&logo=github)](https://github.com/MikhaelCat)
[![eBPF](https://img.shields.io/badge/eBPF-nullca-38bdf8?style=flat-square&labelColor=1e1e2e&logo=linux)](https://github.com/MikhaelCat/nullca)
[![CTF Writeups](https://img.shields.io/badge/THEM%3F!%20CTF-16%2F16%20Solved-50fa7b?style=flat-square&labelColor=1e1e2e&logo=target)](https://github.com/MikhaelCat/THEM-CTF_2026-writeups)
[![Rust](https://img.shields.io/badge/Rust-Systems%20%26%20Drivers-f75c7e?style=flat-square&labelColor=1e1e2e&logo=rust)](https://github.com/MikhaelCat/r-rgb)
[![Open Source](https://img.shields.io/badge/Open%20Source-MIT%20%7C%20GPL-8be9fd?style=flat-square&labelColor=1e1e2e)](https://github.com/MikhaelCat)

</div>

---

### 🚀 Flagship Projects

| Project | Architecture & Stack | Key Metrics & Highlights |
| :--- | :--- | :--- |
| **[⚡ nullca](https://github.com/MikhaelCat/nullca)** | **Zero-CA eBPF Plaintext TLS, HTTP/2, HTTP/3, WebSocket, gRPC, Redis & SQL Inspector**<br>`Rust` • `eBPF Uprobes` • `HTTP/3 RFC 9114` • `DNS & DoH` • `SSE & AI Tokens` • `JWT Auditor` • `Postman v2.1.0` • `QPACK RFC 9204` • `GraphQL AST` • `BOLA/IDOR Engine` • `Fuzzer` • `Web Cockpit` • `AArch64 / AMD64` | • Intercepts plaintext TLS memory (`SSL_read`, `SSL_write`, GnuTLS, NSS, Go `crypto/tls`) with **zero Root CA**<br>• Automated **OpenAPI 3.0.3 & Postman Collection v2.1.0 Generators**, **GraphQL AST Synthesizer**, **BOLA/IDOR detector**, transparent stream decompressor (Brotli RFC 7932 / Gzip / Deflate / RFC 7692 WS)<br>• **RFC 9114 HTTP/3 & QUIC varint codec**, **RFC 1035 / 8484 DNS & DoH wire dissector**, **RFC 8895 SSE & AI streaming token extractor** (OpenAI / Claude / Ollama)<br>• **Zero-dependency JWT Cryptographic Auditor & Dictionary Cracker** (CVE-2015-9235 `alg: none`, RFC 2104 HMAC-SHA256 offline cracking, expiration audit)<br>• **Wireshark Decryption Secrets Block (DSB, type 0x0000000A)** for native zero-config TLS decryption, real **4-tuple TCP socket resolver** (`/proc/<pid>/net/tcp`), memory-bounded LRU stream reassembler (RFC 7230 §3.3.3 EOF)<br>• **Embedded Web Cockpit Daemon** (`nullca web`), Terminal Cockpit with **Vim mode (`:`) & search (`/`)**, real-time **Throughput Sparkline**, parameter **Fuzzing engine** (`nullca fuzz`)<br>• Live network TLS endpoint dissector (`nullca inspect-cert google.com:443`), CSR (PKCS#10) & CRL revocation support<br>• `nullca run -- <cmd>` spawn-tracer, Redis RESP / SQL / SMTP dissectors, side-by-side **Myers Diff Engine (`[d]`)**, live **Request Replayer (`[r]`)**<br>• Comprehensive documentation suite in **[`docs/`](https://github.com/MikhaelCat/nullca/tree/main/docs)** (Architecture, eBPF Engine, Protocols, CLI Reference, Security Audit) |
| **[⚡ r-rgb](https://github.com/MikhaelCat/r-rgb)** | **High-Performance Linux Driver & Native GUI**<br>`Rust` • `GTK4 / Libadwaita` • `Linux hidraw/sysfs` | • Direct hardware offloading to keyboard MCU with **0% background host CPU**<br>• **~3.6µs** scene synthesis, 50 hardware presets, live audio visualizer<br>• Stress-tested for 20,000 cycles with AddressSanitizer and `cargo audit` (0 vulns) |
| **[🚩 THEM-CTF_2026](https://github.com/MikhaelCat/THEM-CTF_2026-writeups)** | **Security Research & Offensive Exploitation**<br>`Pwn` • `Reversing` • `Web & Firmware` • `Crypto` | • 16 comprehensive bilingual (EN/RU) writeups & exploit PoCs<br>• Virtualized Lua VM deobfuscation, stripped Rust reversing, Android APK analysis<br>• Custom x86_64 shellcoding, embedded router injection, PRNG cryptanalysis |
| **[🧭 vibecode](https://github.com/MikhaelCat/vibecode)** | **Autonomous Agentic Travel Engine**<br>`Rust` • `Axum` • `SQLite` • `SSE` • `Leaflet` | • Autonomous LLM agent with strict guardrails against prompt injection and off-topic leaks<br>• 18-rule spatial geo-validation engine (V01–V18) preventing route hallucinations<br>• Asynchronous parallel ingestion pipeline from OSM, weather, and Wikipedia |
| **[🌊 PPS-submarine](https://github.com/MikhaelCat/PPS-submarine)** | **Robotics & Physics Simulator**<br>`C#` • `Unity` • `UDP Sockets` • `JSON API` | • 3D Autonomous Underwater Vehicle (AUV) dynamics simulation<br>• Decoupled network model: high-rate telemetry stream (8081) & command API (8080) |
| **[🎮 Mindustry Tooling](https://github.com/MikhaelCat?tab=repositories&q=mindustry)** | **Game Networking & Custom Shaders**<br>`Java` • `JavaScript (Rhino)` | • **[Scheme-Zize](https://github.com/MikhaelCat/Scheme-Zize):** 512×512 schematics & crash-safe dedicated server RPC<br>• **[unit-table](https://github.com/MikhaelCat/unit-table):** Compact real-time battle HUD with zero draw-tick overhead<br>• **[CanvasForge](https://github.com/MikhaelCat/CanvasForge):** Bayer & Floyd–Steinberg dithering pixel-art compiler |

---

### 🛡️ Security & Systems Research Arsenal

Hands-on experience across low-level kernel tracing, competitive CTF challenges, and application defense:

* **Kernel & eBPF Observability:**
  * Zero-copy kernel tracing via Linux `tracefs`, BPF ring buffers, and multi-stream HTTP/2 session multiplexing.
  * Direct 64-bit ELF parsing (`.dynsym`, `.symtab`, `.strtab`) and Go runtime `.gopclntab` symbol resolution in stripped binaries.
  * Register-level ABI hooking (System V AMD64 and Go ABIInternal register conventions).
* **Binary Exploitation & Reversing:**
  * Bytecode virtualization & custom VM architecture analysis (`last_dance`).
  * Disassembly of stripped native Rust binaries (`crabbymonty.exe`), Windows PE entropy analysis, and ELF checkers.
  * Shellcoding under memory constraints (`Baby Shellcode`).
  * Android APK decompilation and client-side validation tampering (`Good9`).
* **Web, Firmware & Embedded Security:**
  * Reverse-engineering proprietary USB HID communication protocols via Wireshark and Linux `ioctl`.
  * Embedded device web interface exploitation: authentication bypass, command injection, and state pollution (`A Cute Magical Router Gateway`).
* **DevSecOps & Memory Safety:**
  * Pure memory-safe systems development with zero-overhead abstractions in Rust.
  * Integration of automated static analysis, fuzzing, and CI sanitizers.

---

### 🛠️ Technical Stack

```text
Languages     ::  Rust (Primary), C, C#, Java, JavaScript (Node/Rhino), Python, Bash, Lua
Low-Level/OS  ::  Linux eBPF / Uprobes, sysfs / hidraw ioctl, POSIX Sockets, x86_64 ASM, Memory Models
Backends/Web  ::  Axum, REST, Server-Sent Events (SSE), SQLite, GTK4, Libadwaita
Protocols     ::  TLS, HTTP/1.1, HTTP/2 (HPACK), gRPC, Raw TCP/UDP Sockets, PCAP-NG
Security Tool ::  Ghidra, IDA Pro, Binary Ninja, GDB (GEF/pwndbg), pwntools, Burp Suite, Wireshark, JADX
DevOps/CI     ::  Git, GitHub Actions, Docker, Criterion.rs, AddressSanitizer (ASan)
```

---

### 🎓 Engineering Programs & Intensives

* **T-Bank Engineering & Security Bootcamps / Hackathons:**
  * End-to-end service design, backend microservices architecture, and high-intensity hackathon sprints.
  * Implementation of defense-in-depth principles: input sanitization, tokenization, and LLM-agent security guardrails.

---

<div align="center">

### 📊 GitHub Activity & Metrics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=MikhaelCat&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117" alt="MikhaelCat's GitHub stats" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MikhaelCat&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117" alt="Top Languages" width="42%" />
</p>

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=MikhaelCat&theme=tokyo-night&hide_border=true&bg_color=0d1117)](https://github.com/MikhaelCat)

```text
[EOF] -- Open for collaboration on Systems Programming & Security Engineering
```

</div>
