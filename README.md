# EntrainMind - Neural Entrainment PWA 2026

> **EntrainMind is a browser-based PWA that works offline and lets you build configurable neural entrainment sessions using visual flicker, modulated noise, and binaural beats.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Not%20specified-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/nathan-carterdg4119/entrainmind-neural-pwa?style=flat-square)](https://github.com/nathan-carterdg4119/entrainmind-neural-pwa)

---

<p align="center">
  <a href="https://nathan-carterdg4119.github.io/entrainmind-neural-pwa/">
    <img src="https://img.shields.io/badge/Download-EntrainMind%20Latest-brightgreen?style=for-the-badge" alt="Download EntrainMind">
  </a>
</p>

> **[Get EntrainMind](https://nathan-carterdg4119.github.io/entrainmind-neural-pwa/)**

---

[Download Latest Build](https://nathan-carterdg4119.github.io/entrainmind-neural-pwa/)

---

## What EntrainMind Does

EntrainMind is a multimodal neural entrainment application delivered through the modern web browser. Its session engine brings together adjustable photic flicker, amplitude-modulated noise, and binaural beats, so each session can be shaped with independent visual and audio settings.

The progressive web app remains usable offline once its resources have been loaded. Built-in presets, local custom slots, duration controls, and session history make it possible to organize configurations and return to previous sessions without installing a separate desktop program.

---

## Highlights

- Configure visual flicker anywhere from 1 to 40 Hz.
- Generate white, pink, or brown noise.
- Tune the noise amplitude modulation controls.
- Add binaural beats and set their frequency.
- Pick white, amber, or red flicker.
- Begin with six included presets.
- Store two custom configurations on the device.
- Set a session timer and inspect previous sessions.
- Continue using the app offline in a supported browser.
- Install the application as a progressive web app.

---

## Getting Started

### Open the hosted version

Launch the current build in a compatible browser:

[Launch EntrainMind](https://nathan-carterdg4119.github.io/entrainmind-neural-pwa/)

When supported by the browser, select its install command to add EntrainMind as a PWA. For offline access, open the application online at least once so its resources can be loaded and cached.

### Serve a local checkout

```bash
git clone https://github.com/nathan-carterdg4119/entrainmind-neural-pwa.git
cd REPO
```

Use any static web server to serve the project directory. This Python command is one example:

```bash
python -m http.server 8080
```

Open `http://localhost:8080` in your browser. If the browser supports PWAs, it may provide an installation prompt.

---

## Using EntrainMind

1. Start EntrainMind in a modern web browser.
2. Select one of the six presets, or begin building a custom session.
3. Set the flicker color and visual flicker rate.
4. Choose the noise source and configure its amplitude modulation.
5. Optionally specify a binaural beat frequency.
6. Pick the desired duration using the session timer.
7. Run the session, then check session history for its record.
8. Keep commonly used custom setups in either of the two local slots.

Visual and audio features are independent, so a session can include only the components appropriate for the current use.

---

## Available Controls

The session screen contains the primary EntrainMind settings:

- Flicker rate: 1-40 Hz
- Flicker color: white, amber, or red
- Noise source: white, pink, or brown
- Amplitude modulation: adjustable within the app
- Binaural beat frequency: adjustable within the app
- Session duration: set through the session timer
- Saved setups: two custom slots stored locally

Presets, saved custom setups, and session history are handled inside the app. Ordinary browser use does not require a separate configuration file.

---

## Requirements and Compatibility

- A modern browser that supports progressive web applications.
- Browser audio capabilities for generated noise and binaural beats.
- A display that can show animated visual content.
- Internet access for the first hosted launch or application download.
- Local browser storage for custom slots and session history.
- Minimal additional storage for the application and its cached offline resources.

---

## Frequently Asked Questions

### Do I need to install EntrainMind?

No. You can open the hosted build directly in a supported browser. If the browser supports PWA installation, it may also let you install the app.

### Is offline use supported?

Yes. After EntrainMind and its required resources have been loaded or cached, it is designed to operate without an internet connection.

### How are custom settings saved?

The two custom slots and session history are intended to remain in local browser storage. Removing site data or switching browser profiles can make those saved entries unavailable.

### Which session values can I adjust?

The app lets you modify the flicker rate, flicker color, noise type, amplitude modulation, binaural beat frequency, and session duration.

### Why is there no audio?

Make sure the browser tab is not muted and interact with the page before launching the session. Certain browsers block audio until the user performs an action.

### How can I use the newest build?

Open the hosted application at [https://nathan-carterdg4119.github.io/entrainmind-neural-pwa/](https://nathan-carterdg4119.github.io/entrainmind-neural-pwa/). For an installed PWA, the browser may update its cached copy when a newer build is published.

### Where should bugs be reported?

Create an issue at [https://github.com/nathan-carterdg4119/entrainmind-neural-pwa](https://github.com/nathan-carterdg4119/entrainmind-neural-pwa). Include your browser, operating system, selected options, and clear reproduction steps.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
