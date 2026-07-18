# NEON AURA AR

NEON AURA AR is a browser-based **hand-tracking audiovisual experience** that transforms webcam input into glowing neon motion, reactive particles, and sound-driven visual feedback. It uses MediaPipe Hands, HTML5 Canvas, and the Web Audio API to create a futuristic AR-style interaction layer in the browser [file:1].

## Overview

This project is designed as an immersive real-time motion art demo. When the camera starts, the app tracks hand landmarks, detects gestures, and maps hand distance into visible-spectrum color behavior [file:1]. The interface presents a cinematic dark theme with glass panels, neon accents, animated trails, and theme switching for a more polished portfolio-ready presentation [file:1].

The experience is intentionally responsive and reactive. Hand movement affects background motion, fingertip sparks, waveform-style effects, and audio intensity, making the visual output feel alive rather than static [file:1].

## Features

- Real-time hand tracking with MediaPipe Hands [file:1].
- Pinch gesture detection for interactive triggers [file:1].
- Open hand and fist recognition for gesture feedback [file:1].
- Dynamic wavelength mapping from hand distance, shown across the 380–700nm spectrum [file:1].
- Neon particle bursts, shockwaves, ripples, and motion trails [file:1].
- Continuous reactive hum and event-based sound effects [file:1].
- Five visual themes: Rainbow, Cyberpunk, Lava, Ocean, and Galaxy [file:1].
- Futuristic HUD with live stats for hands, FPS, gesture, spread, wavelength, and distance [file:1].

## Interaction Flow

The app begins with a permission gate that asks the user to allow camera access and enter the experience [file:1]. After activation, the audio engine is initialized, the hand tracker starts, and the render loop continuously updates the visual scene [file:1]. The background canvas handles atmospheric motion, while the main canvas renders hands, particles, ripples, and glow-based overlays [file:1].

Gesture logic drives the core interaction. Pinching creates a zap effect, bringing both hands close can trigger an explosion-style response, and hand spacing influences the reported wavelength color and the audio hum [file:1]. This makes every small movement part of the composition [file:1].

## Theme System

The theme system changes the accent color and mood of the interface [file:1].

| Theme | Visual Style |
|---|---|
| Rainbow | Full-spectrum neon glow [file:1] |
| Cyberpunk | Cyan and magenta digital energy [file:1] |
| Lava | Warm red-orange fire tones [file:1] |
| Ocean | Cool blue-green pulse [file:1] |
| Galaxy | Deep purple cosmic glow [file:1] |

## Visual Effects

The animation system is one of the strongest parts of the project. It uses layered canvas rendering, additive blending, and fading trails to create a smooth sci-fi appearance [file:1]. Finger tips emit sparks, close hand movements create electric connections, and touch events produce flashes and expanding shockwaves [file:1]. The matrix-like background motion also reacts to hand speed, giving the whole scene more energy [file:1].

## Audio Effects

Sound is tightly coupled to interaction. A low hum responds to the distance between hands, while pinches and impact-like hand collisions trigger sharper synthesized sounds [file:1]. This adds a second feedback channel that makes the animation feel more responsive and immersive [file:1].

## Tech Stack

- HTML5 [file:1]
- CSS3 with glassmorphism styling [file:1]
- JavaScript [file:1]
- MediaPipe Hands [file:1]
- HTML5 Canvas [file:1]
- Web Audio API [file:1]

## Setup

1. Clone the repository.
2. Open the project in a browser that supports webcam access and audio initialization.
3. Serve it over HTTPS or a local development server.
4. Grant camera permission when prompted.
5. Click **Enter Experience** to start the animation [file:1].

## Browser Notes

Because the project depends on camera and audio permissions, it works best in modern browsers with secure-context support. For a smooth experience, use Chrome, Edge, or another browser with strong WebRTC and canvas performance.

## Use Cases

This project works well as:

- A portfolio showcase for interactive web development.
- A creative coding demo.
- An AR-inspired motion art installation.
- A technical showcase for computer vision and real-time rendering.

## Future Improvements

- Add more gesture types and transitions.
- Include calibration for different hand sizes and camera distances.
- Support mobile screen orientation optimizations.
- Add recording or screenshot export.
- Expand the theme engine with custom user palettes.

## License

Choose a license that matches your publishing goals, such as MIT for open-source use or a private portfolio license.

---
**Project name:** NEON AURA AR [file:1]
**Original page title:** Advanced Hand Tracking AR [file:1]
