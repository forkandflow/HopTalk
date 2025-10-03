# HopTalk 🚀

**Offline Push-to-Talk Walkie-Talkie for Smartphones**

HopTalk is a mobile app that transforms your smartphone into a **real-time walkie-talkie** using **Wi-Fi Direct mesh networking** — no internet required. Messages and voice hop device-to-device, extending your communication range. Perfect for outdoor adventures, events, or areas with no cellular coverage.

---

## 🔹 Features

* **Push-to-Talk (PTT)** interface: Hold to speak, release to stop.
* **Offline voice streaming**: No internet or cellular data needed.
* **Hop-by-hop forwarding**: Extend communication range via nearby devices.
* **Peer discovery**: Automatic detection of nearby phones.
* **Multi-hop mesh network**: Reach distant peers using intermediate devices.
* **Lightweight and real-time**: Minimal latency for smooth conversation.

---

## 🔹 How It Works

1. Phones connect via **Wi-Fi Direct**.
2. Voice is captured in **small audio chunks** and sent as **UDP packets**.
3. Each device can **forward received packets** to other peers (mesh/hop functionality).
4. Destination device plays the audio in real-time.

---

## 🔹 Technology Stack

* **Platform**: Android
* **Language**: Kotlin / Java
* **Audio**: AudioRecord & AudioTrack APIs
* **Networking**: Wi-Fi Direct, UDP sockets
* **Codec**: PCM16 (future: Opus for compression)
* **Architecture**: Peer-to-peer mesh with hop forwarding

---

## 🔹 Installation & Usage

1. Clone this repository:

   ```bash
   git clone https://github.com/<your-username>/HopTalk.git
   ```
2. Open in Android Studio.
3. Build & run on Android devices (minimum API 21).
4. Press **Scan for Peers**, connect to nearby devices.
5. Press **PTT button** to start talking!

---

## 🔹 Roadmap / Next Steps

* ✅ Single-hop voice streaming prototype
* 🔜 Multi-hop mesh forwarding for extended range
* 🔜 Opus audio compression for bandwidth optimization
* 🔜 User-friendly UI & contact list
* 🔜 Optional: Message recording & offline storage

---

## 🔹 License

HopTalk is **MIT Licensed** — free to use, modify, and share.

---

## 🔹 Contact

Developed with 💡 by [Your Name]
GitHub: [https://github.com/<your-username>](https://github.com/<your-username>)
