<div align="center">
  <img src="public/favicon.png" alt="Sublink Worker" width="120" height="120"/>

  <h1><b>Sublink Worker</b></h1>
  <h5><i>One Worker, All Subscriptions</i></h5>

  <p><b>A lightweight subscription converter and manager for proxy protocols, deployable on Cloudflare Workers, Vercel, Node.js, or Docker.</b></p>

  <p style="display: flex; align-items: center; gap: 10px;">
  <a href="https://deploy.workers.cloudflare.com/?url=https://github.com/meyifan20-icloud/sublink-worker">
    <img src="https://deploy.workers.cloudflare.com/button" alt="Deploy to Cloudflare Workers" style="height: 32px;"/>
  </a>
  <a href="https://vercel.com/new/clone?repository-url=https://github.com/meyifan20-icloud/sublink-worker&env=KV_REST_API_URL,KV_REST_API_TOKEN&envDescription=Vercel%20KV%20credentials%20for%20data%20storage&envLink=https://vercel.com/docs/storage/vercel-kv">
    <img src="https://vercel.com/button" alt="Deploy to Vercel" style="height: 32px;"/>
  </a>
</p>

  <h3>📚 Project</h3>
  <p>
    <a href="https://e.a.us.ci/"><b>⚡ Live Service</b></a> ·
    <a href="https://github.com/meyifan20-icloud/sublink-worker"><b>Repository</b></a> ·
    <a href="https://github.com/meyifan20-icloud/sublink-worker#-quick-start"><b>Quick Start</b></a> ·
    <a href="https://github.com/meyifan20-icloud/sublink-worker/releases"><b>Releases</b></a>
  </p>
</div>

## 🚀 Quick Start

### Production Service
- **Live service**: https://e.a.us.ci/

### One-Click Deployment
- Cloudflare Workers and Vercel buttons above use this repository as the deployment source.
- Cloudflare Workers requires a `SUBLINK_KV` namespace. The repository deployment script creates/reuses it automatically.
- Production deployment for this maintained copy is handled through the owner's central Cloudflare automation; no long-lived Cloudflare token is stored in this repository.

### Alternative Runtimes
- **Node.js**: `npm run build:node && node dist/node-server.cjs`
- **Vercel**: `vercel deploy` (configure KV in project settings)
- **Docker**: `docker pull ghcr.io/meyifan20-icloud/sublink-worker:latest`
- **Docker Compose**: `docker compose up -d` (includes Redis)

## ✨ Features

### Supported Protocols
ShadowSocks • VMess • VLESS • Hysteria2 • Trojan • TUIC

### Client Support
Sing-Box • Clash • Xray/V2Ray • Surge

### Input Support
- Base64 subscriptions
- HTTP/HTTPS subscriptions
- Full configs (Sing-Box JSON, Clash YAML, Surge INI)

### Core Capabilities
- Import subscriptions from multiple sources
- Generate fixed/random short links (KV-based)
- Light/Dark theme toggle
- Flexible API for script automation
- Multi-language support (Chinese, English, Persian, Russian)
- Web interface with predefined rule sets and customizable policy groups

## 🤝 Contributing

Issues and Pull Requests are welcome to improve this project.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⚠️ Disclaimer

This project is for learning and exchange purposes only. Please do not use it for illegal purposes. All consequences resulting from the use of this project are solely the responsibility of the user and are not related to the developer.

## 🙏 Upstream

This repository is independently maintained from the original open-source project by 7Sageer. Runtime, deployment, update checks, Docker images, and repository links in this edition point to this repository; the original MIT copyright notice is preserved in [LICENSE](LICENSE).
