# 🎧 AudioSync - Real-Time P2P Audio Streaming Engine

AudioSync is a real-time peer-to-peer audio streaming system leveraging WebRTC for ultra-low latency communication.

---

## ✨ Features
- 🎙 Real-time audio streaming over local network
- 🔗 Peer-to-peer communication using WebRTC (UDP-based)
- 📡 TCP signaling server using Socket.io
- ⚡ Low-latency and efficient transmission

---

## 🛠 Tech Stack
- WebRTC
- Node.js
- Socket.io
- TCP/UDP Protocols

---

## 🧠 Key Concepts
- Real-Time Communication (RTC)
- Signaling & Session Negotiation
- NAT Traversal (WebRTC)
- UDP vs TCP tradeoffs

---

## ⚙️ Architecture
1. TCP signaling server exchanges metadata between peers
2. Peers establish a WebRTC connection
3. Audio streams directly using UDP

---

## 🚀 Getting Started

git clone <repo-link>  
cd AudioSync  
npm install  
node server.js  

---

## 📊 Highlights
- Near real-time audio transmission
- Efficient bandwidth utilization
- Minimal latency

---

## 📌 Future Improvements
- Video streaming support
- Noise suppression
- Multi-user conferencing
