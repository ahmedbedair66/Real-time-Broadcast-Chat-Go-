# Real-Time Broadcast Chat System (Go)

A simple real-time chat system built in Go using:
- Goroutines  
- Channels  
- TCP sockets  
- Mutex for synchronized shared state  

Each new client is announced to all others, and all messages are broadcast in real time (no self-echo).

---

## 📌 Features

### ✔ Real-time Broadcasting  
Any message sent by a client is instantly delivered to all other connected clients.

### ✔ Join Notifications  
When a new client connects, all other users receive:

