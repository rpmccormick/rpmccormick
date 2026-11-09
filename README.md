# Hi, I'm Ryan McCormick 👋

**Founder @ [Surround View Systems RVA](https://svsrva.com)** — Building enterprise B2B SaaS platforms, AI-driven visualization engines, edge-AI hardware accelerators, and local-first smart-home automation in Richmond, VA.

---

### 🚀 Enterprise SaaS & Ambient AI
- **[AUI V2 — Universal Visualization Engine](https://svsrva.com/aui/):** Zero-build UI-as-a-Service API & MCP engine that transforms raw JSON payloads from AI agents into interactive **DataTables**, **DayPilot Schedulers**, and **CRM Pivot Views** with built-in SMS & Email sharing.
- **[`Atmosphere`](https://github.com/rpmccormick/Atmosphere) ([Live Demo](https://svsrva.com/atmosphere/)):** Real-time conversation-to-photo & Smart Q&A TV display powered by Google Gemini Flash, Pexels 4K photography, Wikipedia Commons, and Web Speech API.
- **Hotel Direct PMS:** Multi-tenant hospitality Property Management System, channel manager, and real-time operational telemetry suite.

---

### ⚡ Edge-AI Inference, Embedded Linux & Smart-Home Hardware Automation
- **[`tpuaas` — Coral EdgeTPU-as-a-Service (`v1.2.0`)](https://github.com/rpmccormick/tpuaas):**
  - Multi-tenant HTTP & WebSocket microservice that shares a single Google Coral Edge TPU (`/dev/apex_0`) across robotics fleets, ambient lighting engines, and camera NVRs with **zero model-thrashing** and **`5.94 ms`/frame** hardware latency.
  - Features an **8 MB SRAM-Locality Priority Scheduler (`168 FPS` capacity)**, Dual Operating Modes (Queued Mode 1 with `85 ms` anti-starvation aging + 1-slot Latest-Frame-Wins Stream Mode 2), watchdog-protected Exclusive Take-Over Leases (`/v1/lease/*`), zero-copy raw planar `I420` ingestion (`<0.25 ms`), and CPU-offloaded 2D FFT Phase Correlation optical flow (`0%` TPU load).
- **[`rpmlight` — Perceptual Zero-Blink Ambilight Engine (`v0.4.0`)](https://github.com/rpmccormick/rpmlight):**
  - Human-vision-inspired 52-zone camera & screen Ambilight engine (`15–20 FPS` in pure Python at `<10%` CPU on embedded wall switches) driving Nanoleaf 4D, WLED, and Home Assistant Hue Sky / Wing lights.
  - Implements **3-Step Orthogonal Auto-Blackness Deletion** (`2.35:1` letterbox, Kodi poster rows & `4:3` pillarbox), unbiased Bayer `bggr` fringe cancellation, brown/tan/skin protection against red-diode bias, single-slider perceptual curves (`1%–100%`) with local Kodi JSON-RPC OSD toasts, and optional low-rate (`0.25 Hz`) Coral EdgeTPU (`tpuaas`) & Gemini Vision scene/saliency cues.
- **[`brilliant-mqtt`](https://github.com/rpmccormick/brilliant-mqtt):**
  - **Virtual HMI / Detached Slider Controller:** Decouples physical Brilliant capacitive sliders (BLE mesh switches & multi-gang panels) from 120V load relays via local Thrift `<50ms` unicast RPC, hardware `0x0404` double/triple-tap decoding (`double_tap_scene_id`), and 4 live-selectable operating modes (`passthrough`, `virtual_dimmer`, `stepped`, `gesture_50`).
  - **Native BLE Mesh PIR Motion Passthrough:** Solves the `motion_low_threshold = 20` idle thermal noise latch (`0xc12008`) for zero-polling edge-triggered motion in Home Assistant.
  - **NXP i.MX6 Panel Camera & TV Ambilight Engine:** Hardware-cropped V4L2/i.MX6 capture, mechanical privacy shutter sensing (`GPIO 5`/`GPIO 98`), and real-time MQTT RGB Ambilight extraction.
- **[`wroof-wled-spider`](https://github.com/rpmccormick/wroof-wled-spider) ([Live Roof Video](https://youtu.be/k3ooahqzgD4) • [HA Visualizer Video](https://youtu.be/dJlAyv1m9z0)):** Autonomous 3-pixel Halloween spider patrolling **1,076 roofline & deck LEDs** across 2 ESP32 WLED controllers (`40 FPS` UDP DDP) that spins webs, hunts flies, and "steals" physical Philips Hue porch bulbs—paired with a live Home Assistant custom Lovelace visualizer card.
- **[`Mammotion-HA`](https://github.com/rpmccormick/Mammotion-HA):** BLE/Wi-Fi connection resilience and Home Assistant automation fixes for Mammotion robotic lawn mowers.

---

### 🏛️ Classic Hardware & Embedded Heritage (2006–2012)
- **[`RPMLight / lightpack` (2012)](https://github.com/rpmccormick/lightpack):** The original 2012 Borland Delphi Win32 screen-capture TV Ambilight controller (`Controller.pas`) + Arduino `FastSPI_LED` WS2811 frame-synced 115,200-baud serial firmware (`RPMFastSPI.ino`, `RPMxmas.ino`)—built 8 years before WLED and evolved 14 years later into **[`rpmlight` (`v0.4.0`)](https://github.com/rpmccormick/rpmlight)**.
- **`SKINbedder` (2006 — MP3Car / RoadRunner):** Early CarPC Win32 window-embedding utility created for the classic *MP3Car.com* / *RoadRunner (RideRunner)* touchscreen front-end ecosystem, embedding third-party GPS navigation, OBD-II telemetry, and media players directly inside custom in-dash skins.
- **Samsung Family Hub Camera (Retired 2026):** Author of the early SmartThings / Scrypted interior refrigerator camera integrations (archived after Samsung locked interior camera access behind a mandatory $5/month subscription paywall).

---

📫 **Web:** [svsrva.com](https://svsrva.com) • **Interactive AUI Sandbox:** [svsrva.com/aui/demo.html](https://svsrva.com/aui/demo.html) • **Location:** Richmond, VA
