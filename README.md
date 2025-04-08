# AdvancedTimer Landing Page

This repository contains the source code for the landing page of [AdvancedTimer.com](https://advancedtimer.com), a professional website for the Advanced Timer product—an ESP32-based automation device with a no-code web configuration portal.

## About Advanced Timer

Advanced Timer is an ESP32-based automation device designed to simplify control and monitoring tasks. It features:

- **6 Relays**: Control up to 6 devices with precision.
- **10 Inputs**: Monitor multiple sensors or triggers seamlessly.
- **No-Code Rule Engine**: Create automations effortlessly via a web portal accessible at `advancedtimer.local`.

The landing page highlights these features, explains how the device works, and provides contact information for support.

## Repository Structure

The project is organized as follows:

- **`index.html`**: The main HTML file containing the structure of the landing page, built with Bootstrap 5 (via CDN) for a responsive design.
- **`styles/style.css`**: Custom styles to enhance the look and feel of the page.
- **`scripts/script.js`**: JavaScript for any client-side interactivity (e.g., future dashboard features).

## Deployment

The landing page is deployed and hosted using **Cloudflare Pages**, a platform that allows for easy hosting of static websites. This repository is connected to Cloudflare Pages, which automatically builds and deploys the site whenever changes are pushed to the `main` branch on GitHub. The live site is accessible at [advancedtimer.com](https://advancedtimer.com), where it benefits from Cloudflare’s global CDN, automatic SSL, and fast performance.