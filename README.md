# 🤖 AI Scraper System

<div align="center">

![AI Scraper System](https://img.shields.io/badge/AI-Scraper_System-FF6B6B?style=for-the-badge&logo=robot&logoColor=white)
![AGPL-3.0](https://img.shields.io/badge/License-AGPL_3.0-4CAF50?style=for-the-badge&logo=gnu&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Ready-2496ED?style=for-the-badge&logo=docker&logoColor=white)

**🛡️ Production Ready • 🌐 Open Source**

[🌐 useragent.wtf](https://useragent.wtf) • [📚 Documentation](./production-VMs/README.md) • [🐳 Docker Hub](https://hub.docker.com/u/scrapedat)

</div>

---

## 🔥 What is AI Scraper System?

An **intelligent web scraping platform** that combines AI-powered analysis with distributed browser automation. Built to be **corporate exploitation proof** through AGPL-3.0 licensing.

### 🚫 Corporate Protection
- **AGPL-3.0 Licensed**: Forces any SaaS deployment to open-source their entire platform
- **Big Tech Immune**: Amazon, Google, Meta cannot commercially exploit this code
- **Community Owned**: Stays free and open forever

### ⚡ Key Features
- **🧠 AI-Powered Analysis**: Website DNA fingerprinting and intelligent scraping
- **🌐 Distributed Browsers**: Chrome automation across multiple containers
- **📊 Real-time Dashboard**: Live monitoring and control interface
- **🗄️ Hybrid Database**: SQLite + Redis + Blob storage for maximum performance
- **🔄 MQTT Communication**: Real-time data streaming between components

---

## 🏗️ System Architecture

```
┌─────────────────┐    MQTT     ┌─────────────────┐    Direct    ┌─────────────────┐
│                 │◄──────────► │                 │◄────────────► │                 │
│  Dashboard      │             │  AI Scraper     │               │  FrankensteinDB │
│  (React/Electron│             │  VM (Python)    │               │  (Hybrid DB)    │
│   + TypeScript) │             │                 │               │                 │
│                 │             │  • DNA Analysis │               │  • 46K+ writes/s│
│  • Real-time UI │             │  • Browser VMs  │               │  • <0.4ms query │
│  • Desktop App  │             │  • Extensions   │               │  • 90% compression│
└─────────────────┘             └─────────────────┘               └─────────────────┘
        │                                │                                │
        └────────────────────────────────┼────────────────────────────────┘
                                         │
                               ┌─────────▼─────────┐
                               │                   │
                               │  GitHub Registry  │
                               │  (Free & Public)  │
                               │                   │
                               │  • ghcr.io        │
                               │  • Unlimited      │
                               │  • AGPL Protected │
                               └───────────────────┘
```

---

## 📦 Quick Deploy

```bash
# 1. Clone orchestration repo
git clone https://github.com/scrapedat/production-vms.git
cd production-vms

# 2. Publish containers (requires GITHUB_TOKEN)
./publish-to-github.sh

# 3. Deploy complete system
./deploy-github-registry.sh

# 4. Access your system
# Dashboard: http://localhost:3000
# MQTT: localhost:1883
```

---

## 🛡️ AGPL-3.0 Protection Details

### What Big Tech Cannot Do:
- ❌ **Amazon** cannot embed in AWS services without open-sourcing AWS
- ❌ **Google** cannot use in Cloud Platform without open-sourcing GCP
- ❌ **Meta** cannot integrate without open-sourcing their entire platform
- ❌ **Microsoft** cannot deploy as Azure service without open-sourcing Azure
- ❌ **Any corporation** cannot create proprietary SaaS products

### Why AGPL-3.0?
- **Network Copyleft**: Requires source code sharing for network services
- **SaaS Protection**: Forces cloud deployments to be open source
- **Corporate Deterrent**: Big tech avoids AGPL because it destroys their business model
- **Community Protection**: Keeps the software free and accessible

---

## 📊 Performance Metrics

| Component | Metric | Value |
|-----------|--------|-------|
| FrankensteinDB | Write Speed | 46,000+ records/second |
| FrankensteinDB | Query Time | <0.4ms average |
| FrankensteinDB | Compression | 90%+ data reduction |
| AI Scraper VM | Browser Instances | Scalable Docker containers |
| Dashboard | UI Framework | React + TypeScript + Tailwind |
| System | License | AGPL-3.0 (Corporate Proof) |

---

## 🌟 Featured Projects

### [🤖 AI Scraper VM](https://github.com/scrapedat/ai-scraper-vm)
Intelligent scraping orchestrator with DNA analysis and browser automation.

### [📊 Dashboard](https://github.com/scrapedat/ai-scraper-dashboard)
Real-time monitoring interface built with React and Electron.

### [🗄️ FrankensteinDB](https://github.com/scrapedat/frankenstein-db)
Hybrid database combining SQLite, Redis, and blob storage.

### [🚀 Production VMs](https://github.com/scrapedat/production-vms)
Complete orchestration and deployment infrastructure.

---

## 🔧 Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=flat-square&logo=node.js&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=flat-square&logo=sqlite&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)

</div>

---

## 📈 Development Status

- ✅ **Core System**: Production ready
- ✅ **AGPL-3.0 Protection**: Fully implemented
- ✅ **GitHub Registry**: Free distribution enabled
- ✅ **Documentation**: Complete setup guides
- ✅ **Testing**: End-to-end test suite
- 🚧 **Website**: useragent.wtf (Coming Soon)

---

## 🤝 Contributing

We welcome contributions! All code must remain AGPL-3.0 licensed.

### How to Contribute:
1. Fork any component repository
2. Create a feature branch
3. Make your changes
4. Ensure AGPL-3.0 compliance
5. Submit a pull request

### Code of Conduct:
- Respect the AGPL-3.0 license
- Keep the software free and open
- Protect against corporate exploitation
- Support the open-source community

---

## 📞 Contact & Community

- **🌐 Website**: [useragent.wtf](https://useragent.wtf)
- **📧 Email**: ai-scraper@scrapedat.com
- **🐛 Issues**: [GitHub Issues](https://github.com/scrapedat/production-vms/issues)
- **💬 Discussions**: [GitHub Discussions](https://github.com/scrapedat/production-vms/discussions)

---

<div align="center">

**Built with ❤️ for the open-source community**  
**Protected by AGPL-3.0 • September 2025**

![GitHub stars](https://img.shields.io/github/stars/scrapedat/production-vms?style=social)
![GitHub forks](https://img.shields.io/github/forks/scrapedat/production-vms?style=social)

</div>
