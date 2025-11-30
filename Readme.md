# Assignment 04 – Real-Time Go Chat

## Description
A real-time chat system implemented in Go using TCP sockets, goroutines, channels, and mutex.
Messages are broadcast instantly to all connected clients except the sender.

## Features
- Real-time message broadcasting
- User join notification
- No self echo
- Goroutines and channels for concurrency
- Mutex for client list synchronization

## How to Run

### 1. Start server:
```
go run server.go
```

### 2. Start clients (multiple terminals):
```
go run client.go
```


(Open multiple terminals for multiple clients)

