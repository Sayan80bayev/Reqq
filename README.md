# Reqq 🌀

[![Go Version](https://img.shields.io/badge/Go-1.21%2B-blue)](https://golang.org)
[![Build](https://img.shields.io/badge/build-passing-brightgreen)]()
[![Platform](https://img.shields.io/badge/platform-Desktop%20(Gio)-orange)](https://gioui.org)

 
**Reqq** is a high-performance user behavior simulator built with [gioui.org](https://gioui.org), designed to visualize and control hundreds of concurrent virtual users in real-time using Go’s native concurrency.

---

## ✨ Features

- 🧠 Simulate hundreds or thousands of virtual users
- 🔀 Shuffled requests to simulate different user behaviors 🤹‍♂️👥
- ⏱️ Control timeouts, delays, and retries via UI
- 📊 Real-time stats powered by `sync/atomic`
- ⚡ Built entirely in Go with GPU-accelerated rendering (via Gio)
- 📁 Easily script behaviors using Go functions
- 🔌 Extensible architecture for plugins and metrics

---

## 🖥️ Preview

> *(Coming soon!)*

---

## 🚀 Getting Started

### Prerequisites

- Go `1.21` or higher
- Git
- A supported OS: macOS, Linux, Windows

### Install

```bash
git clone https://github.com/yourusername/reqq.git
cd cmd/reqq
go run .
```
