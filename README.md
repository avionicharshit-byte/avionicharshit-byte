# Hi, I'm Harshit 👋

I build at the intersection of **embedded systems and AI** - firmware, IoT hardware, and developer tools that make on-device ML less painful.

## 🔭 Currently building

### [📟 mcufit](https://github.com/avionicharshit-byte/mcufit)

**Check if an AI model fits on a microcontroller - before you flash it.**
Instant fit verdicts across 31 boards, byte-exact memory measurement using the real TFLite Micro runtime (native *and* WebAssembly), quantization previews, and a CI action.

**[🌐 Try it in your browser](https://avionicharshit-byte.github.io/mcufit/)** · `pip install mcufit`

## 🎙 On-device AI

I work on speech recognition and tool-calling models that run on embedded Linux boards with under 200 MB of RAM, and no cloud round trip. Mostly the unglamorous half of it: what actually fits in memory, what real-time factor an ARMv7 core can hold, and when the honest answer is that the model does not fit.

### [⏱️ mcufit-bench](https://github.com/avionicharshit-byte/mcufit-bench)

**What TensorFlow Lite Micro actually costs on real hardware.**
The ground truth mcufit is checked against: 54 measurements across 4 models and 3 boards, per model and per layer. Anyone can add a board.

### [🗜️ openzl-agent](https://github.com/avionicharshit-byte/openzl-agent)

**Format-aware compression without the compression expertise.**
An agent reads your data, writes the OpenZL data description, trains a compressor, verifies the round-trip byte-for-byte, and reports the savings against zstd and gzip. 50% off a CSV that `zstd -3` had already compressed.

## 🧰 Some other things I've made

- [loan-emi-negotiator](https://github.com/avionicharshit-byte/loan-emi-negotiator) - an agent that drafts a lender-specific rate-negotiation email
- [docpilot](https://github.com/avionicharshit-byte/docpilot) - document collection loop for vehicle-loan officers
- IoT & embedded builds - [laser turret](https://github.com/avionicharshit-byte/LaserTurret), [fire-alert Telegram bot](https://github.com/avionicharshit-byte/fireAlertTelegram)

## 📫 Reach me

[avionicharshit@gmail.com](mailto:avionicharshit@gmail.com) · [YouTube](https://www.youtube.com/c/avionicharshit)
