# Hi, I'm Harshit 👋

📍 **India** | 🔩 **Embedded x AI** | 🧪 **On-device ML that actually fits**

I build firmware, IoT hardware, and developer tools for running AI on devices that are too small for it.

![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/-C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Arduino](https://img.shields.io/badge/-Arduino-00878F?style=flat-square&logo=arduino&logoColor=white)
![ESP32](https://img.shields.io/badge/-ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/-Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![TFLite Micro](https://img.shields.io/badge/-TFLite%20Micro-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Yocto](https://img.shields.io/badge/-Yocto-1C7C54?style=flat-square&logo=linux&logoColor=white)

<p align="center">
  <img src="https://ghchart.rshah.org/196127/avionicharshit-byte" alt="Harshit's GitHub contribution heatmap" />
</p>

## 🔭 What I'm building

### [📟 mcufit](https://github.com/avionicharshit-byte/mcufit)

**Check if an AI model fits on a microcontroller, before you flash it.**
Instant fit verdicts across 31 boards, byte-exact memory measurement using the real TFLite Micro runtime (native *and* WebAssembly), quantization previews, and a CI action.

**[🌐 Try it in your browser](https://avionicharshit-byte.github.io/mcufit/)** · `pip install mcufit`

### [⏱️ mcufit-bench](https://github.com/avionicharshit-byte/mcufit-bench)

**What TensorFlow Lite Micro actually costs on real hardware.**
The ground truth mcufit is checked against: 54 measurements across 4 models and 3 boards, per model and per layer. Anyone can add a board.

### [🗜️ openzl-agent](https://github.com/avionicharshit-byte/openzl-agent)

**Format-aware compression without the compression expertise.**
An agent reads your data, writes the OpenZL data description, trains a compressor, verifies the round-trip byte-for-byte, and reports the savings against zstd and gzip. 50% off a CSV that `zstd -3` had already compressed.

## 🎙 On-device AI

I work on speech recognition and tool-calling models that run on embedded Linux boards with under 200 MB of RAM and no cloud round trip. Mostly the memory arithmetic: what fits, what an ARMv7 core can hold in real time, and when the honest answer is that it does not fit.

## 🔧 Contributing to

- **[nlohmann/json](https://github.com/nlohmann/json)** ![Stars](https://img.shields.io/github/stars/nlohmann/json?style=flat&color=gold) - JSON for Modern C++
- **[yhirose/cpp-httplib](https://github.com/yhirose/cpp-httplib)** ![Stars](https://img.shields.io/github/stars/yhirose/cpp-httplib?style=flat&color=gold) - A C++ header-only HTTP/HTTPS server and client library
- **[livekit/agents](https://github.com/livekit/agents)** ![Stars](https://img.shields.io/github/stars/livekit/agents?style=flat&color=gold) - A framework for building realtime voice AI agents
- **[cactus-compute/needle](https://github.com/cactus-compute/needle)** ![Stars](https://img.shields.io/github/stars/cactus-compute/needle?style=flat&color=gold) - 14MB foundation model for tiny devices; phones, wearables, smart home, and robots
- **[growthbook/growthbook](https://github.com/growthbook/growthbook)** ![Stars](https://img.shields.io/github/stars/growthbook/growthbook?style=flat&color=gold) - Open source feature flags, experimentation, and product analytics
- **[Serial-Studio/Serial-Studio](https://github.com/Serial-Studio/Serial-Studio)** ![Stars](https://img.shields.io/github/stars/Serial-Studio/Serial-Studio?style=flat&color=gold) - Open-source telemetry dashboard. UART, BLE, MQTT, Modbus, CAN bus and more
- **[Openpanel-dev/openpanel](https://github.com/Openpanel-dev/openpanel)** ![Stars](https://img.shields.io/github/stars/Openpanel-dev/openpanel?style=flat&color=gold) - Open-source web and product analytics, an alternative to Mixpanel
- **[0xShug0/audio.cpp](https://github.com/0xShug0/audio.cpp)** ![Stars](https://img.shields.io/github/stars/0xShug0/audio.cpp?style=flat&color=gold) - Pure C++ inference engine for audio models, powered by ggml
- **[dearlordylord/huly-mcp](https://github.com/dearlordylord/huly-mcp)** ![Stars](https://img.shields.io/github/stars/dearlordylord/huly-mcp?style=flat&color=gold) - Feature-complete MCP server and CLI for the Huly platform

## 🧰 Some other things I've made

- **[loan-emi-negotiator](https://github.com/avionicharshit-byte/loan-emi-negotiator)** - an agent that drafts a lender-specific rate-negotiation email
- **[docpilot](https://github.com/avionicharshit-byte/docpilot)** - document collection loop for vehicle-loan officers
- **[fireAlertTelegram](https://github.com/avionicharshit-byte/fireAlertTelegram)** - ESP32 fire alert that pings you on Telegram
- **[LaserTurret](https://github.com/avionicharshit-byte/LaserTurret)** - laser module on a servo gimbal, aimed with a PS2 joystick

## 📫 Reach me

[![Email](https://img.shields.io/badge/Email-avionicharshit@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:avionicharshit@gmail.com)
[![YouTube](https://img.shields.io/badge/YouTube-avionicharshit-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://www.youtube.com/c/avionicharshit)
[![mcufit](https://img.shields.io/badge/Site-mcufit-2563EB?style=flat-square&logo=githubpages&logoColor=white)](https://avionicharshit-byte.github.io/mcufit/)
