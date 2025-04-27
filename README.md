# ✨ LumiGrid - AC Relay/Dimmer Node ✨

---

## 💡 What is this Node?

This ESP32-based node is the bridge between LumiGrid and your standard AC-powered devices! 🔌💡 Use it to simply switch devices on or off, or control dimmable AC loads like traditional incandescent or dimmable LED bulbs.

Developed with passion by **DevSlavDev** 👨‍💻 in collaboration with **Cube & Reclame Fabriek** 🏢.

---

## 🚀 Key Features

* **AC Control:** Safely control devices running on mains voltage. ⚡️
* **On/Off Switching:** Simple relay functionality for switching AC devices.
* **AC Dimming:** Control the brightness of dimmable AC loads (requires appropriate dimmer hardware). 💡
* **Control Modes:** Supports External (MQTT), Sync (Master/Slave), and Independent modes. 🚦
* **Calendar-Based Playback:** Equipped with an RTC for scheduled switching or dimming sequences. 🗓️
* **Preset Support:** Define presets for specific AC states (e.g., "Living Room Lights On", "Lamp 50%").
* **REST API & Web UI:** Configurable and controllable via local network. 🌐

---

## 🧠 Technology Stack

* **Hardware:** ESP32-WROOM + AC Control Circuitry (Relay and/or Dimmer) 🤖
* **Firmware:** ESP-IDF (C++)
* **Communication:** WiFi, HTTP/REST, mDNS, UDP (for Sync).
* **Safety:** Critical focus on electrical isolation and safety during design and implementation. ⚠️

---

## 🚧 Work In Progress (WIP)! 🚧

This node is currently under active development planning. 🌱 The focus is on selecting reliable and safe AC control circuitry and implementing the control logic within the ESP32 firmware.

Development of this node will be part of the ESP32 phase after the Sensor Node.

---

## 🤝 Contributions

Currently, contributions are not being actively accepted for this specific node. We are focusing on building the core system structure.

**HOWEVER!** We are building this with future collaboration in mind! 🎉 Once the main code is complete and stable, we plan to open up contributions. Keep an eye on the main LumiGrid repository for updates! 👀

---

## 🔗 Stay Tuned!

Follow the main LumiGrid repository for updates on our progress! 😊

---

Made with ❤️ by DevSlavDev for Cube & Reclame Fabriek
