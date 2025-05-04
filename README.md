# UnoSynth

**UnoSynth is a minimal but complete modular synthesis node, built entirely on the Arduino Uno.**

It’s a fixed hardware platform — 12 buttons, 4 potentiometers, 4 LEDs, 1 audio input, 1 audio output, and a 3-position switch — designed to use **every single pin** of the Arduino Uno. Nothing more, nothing less.

That’s the whole point.

## Core Architecture

- 🎛️ 12 buttons (in a 4×3 matrix)
- 🎚️ 4 potentiometers (analog inputs)
- 💡 4 LEDs (for visual feedback)
- 🎙️ 1 audio input (analog jack)
- 🔊 1 audio output (PWM jack)
- ⬆️⬇️ 1 three-position switch (used for switching “pages” or modes)

The hardware is already optimized and frozen. The soul of UnoSynth lies in the **software**.

---

## Software-defined behavior

UnoSynth is a single physical form — but it can take on dozens of sonic personalities.

- As a **granular oscillator**
- As a **modulator** or **filter**
- As a **microphone-based FX unit**
- As an **envelope generator**, **LFO**, or **mutator**
- As a **preamp**, **bit crusher**, **sequencer**, or **controller**

Each firmware defines a distinct function. Uploading a new sketch **completely transforms** what a UnoSynth does — without touching the hardware.

---

## Networked Agents

A single UnoSynth is simple.

But multiple UnoSynths — each running different firmware — become a **network of sonic agents**, capable of emergent behavior, complex audio structures, and modular systems that evolve by interconnection and mutation.

This is more than a DIY synth. It's an ecosystem of programmable, replicable, inter-operable micro-agents.

---

🌀 *One form. Infinite forms. UnoSynth.*
