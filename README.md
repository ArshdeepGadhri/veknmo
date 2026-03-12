# Veknmo: Phasmophobia Ghost Speed Tool

Veknmo is a beautiful, performant tool built for identifying and simulating ghost speeds in the game **Phasmophobia**. Built as a single-file static web application, it combines utility with a modern, glassmorphic dark-mode aesthetic. You can find a live working version of the tool [here](https://veknmo.vercel.app/).

## Features

### 🎧 BPM Analyzer
Accurately determine the ghost's speed by tapping along to its footsteps.
1. Select the relevant **Ghost Speed Modifier** based on your custom difficulty settings.
2. Listen to the ghost walk during a hunt and tap the <kbd>Space</kbd> bar (or click the 'Tap' button) in rhythm with its footsteps.
3. The tool instantly calculates the footstep BPM (Beats Per Minute) and outputs the corresponding **Estimated Speed** in meters per second (m/s).

### 🏃‍♂️ Footstep Simulator
Familiarize yourself with what different ghost speeds sound like.
* Input a target speed in m/s (e.g., standard 100% ghost speed is 1.7 m/s).
* Click **Start Simulation** to play a looping audio file replicating the footstep rhythm at that exact speed.

## Technology Stack

This tool emphasizes both performance and design:
*   **Vanilla JavaScript:** Core logic for math, interval timing, and audio playback. No heavy frameworks.
*   **GSAP (GreenSock):** Powers the smooth reveal animations, dynamic button feedback, and the continuous parallax background typography.
*   **Lenis:** Provides butter-smooth, momentum-based scrolling.
*   **CSS Glassmorphism:** Features a premium dark theme enhanced with translucent styling, overlapping glows, and bold Inter/Oswald typography.

## Setup & Usage

Since Veknmo is a completely static tool, you can simply open the `index.html` file in any modern web browser to start using it immediately—no server or build process required!

```bash
# If you prefer to run it on a local server for testing:
python -m http.server 8080
```

> **Note on Audio:** For the Footstep Simulator to function, ensure you have a `footstep.mp3` audio file located in an `assets/` directory adjacent to `index.html`. 
