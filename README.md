# September‑Solomon‑Writes
**A static‑site landing page for my indie‑author paranormal & dark‑romance novels**

![Site screenshot](assets/screenshot.png) <!-- optional: add a screenshot file in an `assets/` folder -->

September‑Solomon‑Writes is a lightweight, SEO‑friendly static website that:

- Showcases upcoming paranormal‑romance novels (cover art, blurbs, purchase links)  
- Hosts a blog for updates, behind‑the‑scenes notes, and excerpts  
- Collects newsletter sign‑ups via **MailerLite** (or your chosen service)  

Built with **Eleventy** and hosted for free on **GitHub Pages**, the site loads in < 1 s on desktop and mobile devices.

## Table of Contents
- [Features](#features)  
- [Live Demo](#live-demo)  
- [Getting Started](#getting-started)  
  - [Prerequisites](#prerequisites)  
  - [Installation](#installation)  
  - [Development Server](#development-server)  
- [Deployment](#deployment)  
- [Contributing](#contributing)  
- [License](#license)  

## Features
- **Landing page** with hero image, tagline, and CTA buttons  
- **Book catalog** with cover art, synopsis, and purchase links  
- **Blog** powered by Markdown files for easy posting  
- **Newsletter signup** integrated via MailerLite API (or your provider)  
- **Responsive design** – looks great on desktop, tablet, and mobile  
- **Performance‑optimized** – Lighthouse performance > 90, under 1 s load time  

## Live Demo
[![Live Demo – Visit Site](https://img.shields.io/badge/Live%20Demo-Visit%20Site-brightgreen?style=for-the-badge)](https://from-the-desk-of-september.github.io/September-Solomon-Writes/)

> *If the demo link ever breaks, you can rebuild locally (see “Getting Started”).*

## Getting Started

### Prerequisites
- **Node.js** ≥ 18 (download from <https://nodejs.org/>)
- **Git** (already installed on your system)

### Installation
```bash
# Clone the repository (skip if you already have a local copy)
git clone https://github.com/From-the-desk-of-September/September-Solomon-Writes.git
cd September-Solomon-Writes

# Install npm dependencies (only needed once)
npm ci        # uses the exact versions from package-lock.json
