<p align="center">
  <a href="https://veilroute.dev"><img src="https://veilroute.dev/favicon.svg" width="64" height="64" alt="VeilRoute"></a>
</p>

<h1 align="center">VeilRoute</h1>

<p align="center">
  High-performance Akamai Bot Manager Web v3 &amp; Mobile BMP Sensor API.<br>
  <strong>200-only billing · Sub-50ms synthesis · Real-time IP Whitelist</strong>
</p>

<p align="center">
  <a href="https://veilroute.dev">Website</a> ·
  <a href="https://docs.veilroute.dev">Documentation</a> ·
  <a href="https://app.veilroute.dev">Dashboard</a> ·
  <a href="https://discord.gg/YrZAcNWtE">Discord</a>
</p>

---

### Official SDKs

| Language | Repository | Install | CI |
| :--- | :--- | :--- | :--- |
| **Python** *(sync & async)* | [`veilroutesdk/veilroute-python`](https://github.com/veilroutesdk/veilroute-python) | `pip install git+https://github.com/veilroutesdk/veilroute-python.git` | [![CI](https://github.com/veilroutesdk/veilroute-python/actions/workflows/ci.yml/badge.svg)](https://github.com/veilroutesdk/veilroute-python/actions/workflows/ci.yml) |
| **Node.js / TypeScript** | [`veilroutesdk/veilroute-node`](https://github.com/veilroutesdk/veilroute-node) | `npm install github:veilroutesdk/veilroute-node` | [![CI](https://github.com/veilroutesdk/veilroute-node/actions/workflows/ci.yml/badge.svg)](https://github.com/veilroutesdk/veilroute-node/actions/workflows/ci.yml) |
| **Go** *(zero dependencies)* | [`veilroutesdk/veilroute-go`](https://github.com/veilroutesdk/veilroute-go) | `go get github.com/veilroutesdk/veilroute-go@v0.1.0` | [![CI](https://github.com/veilroutesdk/veilroute-go/actions/workflows/ci.yml/badge.svg)](https://github.com/veilroutesdk/veilroute-go/actions/workflows/ci.yml) |

### Supported Capabilities

- **Akamai Web (`web.veilroute.dev`)**
  - `sensor_data` generation (`/api/v1/sensor`)
  - `sbsd` payloads (`/api/v1/sbsd`)
  - `sec-cpt` challenge solver (`/api/v1/sec-cpt`)
  - `pixel` payloads & `/api/v1/parse` script parameter extraction
- **Akamai Mobile BMP (`bmp.veilroute.dev`)**
  - Mobile `x-acf-sensor-data` sensor & session cookie generation (`/api/v1/sensor`)

### Getting Started

1. Create an API key in the [VeilRoute Dashboard](https://app.veilroute.dev).
2. Read the [API Reference & TLS Guide](https://docs.veilroute.dev).
3. Support: [support@veilroute.dev](mailto:support@veilroute.dev) · [Discord Community](https://discord.gg/YrZAcNWtE).
