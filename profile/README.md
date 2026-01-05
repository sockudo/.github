# Sockudo - High-Performance WebSocket Server

A blazing-fast, scalable WebSocket server implementing the Pusher protocol in Rust.

🚀 **[Get Started](https://github.com/sockudo/sockudo)** | 📚 **[Documentation](https://sockudo.app)** | 💬 **[Discord](https://discord.gg/ySfNxfh2gZ)**

---

## Why Sockudo?

- ⚡ **100K+ concurrent connections** on a single node
- 🔄 **Pusher-compatible** - drop-in replacement
- 🏗️ **Horizontal scaling** with Redis, NATS, Redis Cluster
- 🛡️ **Production-ready** with rate limiting, SSL/TLS, metrics
- 🦀 **Built in Rust** for memory safety and performance

## Quick Start

```bash
# Clone and start with Docker
git clone https://github.com/sockudo/sockudo.git
cd sockudo
make up

# Server runs on http://localhost:6001
```

Or use any Pusher-compatible client:

```javascript
import Pusher from 'pusher-js';

const pusher = new Pusher('app-key', {
    wsHost: 'localhost',
    wsPort: 6001,
    forceTLS: false
});
```

## Repositories

| Repository | Description | Stars |
|------------|-------------|-------|
| **[sockudo](https://github.com/sockudo/sockudo)** | High-performance Pusher-compatible WebSocket server | ![Stars](https://img.shields.io/github/stars/sockudo/sockudo?style=social) |
| **[sockudo-ws](https://github.com/sockudo/sockudo-ws)** | Ultra-low latency WebSocket library with SIMD acceleration | ![Stars](https://img.shields.io/github/stars/sockudo/sockudo-ws?style=social) |
| **[sockudo-docs](https://github.com/sockudo/sockudo-docs)** | Documentation website | ![Stars](https://img.shields.io/github/stars/sockudo/sockudo-docs?style=social) |

## Community & Support

- 🐦 Follow us on [X @sockudorealtime](https://x.com/sockudorealtime)
- 💬 Join our [Discord server](https://discord.gg/ySfNxfh2gZ)
- 🐛 [Report issues](https://github.com/sockudo/sockudo/issues)
- 💡 [Discussions](https://github.com/sockudo/sockudo/discussions)
- ✉️ Email: [office@sockudo.io](mailto:office@sockudo.io)

---

**License**: MIT | **Built with** ❤️ **and Rust** 🦀
